## Escaneo en la red

```bash
sudo arp-scan 10.10.12.1/24 
```

```
Interface: eth0, type: EN10MB, MAC: 08:00:27:53:0c:ba, IPv4: 10.10.12.5
WARNING: Cannot open MAC/Vendor file ieee-oui.txt: Permission denied
WARNING: Cannot open MAC/Vendor file mac-vendor.txt: Permission denied
WARNING: host part of 10.10.12.1/24 is non-zero
Starting arp-scan 1.10.0 with 256 hosts (https://github.com/royhills/arp-scan)
10.10.12.1      52:54:00:12:35:00       (Unknown: locally administered)
10.10.12.2      52:54:00:12:35:00       (Unknown: locally administered)
10.10.12.3      08:00:27:1c:e5:3e       (Unknown)
10.10.12.6      08:00:27:0a:8a:1e       (Unknown)

4 packets received by filter, 0 packets dropped by kernel
Ending arp-scan 1.10.0: 256 hosts scanned in 1.870 seconds (136.90 hosts/sec). 4 responded
```

## Escaneo de puertos y servicios

```bash
sudo nmap -sV 10.10.12.6 # tambien es 12.7 porque tuve que restaurar la maquina
```

```
PORT     STATE  SERVICE     VERSION
21/tcp   open   ftp         ProFTPD 1.3.5
22/tcp   open   ssh         OpenSSH 6.6.1p1 Ubuntu 2ubuntu2.13 (Ubuntu Linux; protocol 2.0)
80/tcp   open   http        Apache httpd 2.4.7
445/tcp  open   netbios-ssn Samba smbd 3.X - 4.X (workgroup: WORKGROUP)
631/tcp  open   ipp         CUPS 1.7
3000/tcp closed ppp
3306/tcp open   mysql       MySQL (unauthorized)
8080/tcp open   http        Jetty 8.1.7.v20120910
8181/tcp closed intermapper
Service Info: Hosts: 127.0.1.1, PRUEBA2; OSs: Unix, Linux; CPE: cpe:/o:linux:linux_kernel
```

## Escaneo de vulnerabilidades con NSE
```bash
nmap -sV --script vuln 10.10.12.6
```
[[Vulns]] -> Lista de vulnerabilidades

**ProFTPD 1.3.5** (CVE-2015-3306) ->  https://vulners.com/saint/SAINT:FD1752E124A72FD3A26EEB9B315E8382 

## Vulnerabilidades explotadas

### ProFTPD 1.3.5 (CVE-2015-3306)
La vulnerabilidad **CVE-2015-3306** afecta a **ProFTPD**, un servidor FTP ampliamente utilizado. Esta vulnerabilidad permite a atacantes remotos ejecutar código arbitrario en el servidor mediante una técnica de inyección de comandos a través del módulo **mod_copy** de ProFTPD.
#### Detalles de la vulnerabilidad
1. **Causa**: La vulnerabilidad se debe a la falta de validación adecuada en el módulo `mod_copy`, que permite realizar operaciones de copia de archivos en el servidor.
2. **Inyección de comandos**: Un atacante puede aprovechar esta falla para inyectar comandos maliciosos en solicitudes FTP mediante el uso de la funcionalidad `SITE CPFR` y `SITE CPTO` del módulo `mod_copy`.
3. **Impacto**: Si tiene éxito, un atacante podría ejecutar comandos arbitrarios en el sistema, logrando así acceso no autorizado y potencialmente comprometiendo la integridad, confidencialidad y disponibilidad del sistema afectado.

![[Pasted image 20241103140620.png]]

```shell
msfconsole -q # uso de metasploit para explotar la vulnerabilidad
```

```bash
msf > use exploit/unix/ftp/proftpd_modcopy_exec # Seleccion del exploit
```

Se hace configuración de las opciones.

![[Pasted image 20241103140954.png]]

Se explota la vulnerabilidad obteniendo usuario **_(www-data)_**

![[Pasted image 20241103141133.png]]

#### Dato encontrado para la explotación de Apache
Se encuentra el folder **cgi-bin** con el script **hello_world.sh**

![[Pasted image 20241103180608.png]]

### Apache httpd 2.4.7 (CVE-2014-6271)
- **Descripción**: Shellshock es una vulnerabilidad crítica en Bash que permite a un atacante ejecutar comandos en sistemas donde Bash interpreta las variables de entorno. Cuando se explotan ciertos scripts CGI en servidores Apache con módulos vulnerables como `mod_cgi`, un atacante puede aprovechar esta vulnerabilidad para ejecutar código remoto.
- **Impacto**: Ejecución de código remoto (RCE), lo que permite al atacante tomar control del sistema comprometido.
- **Explotación**: Los atacantes pueden explotar esta vulnerabilidad en servidores web configurados para usar Bash en scripts CGI. Enviar una solicitud HTTP manipulada puede activar la ejecución de comandos maliciosos.

**(CVE-2014-6271)** -> https://www.rapid7.com/db/modules/exploit/multi/http/apache_mod_cgi_bash_env_exec/


```shell
msfconsole -q # uso de metasploit para explotar la vulnerabilidad
```

```bash
msf > use multi/http/apache_mod_cgi_bash_env_exec # Seleccion del exploit
```

Se cambia el **TARGETURI** por el **hello_world.sh** encontrado anteriormente.

![[Pasted image 20241103175659.png]]

Se explota la vulnerabilidad.
![[Pasted image 20241103180903.png]]


### Drupal (CVE-2014-3704)
- **Descripción**: Esta vulnerabilidad es una inyección SQL crítica en el núcleo de Drupal. Permite a un atacante enviar una solicitud maliciosa que manipula consultas SQL, lo que puede llevar a la ejecución de código PHP en el servidor.
- **Impacto**: Ejecución remota de código (RCE), lo que da acceso completo al sistema comprometido.
- **Explotación**: Un atacante puede ejecutar comandos maliciosos de forma remota y sin autenticación, comprometiendo completamente el servidor donde está instalado Drupal.

**(CVE-2014-3704)** -> https://www.rapid7.com/db/modules/exploit/multi/http/drupal_drupageddon/

```shell
msfconsole -q # uso de metasploit para explotar la vulnerabilidad
```

```bash
msf > use multi/http/drupal_drupageddon
```

Primero cambiamos el TARGETURI -> **/drupal/**

![[Pasted image 20241103181854.png]]

Se explota la vulnerabilidad.
![[Pasted image 20241103182100.png]]
### Escalada de privilegios
```bash
find / -perm -4000 -type f 2>/dev/null
```

Se buscan permisos **SUID**, pero no se encuentran permisos suficientes para explotar.
https://gtfobins.github.io/

```
/bin/umount
/bin/mount
/bin/su
/bin/fusermount
/usr/bin/lppasswd
/usr/bin/mtr
/usr/bin/pkexec
/usr/bin/chfn
/usr/bin/passwd
/usr/bin/sudo
/usr/bin/newgrp
/usr/bin/gpasswd
/usr/bin/chsh
/usr/bin/traceroute6.iputils
/usr/sbin/uuidd
/usr/sbin/pppd
/usr/lib/eject/dmcrypt-get-device
/usr/lib/openssh/ssh-keysign
/usr/lib/dbus-1.0/dbus-daemon-launch-helper
/usr/lib/policykit-1/polkit-agent-helper-1
/usr/lib/pt_chown
/sbin/mount.nfs
```

Se revisa la version del kernel.
```bash
uname -a
```

```
3.13.0-24-generic
```

la vulnerabilidad encontrada y explotada es la **(2015-1328)** _"'overlayfs' Local Privilege Escalation"_ -> https://www.exploit-db.com/exploits/37292

Se hace creo **ofs.c**
![[Pasted image 20241103170356.png]]

Para posterior descargarlo en la maquina victima, compilar y ejecutar, como resultado da una escalada de privilegios de **www-data** -> **root**

![[Pasted image 20241103170523.png]]
