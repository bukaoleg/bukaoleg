{
	"name": "Deploy Compromised Device Detection Method (M1010)",
	"versions": {
		"attack": "11",
		"navigator": "4.6.6",
		"layer": "4.3"
	},
	"domain": "mobile-attack",
	"description": "Mobile techniques used by Deploy Compromised Device Detection Method, ATT&CK mitigation M1010 v1.0",
	"filters": {
		"platforms": [
			"Android",
			"iOS"
		]
	},
	"sorting": 0,
	"layout": {
		"layout": "side",
		"aggregateFunction": "average",
		"showID": false,
		"showName": true,
		"showAggregateScores": false,
		"countUnscored": false
	},
	"hideDisabled": false,
	"techniques": [
		{
			"techniqueID": "T1623",
			"tactic": "execution",
			"score": 1,
			"color": "",
			"comment": "Mobile security products can typically detect jailbroken or rooted devices. ",
			"enabled": true,
			"metadata": [],
			"links": [],
			"showSubtechniques": true
		},
		{
			"techniqueID": "T1623.001",
			"tactic": "execution",
			"score": 1,
			"color": "",
			"comment": "Mobile security products can typically detect jailbroken or rooted devices. ",
			"enabled": true,
			"metadata": [],
			"links": [],
			"showSubtechniques": true
		},
		{
			"techniqueID": "T1634",
			"tactic": "credential-access",
			"score": 1,
			"color": "",
			"comment": "Mobile security products can take appropriate action when jailbroken devices are detected, potentially limiting the adversary’s access to password stores. ",
			"enabled": true,
			"metadata": [],
			"links": [],
			"showSubtechniques": true
		},
		{
			"techniqueID": "T1634.001",
			"tactic": "credential-access",
			"score": 1,
			"color": "",
			"comment": "Mobile security products can take appropriate action when jailbroken devices are detected, potentially limiting the adversary’s access to password stores.",
			"enabled": true,
			"metadata": [],
			"links": [],
			"showSubtechniques": true
		},
		{
			"techniqueID": "T1404",
			"tactic": "privilege-escalation",
			"score": 1,
			"color": "",
			"comment": "Mobile security products can potentially detect jailbroken or rooted devices.",
			"enabled": true,
			"metadata": [],
			"links": [],
			"showSubtechniques": false
		},
		{
			"techniqueID": "T1628",
			"tactic": "defense-evasion",
			"color": "",
			"comment": "",
			"enabled": true,
			"metadata": [],
			"links": [],
			"showSubtechniques": true
		},
		{
			"techniqueID": "T1628.002",
			"tactic": "defense-evasion",
			"score": 1,
			"color": "",
			"comment": "Mobile security products that are part of the Samsung Knox for Mobile Threat Defense program could examine running applications while the device is idle, potentially detecting malicious applications that are running primarily when the device is not being used.",
			"enabled": true,
			"metadata": [],
			"links": [],
			"showSubtechniques": true
		},
		{
			"techniqueID": "T1617",
			"tactic": "defense-evasion",
			"score": 1,
			"color": "",
			"comment": "Mobile security products can often detect rooted devices.",
			"enabled": true,
			"metadata": [],
			"links": [],
			"showSubtechniques": false
		},
		{
			"techniqueID": "T1629",
			"tactic": "defense-evasion",
			"score": 1,
			"color": "",
			"comment": "Mobile security software can typically detect if a device has been rooted or jailbroken and can inform the user, who can then take appropriate action.",
			"enabled": true,
			"metadata": [],
			"links": [],
			"showSubtechniques": true
		},
		{
			"techniqueID": "T1629.003",
			"tactic": "defense-evasion",
			"score": 1,
			"color": "",
			"comment": "Mobile security software can typically detect if a device has been rooted or jailbroken and can inform the user, who can then take appropriate action.",
			"enabled": true,
			"metadata": [],
			"links": [],
			"showSubtechniques": true
		}
	],
	"gradient": {
		"colors": [
			"#ffffffff",
			"#66b1ffff"
		],
		"minValue": 0,
		"maxValue": 1
	},
	"legendItems": [
		{
			"color": "#66b1ff",
			"label": "used by Deploy Compromised Device Detection Method"
		}
	],
	"metadata": [],
	"links": [],
	"showTacticRowBackground": false,
	"tacticRowBackground": "#dddddd",
	"selectTechniquesAcrossTactics": true,
	"selectSubtechniquesWithParent": false
}
