/*jslint */
/*global AdobeEdge: false, window: false, document: false, console:false, alert: false */
(function (compId) {

    "use strict";
    var im='images/',
        aud='media/',
        vid='media/',
        js='js/',
        fonts = {
        },
        opts = {
            'gAudioPreloadPreference': 'auto',
            'gVideoPreloadPreference': 'auto'
        },
        resources = [
        ],
        scripts = [
        ],
        symbols = {
            "stage": {
                version: "5.0.0",
                minimumCompatibleVersion: "5.0.0",
                build: "5.0.0.375",
                scaleToFit: "height",
                centerStage: "horizontal",
                resizeInstances: false,
                content: {
                    dom: [
                        {
                            id: 'tombolonoff2',
                            type: 'image',
                            rect: ['187px', '50px', '61px', '59px', 'auto', 'auto'],
                            cursor: 'pointer',
                            fill: ["rgba(0,0,0,0)",im+"tombolonoff.png",'0px','0px']
                        },
                        {
                            id: 'tombolonoff2Copy',
                            type: 'image',
                            rect: ['837px', '51px', '61px', '59px', 'auto', 'auto'],
                            cursor: 'pointer',
                            fill: ["rgba(0,0,0,0)",im+"tombolonoff.png",'0px','0px']
                        },
                        {
                            id: 'tombolf2',
                            type: 'image',
                            rect: ['262px', '66px', '28px', '27px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"tombolf.png",'0px','0px']
                        },
                        {
                            id: 'tombolf2Copy',
                            type: 'image',
                            rect: ['392px', '66px', '28px', '27px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"tombolf.png",'0px','0px']
                        },
                        {
                            id: 'tombolf2Copy3',
                            type: 'image',
                            rect: ['789px', '66px', '28px', '27px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"tombolf.png",'0px','0px']
                        },
                        {
                            id: 'tombolf2Copy2',
                            type: 'image',
                            rect: ['657px', '66px', '28px', '27px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"tombolf.png",'0px','0px']
                        },
                        {
                            id: 'garis2',
                            type: 'image',
                            rect: ['411px', '78px', '260px', '2px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garis.png",'0px','0px']
                        },
                        {
                            id: 'garis2Copy',
                            type: 'image',
                            rect: ['557px', '312px', '248px', '2px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garis.png",'0px','0px']
                        },
                        {
                            id: 'garis2Copy2',
                            type: 'image',
                            rect: ['221px', '522px', '334px', '2px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garis.png",'0px','0px']
                        },
                        {
                            id: 'garislurus2',
                            type: 'image',
                            rect: ['557px', '79px', '2px', '59px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garislurus2.png",'0px','0px']
                        },
                        {
                            id: 'garislurus2Copy3',
                            type: 'image',
                            rect: ['557px', '252px', '2px', '117px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garislurus2.png",'0px','0px']
                        },
                        {
                            id: 'garislurus2Copy7',
                            type: 'image',
                            rect: ['520px', '109px', '2px', '303px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garislurus2.png",'0px','0px']
                        },
                        {
                            id: 'garislurus2Copy4',
                            type: 'image',
                            rect: ['803px', '254px', '2px', '59px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garislurus2.png",'0px','0px']
                        },
                        {
                            id: 'garislurus2Copy5',
                            type: 'image',
                            rect: ['555px', '465px', '2px', '59px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garislurus2.png",'0px','0px']
                        },
                        {
                            id: 'garislurus2Copy6',
                            type: 'image',
                            rect: ['521px', '445px', '2px', '50px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garislurus2.png",'0px','0px']
                        },
                        {
                            id: 'garislurus2Copy2',
                            type: 'image',
                            rect: ['802px', '79px', '2px', '59px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garislurus2.png",'0px','0px']
                        },
                        {
                            id: 'batangbiru2',
                            type: 'image',
                            rect: ['545px', '138px', '24px', '116px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"batangbiru.png",'0px','0px']
                        },
                        {
                            id: 'batangbiru2Copy2',
                            type: 'image',
                            rect: ['545px', '349px', '24px', '116px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"batangbiru.png",'0px','0px']
                        },
                        {
                            id: 'batangbiru2Copy',
                            type: 'image',
                            rect: ['792px', '138px', '24px', '116px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"batangbiru.png",'0px','0px']
                        },
                        {
                            id: 'kotakkecil2',
                            type: 'image',
                            rect: ['262px', '343px', '243px', '122px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"kotakkecil.png",'0px','0px']
                        },
                        {
                            id: 'lingkaran2',
                            type: 'image',
                            rect: ['467px', '430px', '24px', '27px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"lingkaran.png",'0px','0px']
                        },
                        {
                            id: 'lingkaran2Copy',
                            type: 'image',
                            rect: ['467px', '397px', '24px', '27px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"lingkaran.png",'0px','0px']
                        },
                        {
                            id: 'garis2Copy4',
                            type: 'image',
                            rect: ['491px', '444px', '30px', '2px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garis.png",'0px','0px']
                        },
                        {
                            id: 'garis2Copy5',
                            type: 'image',
                            rect: ['491px', '409px', '30px', '2px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garis.png",'0px','0px']
                        },
                        {
                            id: 'garislurus3',
                            type: 'image',
                            rect: ['275px', '86px', '2px', '165px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garislurus3.png",'0px','0px']
                        },
                        {
                            id: 'kotakbesar2',
                            type: 'image',
                            rect: ['3px', '147px', '245px', '165px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"kotakbesar.png",'0px','0px']
                        },
                        {
                            id: 'Text10',
                            type: 'text',
                            rect: ['203px', '283px', 'auto', 'auto', 'auto', 'auto'],
                            text: "-",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [25, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'Text6',
                            type: 'text',
                            rect: ['201px', '221px', 'auto', 'auto', 'auto', 'auto'],
                            text: "+",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [25, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'Text6Copy',
                            type: 'text',
                            rect: ['459px', '381px', 'auto', 'auto', 'auto', 'auto'],
                            text: "+",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [25, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'Text11',
                            type: 'text',
                            rect: ['459px', '439px', 'auto', 'auto', 'auto', 'auto'],
                            text: "-",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [25, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'lingkaran2Copy3',
                            type: 'image',
                            rect: ['210px', '272px', '24px', '27px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"lingkaran.png",'0px','0px']
                        },
                        {
                            id: 'lingkaran2Copy2',
                            type: 'image',
                            rect: ['210px', '239px', '24px', '27px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"lingkaran.png",'0px','0px']
                        },
                        {
                            id: 'garislurus3Copy2',
                            type: 'image',
                            rect: ['221px', '299px', '2px', '225px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garislurus3.png",'0px','0px']
                        },
                        {
                            id: 'garis2Copy6',
                            type: 'image',
                            rect: ['232px', '250px', '43px', '2px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garis.png",'0px','0px']
                        },
                        {
                            id: 'Text',
                            type: 'text',
                            rect: ['166px', '15px', 'auto', 'auto', 'auto', 'auto'],
                            text: "On / Off",
                            font: ['Arial, Helvetica, sans-serif', [30, "px"], "rgba(0,0,0,1)", "700", "none", "", "break-word", "nowrap"]
                        },
                        {
                            id: 'Text3',
                            type: 'text',
                            rect: ['821px', '178px', 'auto', 'auto', 'auto', 'auto'],
                            text: "500 Ohm",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [30, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'Text4',
                            type: 'text',
                            rect: ['576px', '394px', 'auto', 'auto', 'auto', 'auto'],
                            text: "1000 Ohm",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [30, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'Text5',
                            type: 'text',
                            rect: ['55px', '196px', 'auto', 'auto', 'auto', 'auto'],
                            text: "1",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [60, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'Text7',
                            type: 'text',
                            rect: ['43px', '151px', 'auto', 'auto', 'auto', 'auto'],
                            text: "Arus Listrik",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [30, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'Text8',
                            type: 'text',
                            rect: ['315px', '349px', 'auto', 'auto', 'auto', 'auto'],
                            text: "Voltmeter",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [30, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'Text9',
                            type: 'text',
                            rect: ['803px', '15px', 'auto', 'auto', 'auto', 'auto'],
                            text: "Switch A",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [30, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'kotakkecil3',
                            type: 'image',
                            rect: ['315px', '385px', '138px', '68px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"kotakkecil.png",'0px','0px']
                        },
                        {
                            id: 'Result_B',
                            display: 'none',
                            type: 'text',
                            rect: ['335px', '397px', '108px', '46px', 'auto', 'auto'],
                            text: "1375",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [45, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "normal"]
                        },
                        {
                            id: 'Result_A',
                            display: 'none',
                            type: 'text',
                            rect: ['338px', '394px', '108px', '52px', 'auto', 'auto'],
                            text: "2500",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [45, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "normal"]
                        },
                        {
                            id: 'BH_L',
                            symbolName: 'BH_L',
                            type: 'rect',
                            rect: ['272px', '35', '130', '52', 'auto', 'auto']
                        },
                        {
                            id: 'BH_R',
                            symbolName: 'BH_L',
                            type: 'rect',
                            rect: ['664px', '35', '130', '52', 'auto', 'auto']
                        },
                        {
                            id: 'NOL',
                            display: 'none',
                            type: 'text',
                            rect: ['373px', '394px', '30px', '52px', 'auto', 'auto'],
                            text: "0",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [45, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "normal"]
                        },
                        {
                            id: 'Text13',
                            type: 'text',
                            rect: ['96px', '218px', 'auto', 'auto', 'auto', 'auto'],
                            text: "Ampere",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [25, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'Text2',
                            type: 'text',
                            rect: ['576px', '178px', 'auto', 'auto', 'auto', 'auto'],
                            text: "1500 Ohm",
                            align: "left",
                            font: ['Arial, Helvetica, sans-serif', [30, "px"], "rgba(0,0,0,1)", "700", "none solid rgb(0, 0, 0)", "normal", "break-word", "nowrap"]
                        },
                        {
                            id: 'garis2Copy3',
                            type: 'image',
                            rect: ['521px', '494px', '35px', '2px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garis.png",'0px','0px']
                        },
                        {
                            id: 'garis2Copy7',
                            type: 'image',
                            rect: ['521px', '110px', '37px', '2px', 'auto', 'auto'],
                            fill: ["rgba(0,0,0,0)",im+"garis.png",'0px','0px']
                        }
                    ],
                    style: {
                        '${Stage}': {
                            isStage: true,
                            rect: ['null', 'null', '1000px', '550px', 'auto', 'auto'],
                            overflow: 'hidden',
                            fill: ["rgba(255,255,255,1.00)"]
                        }
                    }
                },
                timeline: {
                    duration: 0,
                    autoPlay: true,
                    data: [
                        [
                            "eid119",
                            "left",
                            0,
                            0,
                            "linear",
                            "${Result_B}",
                            '335px',
                            '335px'
                        ],
                        [
                            "eid112",
                            "left",
                            0,
                            0,
                            "linear",
                            "${BH_L}",
                            '272px',
                            '272px'
                        ],
                        [
                            "eid96",
                            "width",
                            0,
                            0,
                            "linear",
                            "${Result_A}",
                            '108px',
                            '108px'
                        ],
                        [
                            "eid114",
                            "left",
                            0,
                            0,
                            "linear",
                            "${NOL}",
                            '373px',
                            '373px'
                        ],
                        [
                            "eid106",
                            "width",
                            0,
                            0,
                            "linear",
                            "${Result_B}",
                            '108px',
                            '108px'
                        ],
                        [
                            "eid104",
                            "font-size",
                            0,
                            0,
                            "linear",
                            "${Result_B}",
                            '45px',
                            '45px'
                        ],
                        [
                            "eid109",
                            "font-size",
                            0,
                            0,
                            "linear",
                            "${NOL}",
                            '45px',
                            '45px'
                        ],
                        [
                            "eid118",
                            "left",
                            0,
                            0,
                            "linear",
                            "${Result_A}",
                            '338px',
                            '338px'
                        ],
                        [
                            "eid85",
                            "display",
                            0,
                            0,
                            "linear",
                            "${Result_A}",
                            'none',
                            'none'
                        ],
                        [
                            "eid92",
                            "display",
                            0,
                            0,
                            "linear",
                            "${Result_B}",
                            'none',
                            'none'
                        ],
                        [
                            "eid116",
                            "left",
                            0,
                            0,
                            "linear",
                            "${BH_R}",
                            '664px',
                            '664px'
                        ],
                        [
                            "eid108",
                            "top",
                            0,
                            0,
                            "linear",
                            "${Result_B}",
                            '397px',
                            '397px'
                        ],
                        [
                            "eid103",
                            "font-size",
                            0,
                            0,
                            "linear",
                            "${Result_A}",
                            '45px',
                            '45px'
                        ],
                        [
                            "eid93",
                            "display",
                            0,
                            0,
                            "linear",
                            "${NOL}",
                            'none',
                            'none'
                        ]
                    ]
                }
            },
            "batang1": {
                version: "5.0.0",
                minimumCompatibleVersion: "5.0.0",
                build: "5.0.0.375",
                scaleToFit: "none",
                centerStage: "none",
                resizeInstances: false,
                content: {
                    dom: [
                        {
                            transform: [[], ['-15'], [0, 0, 0], [1, 1, 1]],
                            id: 'batanghitam2',
                            type: 'image',
                            rect: ['0px', '16px', '124px', '14px', 'auto', 'auto'],
                            fill: ['rgba(0,0,0,0)', 'images/batanghitam.png', '0px', '0px']
                        }
                    ],
                    style: {
                        '${symbolSelector}': {
                            rect: [null, null, '123px', '46px']
                        }
                    }
                },
                timeline: {
                    duration: 180,
                    autoPlay: true,
                    data: [
                        [
                            "eid44",
                            "left",
                            0,
                            180,
                            "linear",
                            "${batanghitam2}",
                            '0px',
                            '-6px'
                        ],
                        [
                            "eid47",
                            "width",
                            0,
                            0,
                            "linear",
                            "${batanghitam2}",
                            '124px',
                            '124px'
                        ],
                        [
                            "eid38",
                            "rotateZ",
                            0,
                            180,
                            "linear",
                            "${batanghitam2}",
                            '-15deg',
                            '0deg'
                        ],
                        [
                            "eid45",
                            "top",
                            0,
                            180,
                            "linear",
                            "${batanghitam2}",
                            '16px',
                            '33px'
                        ]
                    ]
                }
            },
            "L_B": {
                version: "5.0.0",
                minimumCompatibleVersion: "5.0.0",
                build: "5.0.0.375",
                scaleToFit: "none",
                centerStage: "none",
                resizeInstances: false,
                content: {
                    dom: [
                        {
                            transform: [[], ['-15'], [0, 0, 0], [1, 1, 1]],
                            id: 'batanghitam2',
                            type: 'image',
                            rect: ['4px', '28px', '124px', '14px', 'auto', 'auto'],
                            fill: ['rgba(0,0,0,0)', 'images/batanghitam.png', '0px', '0px']
                        }
                    ],
                    style: {
                        '${symbolSelector}': {
                            rect: [null, null, '123px', '46px']
                        }
                    }
                },
                timeline: {
                    duration: 180,
                    autoPlay: false,
                    data: [
                        [
                            "eid57",
                            "left",
                            0,
                            180,
                            "linear",
                            "${batanghitam2}",
                            '0px',
                            '4px'
                        ],
                        [
                            "eid58",
                            "width",
                            0,
                            0,
                            "linear",
                            "${batanghitam2}",
                            '124px',
                            '124px'
                        ],
                        [
                            "eid55",
                            "top",
                            0,
                            180,
                            "linear",
                            "${batanghitam2}",
                            '16px',
                            '28px'
                        ],
                        [
                            "eid56",
                            "rotateZ",
                            0,
                            180,
                            "linear",
                            "${batanghitam2}",
                            '-15deg',
                            '0deg'
                        ]
                    ]
                }
            },
            "R_L": {
                version: "5.0.0",
                minimumCompatibleVersion: "5.0.0",
                build: "5.0.0.375",
                scaleToFit: "none",
                centerStage: "none",
                resizeInstances: false,
                content: {
                    dom: [
                        {
                            transform: [[], ['-15'], [0, 0, 0], [1, 1, 1]],
                            id: 'batanghitam2Copy',
                            type: 'image',
                            rect: ['3px', '32px', '124px', '14px', 'auto', 'auto'],
                            fill: ['rgba(0,0,0,0)', 'images/batanghitam.png', '0px', '0px']
                        }
                    ],
                    style: {
                        '${symbolSelector}': {
                            rect: [null, null, '123px', '46px']
                        }
                    }
                },
                timeline: {
                    duration: 180,
                    autoPlay: false,
                    data: [
                        [
                            "eid59",
                            "top",
                            0,
                            180,
                            "linear",
                            "${batanghitam2Copy}",
                            '16px',
                            '32px'
                        ],
                        [
                            "eid61",
                            "left",
                            0,
                            180,
                            "linear",
                            "${batanghitam2Copy}",
                            '-1px',
                            '3px'
                        ],
                        [
                            "eid60",
                            "rotateZ",
                            0,
                            180,
                            "linear",
                            "${batanghitam2Copy}",
                            '-15deg',
                            '0deg'
                        ],
                        [
                            "eid62",
                            "width",
                            0,
                            0,
                            "linear",
                            "${batanghitam2Copy}",
                            '124px',
                            '124px'
                        ]
                    ]
                }
            },
            "BH_L": {
                version: "5.0.0",
                minimumCompatibleVersion: "5.0.0",
                build: "5.0.0.375",
                scaleToFit: "none",
                centerStage: "none",
                resizeInstances: false,
                content: {
                    dom: [
                        {
                            transform: [[], ['-17'], [0, 0, 0], [1, 1, 1]],
                            id: 'batanghitam',
                            type: 'image',
                            rect: ['-1px', '19px', '132px', '14px', 'auto', 'auto'],
                            fill: ['rgba(0,0,0,0)', 'images/batanghitam.png', '0px', '0px']
                        }
                    ],
                    style: {
                        '${symbolSelector}': {
                            rect: [null, null, '130px', '52px']
                        }
                    }
                },
                timeline: {
                    duration: 250,
                    autoPlay: false,
                    data: [
                        [
                            "eid76",
                            "left",
                            0,
                            250,
                            "linear",
                            "${batanghitam}",
                            '-1px',
                            '5px'
                        ],
                        [
                            "eid77",
                            "top",
                            0,
                            250,
                            "linear",
                            "${batanghitam}",
                            '19px',
                            '36px'
                        ],
                        [
                            "eid75",
                            "rotateZ",
                            0,
                            250,
                            "linear",
                            "${batanghitam}",
                            '-17deg',
                            '0deg'
                        ]
                    ]
                }
            },
            "BH_R": {
                version: "5.0.0",
                minimumCompatibleVersion: "5.0.0",
                build: "5.0.0.375",
                scaleToFit: "none",
                centerStage: "none",
                resizeInstances: false,
                content: {
                    dom: [
                        {
                            id: 'batanghitamCopy',
                            type: 'image',
                            rect: ['-1px', '19px', '132px', '14px', 'auto', 'auto'],
                            fill: ['rgba(0,0,0,0)', 'images/batanghitam.png', '0px', '0px']
                        }
                    ],
                    style: {
                        '${symbolSelector}': {
                            rect: [null, null, '130px', '52px']
                        }
                    }
                },
                timeline: {
                    duration: 320,
                    autoPlay: false,
                    data: [
                        [
                            "eid79",
                            "left",
                            0,
                            320,
                            "linear",
                            "${batanghitamCopy}",
                            '-1px',
                            '3px'
                        ],
                        [
                            "eid78",
                            "rotateZ",
                            0,
                            320,
                            "linear",
                            "${batanghitamCopy}",
                            '-17deg',
                            '0deg'
                        ],
                        [
                            "eid80",
                            "top",
                            0,
                            320,
                            "linear",
                            "${batanghitamCopy}",
                            '19px',
                            '39px'
                        ]
                    ]
                }
            }
        };

    AdobeEdge.registerCompositionDefn(compId, symbols, fonts, scripts, resources, opts);

    if (!window.edge_authoring_mode) AdobeEdge.getComposition(compId).load("animasi_edgeActions.js");
})("EDGE-13364392");
