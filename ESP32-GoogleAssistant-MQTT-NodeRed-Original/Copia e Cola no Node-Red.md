[
    {
        "id": "8e600a1d9cc6877a",
        "type": "tab",
        "label": "ESP32 e Google Assistant",
        "disabled": false,
        "info": "",
        "env": []
    },
    {
        "id": "0bc70d3a568e5fe7",
        "type": "tab",
        "label": "Interruptores",
        "disabled": false,
        "info": "",
        "env": []
    },
    {
        "id": "d1609a41d0822de3",
        "type": "tab",
        "label": "Sensores",
        "disabled": false,
        "info": "",
        "env": []
    },
    {
        "id": "03fa7ff17c898856",
        "type": "mqtt-broker",
        "name": "MQTT Broker",
        "broker": "192.168.15.25",
        "port": "1883",
        "clientid": "",
        "autoConnect": true,
        "usetls": false,
        "protocolVersion": "4",
        "keepalive": "60",
        "cleansession": true,
        "birthTopic": "",
        "birthQos": "1",
        "birthPayload": "",
        "birthMsg": {},
        "closeTopic": "",
        "closeQos": "0",
        "closePayload": "",
        "closeMsg": {},
        "willTopic": "",
        "willQos": "0",
        "willPayload": "",
        "willMsg": {},
        "sessionExpiry": ""
    },
    {
        "id": "bf2335351d119ded",
        "type": "noraf-config",
        "name": "Nora",
        "group": "Casa",
        "twofactor": "off",
        "twofactorpin": "",
        "localexecution": true,
        "structure": "Robson's House",
        "storeStateInContext": true
    },
    {
        "id": "efd70f10282c1c79",
        "type": "ui_base",
        "theme": {
            "name": "theme-custom",
            "lightTheme": {
                "default": "#0094CE",
                "baseColor": "#0094CE",
                "baseFont": "Arial Black,Arial Black,Gadget,sans-serif",
                "edited": true,
                "reset": false
            },
            "darkTheme": {
                "default": "#097479",
                "baseColor": "#097479",
                "baseFont": "Arial Black,Arial Black,Gadget,sans-serif",
                "edited": true,
                "reset": false
            },
            "customTheme": {
                "name": "Untitled Theme 1",
                "default": "#4B7930",
                "baseColor": "#000000",
                "baseFont": "Arial,Arial,Helvetica,sans-serif",
                "reset": false
            },
            "themeState": {
                "base-color": {
                    "default": "#4B7930",
                    "value": "#000000",
                    "edited": true
                },
                "page-titlebar-backgroundColor": {
                    "value": "#000000",
                    "edited": false
                },
                "page-backgroundColor": {
                    "value": "#111111",
                    "edited": false
                },
                "page-sidebar-backgroundColor": {
                    "value": "#000000",
                    "edited": true
                },
                "group-textColor": {
                    "value": "#ffae00",
                    "edited": true
                },
                "group-borderColor": {
                    "value": "#f50000",
                    "edited": true
                },
                "group-backgroundColor": {
                    "value": "#050000",
                    "edited": true
                },
                "widget-textColor": {
                    "value": "#eeeeee",
                    "edited": false
                },
                "widget-backgroundColor": {
                    "value": "#e1dbdb",
                    "edited": true
                },
                "widget-borderColor": {
                    "value": "#000000",
                    "edited": true
                },
                "base-font": {
                    "value": "Arial,Arial,Helvetica,sans-serif"
                }
            },
            "angularTheme": {
                "primary": "indigo",
                "accents": "blue",
                "warn": "red",
                "background": "grey",
                "palette": "light"
            }
        },
        "site": {
            "name": "Node-RED Dashboard",
            "hideToolbar": "false",
            "allowSwipe": "false",
            "lockMenu": "false",
            "allowTempTheme": "true",
            "dateFormat": "DD/MM/YYYY",
            "sizes": {
                "sx": 48,
                "sy": 48,
                "gx": 6,
                "gy": 6,
                "cx": 6,
                "cy": 6,
                "px": 0,
                "py": 0
            }
        }
    },
    {
        "id": "40d13ed77576d565",
        "type": "ui_group",
        "name": "Group 1",
        "tab": "",
        "order": 1,
        "disp": true,
        "width": "6",
        "collapse": false,
        "className": ""
    },
    {
        "id": "ecd95f264f5fcd2a",
        "type": "ui_spacer",
        "z": "8e600a1d9cc6877a",
        "name": "spacer",
        "group": "40d13ed77576d565",
        "order": 1,
        "width": "1",
        "height": "1"
    },
    {
        "id": "7ccfe2f3.3fd12c",
        "type": "ui_group",
        "name": "Group 1",
        "tab": "",
        "order": 1,
        "disp": false,
        "width": "6",
        "collapse": false
    },
    {
        "id": "fea7d4d6.f60f68",
        "type": "ui_group",
        "name": "Group 2",
        "tab": "",
        "order": 2,
        "disp": false,
        "width": "6",
        "collapse": false
    },
    {
        "id": "e8b7cd70.90dcb",
        "type": "ui_group",
        "name": "Group 3",
        "tab": "",
        "order": 3,
        "disp": false,
        "width": "6",
        "collapse": false
    },
    {
        "id": "1f03af3b.e5c8d1",
        "type": "ui_group",
        "name": "Group 4",
        "tab": "",
        "order": 4,
        "disp": false,
        "width": "4",
        "collapse": false
    },
    {
        "id": "36778cb60bc3c823",
        "type": "ui_group",
        "name": "Group 5",
        "tab": "",
        "order": 5,
        "disp": true,
        "width": 6
    },
    {
        "id": "c91af49f97fe4fbe",
        "type": "tasmota-mqtt-broker",
        "name": "Meu Broker",
        "broker": "192.168.15.25",
        "port": "1883",
        "clientid": "",
        "usetls": false,
        "keepalive": "60",
        "cleansession": true
    },
    {
        "id": "b2907dad.3b4d88",
        "type": "mqtt-broker",
        "name": "Meu Notebook",
        "broker": "192.168.15.25",
        "port": "1883",
        "clientid": "",
        "autoConnect": true,
        "usetls": false,
        "compatmode": false,
        "protocolVersion": "4",
        "keepalive": "60",
        "cleansession": true,
        "birthTopic": "",
        "birthQos": "0",
        "birthRetain": "false",
        "birthPayload": "",
        "birthMsg": {},
        "closeTopic": "",
        "closeQos": "0",
        "closeRetain": "false",
        "closePayload": "",
        "closeMsg": {},
        "willTopic": "",
        "willQos": "0",
        "willRetain": "false",
        "willPayload": "",
        "willMsg": {},
        "sessionExpiry": ""
    },
    {
        "id": "f57a184e.4f4fa",
        "type": "ui_tab",
        "name": "ESP32 - IoT internet das Coisas",
        "icon": "dashboard",
        "disabled": false,
        "hidden": false
    },
    {
        "id": "d7c12b74.277828",
        "type": "ui_group",
        "name": "Interruptores",
        "tab": "f57a184e.4f4fa",
        "order": 1,
        "disp": true,
        "width": "6",
        "collapse": false,
        "className": ""
    },
    {
        "id": "4120bc84.e1bb74",
        "type": "ui_group",
        "name": "Controls",
        "tab": "",
        "order": 1,
        "disp": true,
        "width": "6",
        "collapse": false
    },
    {
        "id": "7ccde2ba.796d34",
        "type": "ui_group",
        "name": "Monitor",
        "tab": "",
        "order": 2,
        "disp": true,
        "width": "6",
        "collapse": false
    },
    {
        "id": "ae4b8351.dfe6f8",
        "type": "mqtt-broker",
        "name": "",
        "broker": "192.168.15.25",
        "port": "1883",
        "clientid": "",
        "autoConnect": true,
        "usetls": false,
        "compatmode": false,
        "protocolVersion": "4",
        "keepalive": "60",
        "cleansession": true,
        "birthTopic": "",
        "birthQos": "0",
        "birthRetain": "false",
        "birthPayload": "",
        "birthMsg": {},
        "closeTopic": "",
        "closeQos": "0",
        "closeRetain": "false",
        "closePayload": "",
        "closeMsg": {},
        "willTopic": "",
        "willQos": "0",
        "willRetain": "false",
        "willPayload": "",
        "willMsg": {},
        "sessionExpiry": ""
    },
    {
        "id": "45975112.c3f2d8",
        "type": "mqtt-broker",
        "name": "Mosquitto",
        "broker": "192.168.15.95",
        "port": "1883",
        "clientid": "",
        "usetls": false,
        "compatmode": false,
        "keepalive": "60",
        "cleansession": true,
        "birthTopic": "",
        "birthQos": "0",
        "birthRetain": "false",
        "birthPayload": "",
        "closeTopic": "",
        "closeQos": "0",
        "closeRetain": "false",
        "closePayload": "",
        "willTopic": "",
        "willQos": "0",
        "willRetain": "false",
        "willPayload": ""
    },
    {
        "id": "f12b6b658291d542",
        "type": "ui_group",
        "name": "Previsão do Tempo",
        "tab": "f57a184e.4f4fa",
        "order": 2,
        "disp": true,
        "width": "6",
        "collapse": false,
        "className": ""
    },
    {
        "id": "2b3a5e6c865b5a25",
        "type": "noraf-light",
        "z": "8e600a1d9cc6877a",
        "devicename": "Minha lâmpada",
        "lightcolor": false,
        "brightnesscontrol": false,
        "commandonlycolor": false,
        "turnonwhenbrightnesschanges": false,
        "passthru": false,
        "errorifstateunchaged": false,
        "statepayload": true,
        "brightnessoverride": "",
        "roomhint": "Lâmpada do Meu Quarto",
        "name": "Lâmpada Robson",
        "colortype": "hsv",
        "nora": "bf2335351d119ded",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarLampada",
        "onvalue": "0",
        "onvalueType": "num",
        "offvalue": "1",
        "offvalueType": "num",
        "temperaturemin": "2700",
        "temperaturemax": "5500",
        "twofactor": "off",
        "twofactorpin": "",
        "filter": false,
        "x": 230,
        "y": 240,
        "wires": [
            [
                "13e2b7aeb791786d",
                "fe0e8995374b95d4"
            ]
        ]
    },
    {
        "id": "13e2b7aeb791786d",
        "type": "debug",
        "z": "8e600a1d9cc6877a",
        "name": "",
        "active": true,
        "tosidebar": true,
        "console": true,
        "tostatus": false,
        "complete": "payload",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 580,
        "y": 400,
        "wires": []
    },
    {
        "id": "fe0e8995374b95d4",
        "type": "mqtt out",
        "z": "8e600a1d9cc6877a",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarLampada",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 880,
        "y": 160,
        "wires": []
    },
    {
        "id": "645fe0a9ccf3ec8b",
        "type": "noraf-light",
        "z": "8e600a1d9cc6877a",
        "devicename": "Lâmpada da Bancada",
        "lightcolor": false,
        "brightnesscontrol": false,
        "commandonlycolor": false,
        "turnonwhenbrightnesschanges": false,
        "passthru": false,
        "errorifstateunchaged": false,
        "statepayload": true,
        "brightnessoverride": "",
        "roomhint": "Lâmpada da Bancada",
        "name": "Lâmpada da Bancada",
        "colortype": "hsv",
        "nora": "bf2335351d119ded",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarBancada",
        "onvalue": "0",
        "onvalueType": "num",
        "offvalue": "1",
        "offvalueType": "num",
        "temperaturemin": "2700",
        "temperaturemax": "5500",
        "twofactor": "off",
        "twofactorpin": "",
        "filter": false,
        "x": 220,
        "y": 320,
        "wires": [
            [
                "13e2b7aeb791786d",
                "677f73033bfdea01"
            ]
        ]
    },
    {
        "id": "7950712dd4c9cd16",
        "type": "noraf-light",
        "z": "8e600a1d9cc6877a",
        "devicename": "Caixa de Som",
        "lightcolor": false,
        "brightnesscontrol": false,
        "commandonlycolor": false,
        "turnonwhenbrightnesschanges": false,
        "passthru": false,
        "errorifstateunchaged": false,
        "statepayload": true,
        "brightnessoverride": "",
        "roomhint": "Caixa de Som do Notebook",
        "name": "Caixa de Som",
        "colortype": "hsv",
        "nora": "bf2335351d119ded",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarSom",
        "onvalue": "0",
        "onvalueType": "num",
        "offvalue": "1",
        "offvalueType": "num",
        "temperaturemin": "2700",
        "temperaturemax": "5500",
        "twofactor": "off",
        "twofactorpin": "",
        "filter": false,
        "x": 240,
        "y": 480,
        "wires": [
            [
                "13e2b7aeb791786d",
                "94d5e78081efbff1"
            ]
        ]
    },
    {
        "id": "d5d6febd84ac0471",
        "type": "noraf-light",
        "z": "8e600a1d9cc6877a",
        "devicename": "Cooler",
        "lightcolor": false,
        "brightnesscontrol": false,
        "commandonlycolor": false,
        "turnonwhenbrightnesschanges": false,
        "passthru": true,
        "errorifstateunchaged": false,
        "statepayload": false,
        "brightnessoverride": "",
        "roomhint": "Cooler do Meu Quarto",
        "name": "Cooler",
        "colortype": "hsv",
        "nora": "bf2335351d119ded",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarCooler",
        "onvalue": "0",
        "onvalueType": "num",
        "offvalue": "1",
        "offvalueType": "num",
        "temperaturemin": "2700",
        "temperaturemax": "5500",
        "twofactor": "off",
        "twofactorpin": "",
        "filter": false,
        "x": 270,
        "y": 400,
        "wires": [
            [
                "13e2b7aeb791786d",
                "50c566708019f05b"
            ]
        ]
    },
    {
        "id": "94d5e78081efbff1",
        "type": "mqtt out",
        "z": "8e600a1d9cc6877a",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarSom",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 880,
        "y": 520,
        "wires": []
    },
    {
        "id": "50c566708019f05b",
        "type": "mqtt out",
        "z": "8e600a1d9cc6877a",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarCooler",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 880,
        "y": 400,
        "wires": []
    },
    {
        "id": "677f73033bfdea01",
        "type": "mqtt out",
        "z": "8e600a1d9cc6877a",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarBancada",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 880,
        "y": 280,
        "wires": []
    },
    {
        "id": "7370dfbd73b8395c",
        "type": "noraf-light",
        "z": "8e600a1d9cc6877a",
        "devicename": "Bluetooth",
        "lightcolor": false,
        "brightnesscontrol": false,
        "commandonlycolor": false,
        "turnonwhenbrightnesschanges": false,
        "passthru": false,
        "errorifstateunchaged": false,
        "statepayload": true,
        "brightnessoverride": "",
        "roomhint": "Bluetooth",
        "name": "Bluetooth Robson",
        "colortype": "hsv",
        "nora": "bf2335351d119ded",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarBluetooth",
        "onvalue": "0",
        "onvalueType": "num",
        "offvalue": "1",
        "offvalueType": "num",
        "temperaturemin": "2700",
        "temperaturemax": "5500",
        "twofactor": "off",
        "twofactorpin": "",
        "filter": false,
        "x": 230,
        "y": 560,
        "wires": [
            [
                "666fe101703abe94",
                "13e2b7aeb791786d"
            ]
        ]
    },
    {
        "id": "666fe101703abe94",
        "type": "mqtt out",
        "z": "8e600a1d9cc6877a",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarBluetooth",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 880,
        "y": 640,
        "wires": []
    },
    {
        "id": "4c5dbbfef82dc998",
        "type": "mqtt out",
        "z": "0bc70d3a568e5fe7",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarInterruptor6",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 900,
        "y": 540,
        "wires": []
    },
    {
        "id": "710c5d49d3c9afd0",
        "type": "mqtt out",
        "z": "0bc70d3a568e5fe7",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarInterruptor7",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 900,
        "y": 620,
        "wires": []
    },
    {
        "id": "42d6f543c6442109",
        "type": "mqtt out",
        "z": "0bc70d3a568e5fe7",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarInterruptor8",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 900,
        "y": 680,
        "wires": []
    },
    {
        "id": "67b9667fbd9711b9",
        "type": "ui_switch",
        "z": "0bc70d3a568e5fe7",
        "name": "interruptor 6",
        "label": "Interruptor 6",
        "tooltip": "",
        "group": "d7c12b74.277828",
        "order": 7,
        "width": 0,
        "height": 0,
        "passthru": true,
        "decouple": "false",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarInterruptor6",
        "topicType": "str",
        "style": "",
        "onvalue": "0",
        "onvalueType": "num",
        "onicon": "",
        "oncolor": "",
        "offvalue": "1",
        "offvalueType": "num",
        "officon": "",
        "offcolor": "",
        "animate": true,
        "className": "",
        "x": 290,
        "y": 500,
        "wires": [
            [
                "4c5dbbfef82dc998",
                "a22e8a321accceb7"
            ]
        ]
    },
    {
        "id": "0606e1bbc60b1cd9",
        "type": "ui_switch",
        "z": "0bc70d3a568e5fe7",
        "name": "Interruptor 7",
        "label": "Interruptor 7",
        "tooltip": "",
        "group": "d7c12b74.277828",
        "order": 8,
        "width": 0,
        "height": 0,
        "passthru": true,
        "decouple": "false",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarInterruptor7",
        "topicType": "str",
        "style": "",
        "onvalue": "0",
        "onvalueType": "num",
        "onicon": "",
        "oncolor": "",
        "offvalue": "1",
        "offvalueType": "num",
        "officon": "",
        "offcolor": "",
        "animate": true,
        "className": "",
        "x": 290,
        "y": 560,
        "wires": [
            [
                "710c5d49d3c9afd0",
                "a22e8a321accceb7"
            ]
        ]
    },
    {
        "id": "cd5cae440980d745",
        "type": "ui_switch",
        "z": "0bc70d3a568e5fe7",
        "name": "Interruptor 8",
        "label": "Interruptor 8",
        "tooltip": "",
        "group": "d7c12b74.277828",
        "order": 9,
        "width": 0,
        "height": 0,
        "passthru": true,
        "decouple": "false",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarInterruptor8",
        "topicType": "str",
        "style": "",
        "onvalue": "0",
        "onvalueType": "num",
        "onicon": "",
        "oncolor": "",
        "offvalue": "1",
        "offvalueType": "num",
        "officon": "",
        "offcolor": "",
        "animate": true,
        "className": "",
        "x": 290,
        "y": 620,
        "wires": [
            [
                "42d6f543c6442109",
                "a22e8a321accceb7"
            ]
        ]
    },
    {
        "id": "a22e8a321accceb7",
        "type": "debug",
        "z": "0bc70d3a568e5fe7",
        "name": "",
        "active": true,
        "tosidebar": true,
        "console": true,
        "tostatus": false,
        "complete": "payload",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 620,
        "y": 380,
        "wires": []
    },
    {
        "id": "1fa1e27f6aad2801",
        "type": "mqtt out",
        "z": "0bc70d3a568e5fe7",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarBancada",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 900,
        "y": 240,
        "wires": []
    },
    {
        "id": "3de8dbf13d467a66",
        "type": "mqtt out",
        "z": "0bc70d3a568e5fe7",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarCooler",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 900,
        "y": 320,
        "wires": []
    },
    {
        "id": "449c4140a7b4c0d2",
        "type": "mqtt out",
        "z": "0bc70d3a568e5fe7",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarSom",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 900,
        "y": 380,
        "wires": []
    },
    {
        "id": "8a1bf80f5178c19e",
        "type": "ui_switch",
        "z": "0bc70d3a568e5fe7",
        "name": "",
        "label": "Lâmpada da Bancada",
        "tooltip": "",
        "group": "d7c12b74.277828",
        "order": 3,
        "width": 0,
        "height": 0,
        "passthru": true,
        "decouple": "false",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarBancada",
        "topicType": "str",
        "style": "",
        "onvalue": "0",
        "onvalueType": "num",
        "onicon": "",
        "oncolor": "",
        "offvalue": "1",
        "offvalueType": "num",
        "officon": "",
        "offcolor": "",
        "animate": true,
        "className": "",
        "x": 260,
        "y": 260,
        "wires": [
            [
                "1fa1e27f6aad2801",
                "a22e8a321accceb7"
            ]
        ]
    },
    {
        "id": "e30b1ffd058a3491",
        "type": "ui_switch",
        "z": "0bc70d3a568e5fe7",
        "name": "",
        "label": "Cooler",
        "tooltip": "",
        "group": "d7c12b74.277828",
        "order": 4,
        "width": 0,
        "height": 0,
        "passthru": true,
        "decouple": "false",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarCooler",
        "topicType": "str",
        "style": "",
        "onvalue": "0",
        "onvalueType": "num",
        "onicon": "",
        "oncolor": "",
        "offvalue": "1",
        "offvalueType": "num",
        "officon": "",
        "offcolor": "",
        "animate": true,
        "className": "",
        "x": 310,
        "y": 320,
        "wires": [
            [
                "3de8dbf13d467a66",
                "a22e8a321accceb7"
            ]
        ]
    },
    {
        "id": "b4b7047327d8ca52",
        "type": "ui_switch",
        "z": "0bc70d3a568e5fe7",
        "name": "",
        "label": "Caixa de Som",
        "tooltip": "",
        "group": "d7c12b74.277828",
        "order": 5,
        "width": 0,
        "height": 0,
        "passthru": true,
        "decouple": "false",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarSom",
        "topicType": "str",
        "style": "",
        "onvalue": "0",
        "onvalueType": "num",
        "onicon": "",
        "oncolor": "",
        "offvalue": "1",
        "offvalueType": "num",
        "officon": "",
        "offcolor": "",
        "animate": true,
        "className": "",
        "x": 280,
        "y": 380,
        "wires": [
            [
                "449c4140a7b4c0d2",
                "a22e8a321accceb7"
            ]
        ]
    },
    {
        "id": "7363fd0fb87da2bf",
        "type": "mqtt out",
        "z": "0bc70d3a568e5fe7",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarLampada",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 900,
        "y": 160,
        "wires": []
    },
    {
        "id": "5d0b5de3c76a14c2",
        "type": "ui_switch",
        "z": "0bc70d3a568e5fe7",
        "name": "",
        "label": "Lâmpada do Meu Quarto",
        "tooltip": "",
        "group": "d7c12b74.277828",
        "order": 2,
        "width": 0,
        "height": 0,
        "passthru": true,
        "decouple": "false",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarLampada",
        "topicType": "str",
        "style": "",
        "onvalue": "0",
        "onvalueType": "num",
        "onicon": "",
        "oncolor": "green",
        "offvalue": "1",
        "offvalueType": "num",
        "officon": "",
        "offcolor": "red",
        "animate": true,
        "className": "",
        "x": 250,
        "y": 200,
        "wires": [
            [
                "7363fd0fb87da2bf",
                "a22e8a321accceb7"
            ]
        ]
    },
    {
        "id": "d75b2cb4e40d46d8",
        "type": "mqtt out",
        "z": "0bc70d3a568e5fe7",
        "name": "Envia ao Broker",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarBluetooth",
        "qos": "2",
        "retain": "true",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "03fa7ff17c898856",
        "x": 900,
        "y": 460,
        "wires": []
    },
    {
        "id": "19bbf50a8fe7ecba",
        "type": "ui_switch",
        "z": "0bc70d3a568e5fe7",
        "name": "",
        "label": "Bluetooth",
        "tooltip": "",
        "group": "d7c12b74.277828",
        "order": 6,
        "width": 0,
        "height": 0,
        "passthru": true,
        "decouple": "false",
        "topic": "ESP32-MinhaCasa/QuartoRobson/LigarBluetooth",
        "topicType": "str",
        "style": "",
        "onvalue": "0",
        "onvalueType": "num",
        "onicon": "",
        "oncolor": "",
        "offvalue": "1",
        "offvalueType": "num",
        "officon": "",
        "offcolor": "",
        "animate": true,
        "className": "",
        "x": 300,
        "y": 440,
        "wires": [
            [
                "d75b2cb4e40d46d8",
                "a22e8a321accceb7"
            ]
        ]
    },
    {
        "id": "c423173b55e0e1e9",
        "type": "ui_gauge",
        "z": "d1609a41d0822de3",
        "name": "Temperatura",
        "group": "f12b6b658291d542",
        "order": 1,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "Temperatura",
        "label": "deg C",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "className": "",
        "x": 890,
        "y": 300,
        "wires": []
    },
    {
        "id": "64f81d95af4f58e0",
        "type": "ui_gauge",
        "z": "d1609a41d0822de3",
        "name": "Umidade",
        "group": "f12b6b658291d542",
        "order": 2,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "Umidade",
        "label": "%",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "className": "",
        "x": 900,
        "y": 500,
        "wires": []
    },
    {
        "id": "276e68f36a4d0b2e",
        "type": "mqtt in",
        "z": "d1609a41d0822de3",
        "name": "",
        "topic": "ESP32-MinhaCasa/QuartoRobson/Temperatura",
        "qos": "2",
        "datatype": "auto",
        "broker": "03fa7ff17c898856",
        "nl": false,
        "rap": false,
        "inputs": 0,
        "x": 340,
        "y": 360,
        "wires": [
            [
                "c423173b55e0e1e9",
                "a33a4e629b26e836"
            ]
        ]
    },
    {
        "id": "ce60f41a5202543d",
        "type": "mqtt in",
        "z": "d1609a41d0822de3",
        "name": "",
        "topic": "ESP32-MinhaCasa/QuartoRobson/Umidade",
        "qos": "2",
        "datatype": "auto",
        "broker": "ae4b8351.dfe6f8",
        "nl": false,
        "rap": false,
        "inputs": 0,
        "x": 350,
        "y": 440,
        "wires": [
            [
                "64f81d95af4f58e0",
                "a33a4e629b26e836"
            ]
        ]
    },
    {
        "id": "a33a4e629b26e836",
        "type": "debug",
        "z": "d1609a41d0822de3",
        "name": "",
        "active": false,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "false",
        "statusVal": "",
        "statusType": "auto",
        "x": 780,
        "y": 400,
        "wires": []
    }
]