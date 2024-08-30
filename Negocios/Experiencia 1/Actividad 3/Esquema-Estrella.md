---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
D_LIBRO
id_libro (int)
autor (str)
titulo (str)
editorial (str)
 ^O45gwJoo

D_CATEGORIA
id_categoria (int)
nom_categoria (str)
 ^U4hBf1Hm

D_ALUMNO
id_alumno (id)
nom_completo (str)
rut_completo (str) ^tOu1rnVz

D_SEDE
id_sede (int)
nombre_sede (str)
num_sede (int) ^bQEbl6fl

D_COMUNA
id_comuna (int)
nombre_comuna (str) ^csUtj2RJ

D_TIPO
id_tipo (int)
n_tipo (str)
 ^RWI39Yd2

D_TIEMPO
Fecha (date)
Dia (int)
Mes (int)
Año (int)
Semestre (int) ^7usnpMN6

H_PRESTAMO
id_alumno (int)
id_sede (int)
id_comuna (int)
id_categoria (int)
id_libro (int)
id_tipo (int)
fecha (date)

cant_libros_prestados (int)
dias_retraso (int)
dias_prestados (int) ^dpOvsCnE

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.23",
	"elements": [
		{
			"type": "rectangle",
			"version": 171,
			"versionNonce": 1991178395,
			"isDeleted": false,
			"id": "IiMhtxVibp774n1GAchnj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1095.9148351648353,
			"y": -330.50111607142856,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 277.3076923076924,
			"height": 394,
			"seed": 1147412827,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "U4hBf1Hm"
				},
				{
					"id": "JI-ro4-ihYKwSh7p7Bshd",
					"type": "arrow"
				}
			],
			"updated": 1724978915809,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 211,
			"versionNonce": 1981752149,
			"isDeleted": false,
			"id": "U4hBf1Hm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1068.589114010989,
			"y": -181.50111607142856,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 222.65625,
			"height": 96,
			"seed": 1723097461,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724979096809,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "D_CATEGORIA\nid_categoria (int)\nnom_categoria (str)\n",
			"rawText": "D_CATEGORIA\nid_categoria (int)\nnom_categoria (str)\n",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "IiMhtxVibp774n1GAchnj",
			"originalText": "D_CATEGORIA\nid_categoria (int)\nnom_categoria (str)\n",
			"lineHeight": 1.2,
			"baseline": 91
		},
		{
			"type": "rectangle",
			"version": 177,
			"versionNonce": 296967765,
			"isDeleted": false,
			"id": "ek6eBsN8d_901hSTL8O-F",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -582.6785714285713,
			"y": -330.92968749999994,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 225,
			"height": 394,
			"seed": 1663192533,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "O45gwJoo"
				},
				{
					"id": "1QHd4Sb7ItrYhWCZMqDti",
					"type": "arrow"
				}
			],
			"updated": 1724978914762,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 214,
			"versionNonce": 1866918261,
			"isDeleted": false,
			"id": "O45gwJoo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -558.0691964285713,
			"y": -205.92968749999994,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 175.78125,
			"height": 144,
			"seed": 1686971643,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724979121998,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "D_LIBRO\nid_libro (int)\nautor (str)\ntitulo (str)\neditorial (str)\n",
			"rawText": "D_LIBRO\nid_libro (int)\nautor (str)\ntitulo (str)\neditorial (str)\n",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ek6eBsN8d_901hSTL8O-F",
			"originalText": "D_LIBRO\nid_libro (int)\nautor (str)\ntitulo (str)\neditorial (str)\n",
			"lineHeight": 1.2,
			"baseline": 139
		},
		{
			"type": "rectangle",
			"version": 181,
			"versionNonce": 1023292416,
			"isDeleted": false,
			"id": "ba3CkhrHdYr5w-ugzviEk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -141.25,
			"y": 332.73697916666663,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 421,
			"height": 394,
			"seed": 1336999995,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "tOu1rnVz"
				},
				{
					"id": "Vc3_LAQZZjpOPHIDQa3tF",
					"type": "arrow"
				}
			],
			"updated": 1724979175125,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 306,
			"versionNonce": 1618054144,
			"isDeleted": false,
			"id": "tOu1rnVz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -36.21875,
			"y": 481.73697916666663,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 210.9375,
			"height": 96,
			"seed": 867909851,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724979226071,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "D_ALUMNO\nid_alumno (id)\nnom_completo (str)\nrut_completo (str)",
			"rawText": "D_ALUMNO\nid_alumno (id)\nnom_completo (str)\nrut_completo (str)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ba3CkhrHdYr5w-ugzviEk",
			"originalText": "D_ALUMNO\nid_alumno (id)\nnom_completo (str)\nrut_completo (str)",
			"lineHeight": 1.2,
			"baseline": 91
		},
		{
			"type": "rectangle",
			"version": 328,
			"versionNonce": 1771015168,
			"isDeleted": false,
			"id": "DYyg_dK8VFWlE0cXNdFaW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -535.7738095238094,
			"y": 752.0226934523812,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 359.66666666666674,
			"height": 394,
			"seed": 1812440635,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "bQEbl6fl"
				},
				{
					"id": "JEPdUVf1PD-Gj0ZDpUJXI",
					"type": "arrow"
				}
			],
			"updated": 1724979403267,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 359,
			"versionNonce": 11209728,
			"isDeleted": false,
			"id": "bQEbl6fl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -455.54985119047603,
			"y": 901.0226934523812,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 199.21875,
			"height": 96,
			"seed": 441263835,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724979403268,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "D_SEDE\nid_sede (int)\nnombre_sede (str)\nnum_sede (int)",
			"rawText": "D_SEDE\nid_sede (int)\nnombre_sede (str)\nnum_sede (int)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "DYyg_dK8VFWlE0cXNdFaW",
			"originalText": "D_SEDE\nid_sede (int)\nnombre_sede (str)\nnum_sede (int)",
			"lineHeight": 1.2,
			"baseline": 91
		},
		{
			"type": "rectangle",
			"version": 350,
			"versionNonce": 830835712,
			"isDeleted": false,
			"id": "nD64qdXgZehwMuKeQnfXE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1043.654761904762,
			"y": 733.1417410714289,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 346.3333333333334,
			"height": 394,
			"seed": 1791285557,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "csUtj2RJ"
				},
				{
					"id": "SouqcSUsaOZHLr3CbJKdp",
					"type": "arrow"
				}
			],
			"updated": 1724979411709,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 393,
			"versionNonce": 73468928,
			"isDeleted": false,
			"id": "csUtj2RJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -981.8162202380952,
			"y": 894.1417410714289,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 222.65625,
			"height": 72,
			"seed": 262007445,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724979411711,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "D_COMUNA\nid_comuna (int)\nnombre_comuna (str)",
			"rawText": "D_COMUNA\nid_comuna (int)\nnombre_comuna (str)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "nD64qdXgZehwMuKeQnfXE",
			"originalText": "D_COMUNA\nid_comuna (int)\nnombre_comuna (str)",
			"lineHeight": 1.2,
			"baseline": 67
		},
		{
			"type": "rectangle",
			"version": 307,
			"versionNonce": 450175029,
			"isDeleted": false,
			"id": "O5uoqU4i3wlHt_94EKCt8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -127.37449392712551,
			"y": -221.50024851792944,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 225,
			"height": 394,
			"seed": 1879287349,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "RWI39Yd2"
				},
				{
					"id": "aJwq4Iu1sf-_5h3ge77d2",
					"type": "arrow"
				}
			],
			"updated": 1724978998428,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 335,
			"versionNonce": 1395493888,
			"isDeleted": false,
			"id": "RWI39Yd2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -91.04636892712551,
			"y": -72.50024851792944,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 152.34375,
			"height": 96,
			"seed": 2105218965,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724979146149,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "D_TIPO\nid_tipo (int)\nn_tipo (str)\n",
			"rawText": "D_TIPO\nid_tipo (int)\nn_tipo (str)\n",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "O5uoqU4i3wlHt_94EKCt8",
			"originalText": "D_TIPO\nid_tipo (int)\nn_tipo (str)\n",
			"lineHeight": 1.2,
			"baseline": 91
		},
		{
			"type": "rectangle",
			"version": 420,
			"versionNonce": 1134932992,
			"isDeleted": false,
			"id": "tmCAHfvSRssbh_OzPg_4D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1223.8671679197996,
			"y": 169.69938518170426,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 225,
			"height": 394,
			"seed": 1615207893,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "7usnpMN6"
				},
				{
					"id": "yEULiIL_wxZvpA8BGF0xZ",
					"type": "arrow"
				}
			],
			"updated": 1724979327295,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 478,
			"versionNonce": 751776768,
			"isDeleted": false,
			"id": "7usnpMN6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1193.3984179197996,
			"y": 294.69938518170426,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 164.0625,
			"height": 144,
			"seed": 432905013,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724979327295,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "D_TIEMPO\nFecha (date)\nDia (int)\nMes (int)\nAño (int)\nSemestre (int)",
			"rawText": "D_TIEMPO\nFecha (date)\nDia (int)\nMes (int)\nAño (int)\nSemestre (int)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "tmCAHfvSRssbh_OzPg_4D",
			"originalText": "D_TIEMPO\nFecha (date)\nDia (int)\nMes (int)\nAño (int)\nSemestre (int)",
			"lineHeight": 1.2,
			"baseline": 139
		},
		{
			"type": "rectangle",
			"version": 392,
			"versionNonce": 1527614464,
			"isDeleted": false,
			"id": "F5Y9ekIKnkSRXCkcVVzft",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -757.5397869674189,
			"y": 213.7948190789474,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 410.7142857142855,
			"height": 394,
			"seed": 15147771,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "dpOvsCnE"
				},
				{
					"id": "1QHd4Sb7ItrYhWCZMqDti",
					"type": "arrow"
				},
				{
					"id": "aJwq4Iu1sf-_5h3ge77d2",
					"type": "arrow"
				},
				{
					"id": "Vc3_LAQZZjpOPHIDQa3tF",
					"type": "arrow"
				},
				{
					"id": "JEPdUVf1PD-Gj0ZDpUJXI",
					"type": "arrow"
				},
				{
					"id": "SouqcSUsaOZHLr3CbJKdp",
					"type": "arrow"
				},
				{
					"id": "yEULiIL_wxZvpA8BGF0xZ",
					"type": "arrow"
				},
				{
					"id": "JI-ro4-ihYKwSh7p7Bshd",
					"type": "arrow"
				}
			],
			"updated": 1724979817649,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 768,
			"versionNonce": 1796289536,
			"isDeleted": false,
			"id": "dpOvsCnE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -710.3857691102761,
			"y": 266.7948190789474,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 316.40625,
			"height": 288,
			"seed": 127863707,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724980375701,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "H_PRESTAMO\nid_alumno (int)\nid_sede (int)\nid_comuna (int)\nid_categoria (int)\nid_libro (int)\nid_tipo (int)\nfecha (date)\n\ncant_libros_prestados (int)\ndias_retraso (int)\ndias_prestados (int)",
			"rawText": "H_PRESTAMO\nid_alumno (int)\nid_sede (int)\nid_comuna (int)\nid_categoria (int)\nid_libro (int)\nid_tipo (int)\nfecha (date)\n\ncant_libros_prestados (int)\ndias_retraso (int)\ndias_prestados (int)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "F5Y9ekIKnkSRXCkcVVzft",
			"originalText": "H_PRESTAMO\nid_alumno (int)\nid_sede (int)\nid_comuna (int)\nid_categoria (int)\nid_libro (int)\nid_tipo (int)\nfecha (date)\n\ncant_libros_prestados (int)\ndias_retraso (int)\ndias_prestados (int)",
			"lineHeight": 1.2,
			"baseline": 283
		},
		{
			"type": "arrow",
			"version": 109,
			"versionNonce": 37729280,
			"isDeleted": false,
			"id": "JI-ro4-ihYKwSh7p7Bshd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -813.2055484667569,
			"y": 73.69075291312419,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 116.92389855420583,
			"height": 126.2945423562995,
			"seed": 1877659317,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724980376571,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "IiMhtxVibp774n1GAchnj",
				"gap": 11.534791517688433,
				"focus": 0.14878195832646238
			},
			"endBinding": {
				"elementId": "F5Y9ekIKnkSRXCkcVVzft",
				"gap": 13.80952380952371,
				"focus": 0.13170961768054304
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					116.92389855420583,
					126.2945423562995
				]
			]
		},
		{
			"type": "arrow",
			"version": 98,
			"versionNonce": 112047104,
			"isDeleted": false,
			"id": "1QHd4Sb7ItrYhWCZMqDti",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -477.35811878666345,
			"y": 76.65196193609029,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.698127981078471,
			"height": 125.00000000000011,
			"seed": 1296524859,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724980376569,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ek6eBsN8d_901hSTL8O-F",
				"gap": 13.581649436090174,
				"focus": -0.006103113414183531
			},
			"endBinding": {
				"elementId": "F5Y9ekIKnkSRXCkcVVzft",
				"gap": 12.142857142856997,
				"focus": 0.29265534184196207
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-4.698127981078471,
					125.00000000000011
				]
			]
		},
		{
			"type": "arrow",
			"version": 99,
			"versionNonce": 1439740928,
			"isDeleted": false,
			"id": "aJwq4Iu1sf-_5h3ge77d2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -137.24051314182296,
			"y": 123.4966792974609,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 201.95006747638328,
			"height": 125.05413852058095,
			"seed": 30167285,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724980376569,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "O5uoqU4i3wlHt_94EKCt8",
				"gap": 9.866019214697417,
				"focus": -0.27084233301726557
			},
			"endBinding": {
				"elementId": "F5Y9ekIKnkSRXCkcVVzft",
				"gap": 7.634920634927113,
				"focus": -0.09363255354294837
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-201.95006747638328,
					125.05413852058095
				]
			]
		},
		{
			"type": "arrow",
			"version": 139,
			"versionNonce": 2016654336,
			"isDeleted": false,
			"id": "Vc3_LAQZZjpOPHIDQa3tF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -154.80461570592544,
			"y": 433.9826828554442,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 180.05263157894754,
			"height": 15.718576400275765,
			"seed": 1977487355,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724980376570,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ba3CkhrHdYr5w-ugzviEk",
				"gap": 13.554615705925443,
				"focus": 0.35377213972973526
			},
			"endBinding": {
				"elementId": "F5Y9ekIKnkSRXCkcVVzft",
				"gap": 11.96825396826037,
				"focus": -0.053521253428085856
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-180.05263157894754,
					-15.718576400275765
				]
			]
		},
		{
			"type": "arrow",
			"version": 245,
			"versionNonce": 500610048,
			"isDeleted": false,
			"id": "JEPdUVf1PD-Gj0ZDpUJXI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -340.1759401268546,
			"y": 740.6519619360905,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 58.996984681052254,
			"height": 119.00000000000011,
			"seed": 1541510677,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724980376570,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "DYyg_dK8VFWlE0cXNdFaW",
				"gap": 11.370731516290675,
				"focus": 0.4290748618539196
			},
			"endBinding": {
				"elementId": "F5Y9ekIKnkSRXCkcVVzft",
				"gap": 13.857142857142975,
				"focus": -0.15996217441058241
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-58.996984681052254,
					-119.00000000000011
				]
			]
		},
		{
			"type": "arrow",
			"version": 163,
			"versionNonce": 1991881728,
			"isDeleted": false,
			"id": "SouqcSUsaOZHLr3CbJKdp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -884.5710411713048,
			"y": 711.6519619360905,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 134.04643350909373,
			"height": 85.0001567809204,
			"seed": 1334621755,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724980376571,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "nD64qdXgZehwMuKeQnfXE",
				"gap": 21.48977913533838,
				"focus": -0.7412487251151996
			},
			"endBinding": {
				"elementId": "F5Y9ekIKnkSRXCkcVVzft",
				"gap": 18.856986076222682,
				"focus": -0.2753092281211788
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					134.04643350909373,
					-85.0001567809204
				]
			]
		},
		{
			"type": "arrow",
			"version": 211,
			"versionNonce": 853324800,
			"isDeleted": false,
			"id": "yEULiIL_wxZvpA8BGF0xZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -992.8046157059258,
			"y": 353.38092406563925,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 223.61403508771957,
			"height": 37.06729750503143,
			"seed": 1364030069,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724980376571,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "tmCAHfvSRssbh_OzPg_4D",
				"gap": 6.062552213873801,
				"focus": -0.1528966579975723
			},
			"endBinding": {
				"elementId": "F5Y9ekIKnkSRXCkcVVzft",
				"gap": 11.650793650787392,
				"focus": -0.06763148472867372
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					223.61403508771957,
					37.06729750503143
				]
			]
		},
		{
			"id": "GTImDjoe",
			"type": "text",
			"x": -211.45416425679446,
			"y": -21.44438244047609,
			"width": 11.71875,
			"height": 24,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1765149696,
			"version": 4,
			"versionNonce": 1842164736,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1724979154661,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 19,
			"containerId": null,
			"originalText": "",
			"lineHeight": 1.2
		}
	],
	"appState": {
		"theme": "dark",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 3,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 1723.8340913472496,
		"scrollY": 136.08335202352538,
		"zoom": {
			"value": 0.55
		},
		"currentItemRoundness": "sharp",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%