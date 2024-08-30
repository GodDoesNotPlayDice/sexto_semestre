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
dias_prestados (int)
cantidad_reservas (int)
cant_prestados_semestral (int)
cant_prestado_anual (int)
cant_reservas (int) ^dpOvsCnE

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
			"version": 219,
			"versionNonce": 1374237953,
			"isDeleted": false,
			"id": "IiMhtxVibp774n1GAchnj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1182.3148595788978,
			"y": -354.50111607142856,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 385.3076923076924,
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
			"updated": 1724969861860,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 346,
			"versionNonce": 333245665,
			"isDeleted": false,
			"id": "U4hBf1Hm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1145.5203884250516,
			"y": -224.70111607142854,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 311.71875,
			"height": 134.4,
			"seed": 1723097461,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724969861860,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "D_CATEGORIA\nid_categoria (int)\nnom_categoria (str)\n",
			"rawText": "D_CATEGORIA\nid_categoria (int)\nnom_categoria (str)\n",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "IiMhtxVibp774n1GAchnj",
			"originalText": "D_CATEGORIA\nid_categoria (int)\nnom_categoria (str)\n",
			"lineHeight": 1.2,
			"baseline": 128
		},
		{
			"type": "rectangle",
			"version": 222,
			"versionNonce": 1819812929,
			"isDeleted": false,
			"id": "ek6eBsN8d_901hSTL8O-F",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -613.8785226004463,
			"y": -402.92968749999994,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 337.7998046875,
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
			"updated": 1724969858817,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 331,
			"versionNonce": 894170145,
			"isDeleted": false,
			"id": "O45gwJoo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -568.0254952566963,
			"y": -306.72968749999995,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 246.09375,
			"height": 201.60000000000002,
			"seed": 1686971643,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724969858817,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "D_LIBRO\nid_libro (int)\nautor (str)\ntitulo (str)\neditorial (str)\n",
			"rawText": "D_LIBRO\nid_libro (int)\nautor (str)\ntitulo (str)\neditorial (str)\n",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ek6eBsN8d_901hSTL8O-F",
			"originalText": "D_LIBRO\nid_libro (int)\nautor (str)\ntitulo (str)\neditorial (str)\n",
			"lineHeight": 1.2,
			"baseline": 196
		},
		{
			"type": "rectangle",
			"version": 230,
			"versionNonce": 574027905,
			"isDeleted": false,
			"id": "ba3CkhrHdYr5w-ugzviEk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -12.983371310763914,
			"y": 317.2702636718749,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 504.99993896484375,
			"height": 427.0000305175781,
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
			"updated": 1724973639585,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 367,
			"versionNonce": 749092961,
			"isDeleted": false,
			"id": "tOu1rnVz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 91.86034817165796,
			"y": 463.57027893066396,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 295.3125,
			"height": 134.4,
			"seed": 867909851,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724973639585,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "D_ALUMNO\nid_alumno (id)\nnom_completo (str)\nrut_completo (str)",
			"rawText": "D_ALUMNO\nid_alumno (id)\nnom_completo (str)\nrut_completo (str)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ba3CkhrHdYr5w-ugzviEk",
			"originalText": "D_ALUMNO\nid_alumno (id)\nnom_completo (str)\nrut_completo (str)",
			"lineHeight": 1.2,
			"baseline": 128
		},
		{
			"type": "rectangle",
			"version": 391,
			"versionNonce": 538547919,
			"isDeleted": false,
			"id": "DYyg_dK8VFWlE0cXNdFaW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -421.64042736235115,
			"y": 952.0226934523812,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 424.4667154947918,
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
			"updated": 1724969994813,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 431,
			"versionNonce": 858567983,
			"isDeleted": false,
			"id": "bQEbl6fl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -348.8601946149553,
			"y": 1081.8226934523811,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 278.90625,
			"height": 134.4,
			"seed": 441263835,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724969994813,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "D_SEDE\nid_sede (int)\nnombre_sede (str)\nnum_sede (int)",
			"rawText": "D_SEDE\nid_sede (int)\nnombre_sede (str)\nnum_sede (int)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "DYyg_dK8VFWlE0cXNdFaW",
			"originalText": "D_SEDE\nid_sede (int)\nnombre_sede (str)\nnum_sede (int)",
			"lineHeight": 1.2,
			"baseline": 128
		},
		{
			"type": "rectangle",
			"version": 411,
			"versionNonce": 1020798831,
			"isDeleted": false,
			"id": "nD64qdXgZehwMuKeQnfXE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1351.6548704117063,
			"y": 828.0752263144843,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 454.3333333333334,
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
			"updated": 1724969987816,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 464,
			"versionNonce": 358572431,
			"isDeleted": false,
			"id": "csUtj2RJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1280.3475787450395,
			"y": 974.6752263144843,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 311.71875,
			"height": 100.80000000000001,
			"seed": 262007445,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724969987816,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "D_COMUNA\nid_comuna (int)\nnombre_comuna (str)",
			"rawText": "D_COMUNA\nid_comuna (int)\nnombre_comuna (str)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "nD64qdXgZehwMuKeQnfXE",
			"originalText": "D_COMUNA\nid_comuna (int)\nnombre_comuna (str)",
			"lineHeight": 1.2,
			"baseline": 95
		},
		{
			"type": "rectangle",
			"version": 333,
			"versionNonce": 1944352047,
			"isDeleted": false,
			"id": "O5uoqU4i3wlHt_94EKCt8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -127.37449392712551,
			"y": -224.50020274156225,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 332.9998779296875,
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
			"updated": 1724969888870,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 373,
			"versionNonce": 83079055,
			"isDeleted": false,
			"id": "RWI39Yd2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -67.51517996228176,
			"y": -94.70020274156225,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 213.28125,
			"height": 134.4,
			"seed": 2105218965,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724969888871,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "D_TIPO\nid_tipo (int)\nn_tipo (str)\n",
			"rawText": "D_TIPO\nid_tipo (int)\nn_tipo (str)\n",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "O5uoqU4i3wlHt_94EKCt8",
			"originalText": "D_TIPO\nid_tipo (int)\nn_tipo (str)\n",
			"lineHeight": 1.2,
			"baseline": 128
		},
		{
			"type": "rectangle",
			"version": 479,
			"versionNonce": 219775745,
			"isDeleted": false,
			"id": "tmCAHfvSRssbh_OzPg_4D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1327.067241161987,
			"y": 155.2994828379542,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 328.2000732421875,
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
			"updated": 1724969864368,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 577,
			"versionNonce": 1607695073,
			"isDeleted": false,
			"id": "7usnpMN6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1277.8109545408934,
			"y": 251.4994828379542,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 229.6875,
			"height": 201.60000000000002,
			"seed": 432905013,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724969864368,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "D_TIEMPO\nFecha (date)\nDia (int)\nMes (int)\nAño (int)\nSemestre (int)",
			"rawText": "D_TIEMPO\nFecha (date)\nDia (int)\nMes (int)\nAño (int)\nSemestre (int)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "tmCAHfvSRssbh_OzPg_4D",
			"originalText": "D_TIEMPO\nFecha (date)\nDia (int)\nMes (int)\nAño (int)\nSemestre (int)",
			"lineHeight": 1.2,
			"baseline": 196
		},
		{
			"type": "rectangle",
			"version": 506,
			"versionNonce": 1293635393,
			"isDeleted": false,
			"id": "F5Y9ekIKnkSRXCkcVVzft",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -819.1398574969328,
			"y": 148.9947431240863,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 546.9811042906741,
			"height": 594.4667697482639,
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
			"updated": 1724973650993,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1087,
			"versionNonce": 746756783,
			"isDeleted": false,
			"id": "dpOvsCnE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -791.7430553515958,
			"y": 177.42812799821826,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 492.1875,
			"height": 537.6,
			"seed": 127863707,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724973672357,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "H_PRESTAMO\nid_alumno (int)\nid_sede (int)\nid_comuna (int)\nid_categoria (int)\nid_libro (int)\nid_tipo (int)\nfecha (date)\n\ncant_libros_prestados (int)\ndias_retraso (int)\ndias_prestados (int)\ncantidad_reservas (int)\ncant_prestados_semestral (int)\ncant_prestado_anual (int)\ncant_reservas (int)",
			"rawText": "H_PRESTAMO\nid_alumno (int)\nid_sede (int)\nid_comuna (int)\nid_categoria (int)\nid_libro (int)\nid_tipo (int)\nfecha (date)\n\ncant_libros_prestados (int)\ndias_retraso (int)\ndias_prestados (int)\ncantidad_reservas (int)\ncant_prestados_semestral (int)\ncant_prestado_anual (int)\ncant_reservas (int)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "F5Y9ekIKnkSRXCkcVVzft",
			"originalText": "H_PRESTAMO\nid_alumno (int)\nid_sede (int)\nid_comuna (int)\nid_categoria (int)\nid_libro (int)\nid_tipo (int)\nfecha (date)\n\ncant_libros_prestados (int)\ndias_retraso (int)\ndias_prestados (int)\ncantidad_reservas (int)\ncant_prestados_semestral (int)\ncant_prestado_anual (int)\ncant_reservas (int)",
			"lineHeight": 1.2,
			"baseline": 531
		},
		{
			"type": "arrow",
			"version": 589,
			"versionNonce": 97617551,
			"isDeleted": false,
			"id": "JI-ro4-ihYKwSh7p7Bshd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -847.8884523394763,
			"y": 51.03367544625982,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 79.9479429922327,
			"height": 84.15154386830281,
			"seed": 1877659317,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724973673351,
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
					79.9479429922327,
					84.15154386830281
				]
			]
		},
		{
			"type": "arrow",
			"version": 600,
			"versionNonce": 636601615,
			"isDeleted": false,
			"id": "1QHd4Sb7ItrYhWCZMqDti",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -450.09222931255124,
			"y": 4.651961936090203,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.881387838934529,
			"height": 132.1999240451391,
			"seed": 1296524859,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724973673351,
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
					-3.881387838934529,
					132.1999240451391
				]
			]
		},
		{
			"type": "arrow",
			"version": 523,
			"versionNonce": 696323407,
			"isDeleted": false,
			"id": "aJwq4Iu1sf-_5h3ge77d2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -137.24051314182296,
			"y": 158.42927281822656,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 127.28331942950868,
			"height": 76.24045139731467,
			"seed": 30167285,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724973673351,
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
					-127.28331942950868,
					76.24045139731467
				]
			]
		},
		{
			"type": "arrow",
			"version": 643,
			"versionNonce": 1401636239,
			"isDeleted": false,
			"id": "Vc3_LAQZZjpOPHIDQa3tF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -26.537987016689385,
			"y": 444.9242466711494,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 233.652512221309,
			"height": 6.764196972271179,
			"seed": 1977487355,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724973673351,
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
					-233.652512221309,
					-6.764196972271179
				]
			]
		},
		{
			"type": "arrow",
			"version": 751,
			"versionNonce": 370437583,
			"isDeleted": false,
			"id": "JEPdUVf1PD-Gj0ZDpUJXI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -189.68403902976542,
			"y": 940.6519619360905,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 105.6143412537021,
			"height": 183.33330620659729,
			"seed": 1541510677,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724973673351,
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
					-105.6143412537021,
					-183.33330620659729
				]
			]
		},
		{
			"type": "arrow",
			"version": 665,
			"versionNonce": 840992271,
			"isDeleted": false,
			"id": "SouqcSUsaOZHLr3CbJKdp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1123.0644270117255,
			"y": 806.585447179146,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 285.06758343856995,
			"height": 121.6449071337446,
			"seed": 1334621755,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724973673351,
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
					285.06758343856995,
					-121.6449071337446
				]
			]
		},
		{
			"type": "arrow",
			"version": 723,
			"versionNonce": 2008256079,
			"isDeleted": false,
			"id": "yEULiIL_wxZvpA8BGF0xZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -992.8046157059257,
			"y": 358.62213403632995,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 162.01396455820543,
			"height": 40.70896462582459,
			"seed": 1364030069,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724973673351,
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
					162.01396455820543,
					40.70896462582459
				]
			]
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
		"currentItemFontSize": 28,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 1961.527593219091,
		"scrollY": 465.45355127728163,
		"zoom": {
			"value": 0.45
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