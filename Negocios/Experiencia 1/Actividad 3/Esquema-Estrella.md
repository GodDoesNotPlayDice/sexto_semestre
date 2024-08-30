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
comuna (str)
num_sede (int) ^bQEbl6fl

D_CARRERA
id_carrera (int)
nombre_carrera (str) ^csUtj2RJ

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
			"version": 220,
			"versionNonce": 1695801079,
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
			"updated": 1724991921977,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 347,
			"versionNonce": 232189945,
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
			"updated": 1724991921977,
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
			"version": 223,
			"versionNonce": 323676183,
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
			"updated": 1724991921977,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 332,
			"versionNonce": 1229490393,
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
			"updated": 1724991921977,
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
			"version": 231,
			"versionNonce": 872664375,
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
			"updated": 1724991921977,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 368,
			"versionNonce": 1490290105,
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
			"updated": 1724991921978,
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
			"version": 392,
			"versionNonce": 1386417751,
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
			"updated": 1724991921978,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 448,
			"versionNonce": 1738335897,
			"isDeleted": false,
			"id": "bQEbl6fl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -348.8601946149553,
			"y": 1065.0226934523812,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 278.90625,
			"height": 168,
			"seed": 441263835,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724991921978,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "D_SEDE\nid_sede (int)\nnombre_sede (str)\ncomuna (str)\nnum_sede (int)",
			"rawText": "D_SEDE\nid_sede (int)\nnombre_sede (str)\ncomuna (str)\nnum_sede (int)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "DYyg_dK8VFWlE0cXNdFaW",
			"originalText": "D_SEDE\nid_sede (int)\nnombre_sede (str)\ncomuna (str)\nnum_sede (int)",
			"lineHeight": 1.2,
			"baseline": 162
		},
		{
			"type": "rectangle",
			"version": 422,
			"versionNonce": 436022135,
			"isDeleted": false,
			"id": "nD64qdXgZehwMuKeQnfXE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1383.654789031498,
			"y": 830.7419201078872,
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
			"updated": 1724991921978,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 543,
			"versionNonce": 1904649559,
			"isDeleted": false,
			"id": "csUtj2RJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1320.5506223648313,
			"y": 977.3419201078872,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 328.125,
			"height": 100.80000000000001,
			"seed": 262007445,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724992138204,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "D_CARRERA\nid_carrera (int)\nnombre_carrera (str)",
			"rawText": "D_CARRERA\nid_carrera (int)\nnombre_carrera (str)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "nD64qdXgZehwMuKeQnfXE",
			"originalText": "D_CARRERA\nid_carrera (int)\nnombre_carrera (str)",
			"lineHeight": 1.2,
			"baseline": 95
		},
		{
			"type": "rectangle",
			"version": 334,
			"versionNonce": 1716954263,
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
			"updated": 1724991921978,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 374,
			"versionNonce": 1262802009,
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
			"updated": 1724991921978,
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
			"version": 490,
			"versionNonce": 392427959,
			"isDeleted": false,
			"id": "tmCAHfvSRssbh_OzPg_4D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1404.4005473685843,
			"y": 171.2995099646904,
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
			"updated": 1724991921978,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 588,
			"versionNonce": 2084233529,
			"isDeleted": false,
			"id": "7usnpMN6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1355.1442607474905,
			"y": 267.4995099646904,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 229.6875,
			"height": 201.60000000000002,
			"seed": 432905013,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724991921978,
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
			"version": 507,
			"versionNonce": 575253207,
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
			"updated": 1724991921978,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1088,
			"versionNonce": 1083986457,
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
			"updated": 1724991921978,
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
			"version": 602,
			"versionNonce": 517102265,
			"isDeleted": false,
			"id": "JI-ro4-ihYKwSh7p7Bshd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -847.9953923217814,
			"y": 51.03367544625985,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 79.97321828165411,
			"height": 84.15154386830278,
			"seed": 1877659317,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724992295351,
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
					79.97321828165411,
					84.15154386830278
				]
			]
		},
		{
			"type": "arrow",
			"version": 613,
			"versionNonce": 337299513,
			"isDeleted": false,
			"id": "1QHd4Sb7ItrYhWCZMqDti",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -450.09432231939246,
			"y": 4.651961936090231,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.8808643530094855,
			"height": 132.19992404513914,
			"seed": 1296524859,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724992295350,
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
					-3.8808643530094855,
					132.19992404513914
				]
			]
		},
		{
			"type": "arrow",
			"version": 536,
			"versionNonce": 766430713,
			"isDeleted": false,
			"id": "aJwq4Iu1sf-_5h3ge77d2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -137.24051314182296,
			"y": 158.4803596735821,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 127.28331942950868,
			"height": 76.22546923451065,
			"seed": 30167285,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724992295350,
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
					76.22546923451065
				]
			]
		},
		{
			"type": "arrow",
			"version": 656,
			"versionNonce": 785146809,
			"isDeleted": false,
			"id": "Vc3_LAQZZjpOPHIDQa3tF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -26.537987016689385,
			"y": 444.9403216097498,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 233.65251222130894,
			"height": 6.771642255012864,
			"seed": 1977487355,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724992295350,
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
					-233.65251222130894,
					-6.771642255012864
				]
			]
		},
		{
			"type": "arrow",
			"version": 768,
			"versionNonce": 900834775,
			"isDeleted": false,
			"id": "JEPdUVf1PD-Gj0ZDpUJXI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -189.68590200544259,
			"y": 940.6519619360905,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 105.61371106101086,
			"height": 183.33330620659717,
			"seed": 1541510677,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724992333065,
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
					-105.61371106101086,
					-183.33330620659717
				]
			]
		},
		{
			"type": "arrow",
			"version": 717,
			"versionNonce": 1007959865,
			"isDeleted": false,
			"id": "SouqcSUsaOZHLr3CbJKdp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1149.7850701850484,
			"y": 809.2521409725488,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 311.7882266118928,
			"height": 129.0384748275518,
			"seed": 1334621755,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724992295351,
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
					311.7882266118928,
					-129.0384748275518
				]
			]
		},
		{
			"type": "arrow",
			"version": 764,
			"versionNonce": 1626768633,
			"isDeleted": false,
			"id": "yEULiIL_wxZvpA8BGF0xZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1070.1379219125229,
			"y": 366.73401209344047,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 239.34727076480272,
			"height": 47.111686822000024,
			"seed": 1364030069,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724992295351,
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
					239.34727076480272,
					47.111686822000024
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
		"scrollX": 1491.4345654782458,
		"scrollY": -285.4438930972595,
		"zoom": {
			"value": 0.6500000000000001
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