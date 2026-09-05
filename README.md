# Awesome Homematic with stars

> A curated list of Homematic related links

[Homematic](https://www.homematic.com/) is a series of Smart Home devices from the manufacturer [eQ-3](https://www.eq-3.de), popular especially in Germany.

## Contents

* [Community](#community)
* [Documentation](#documentation)
* [Mobile Apps](#mobile-apps)
* [CCU Alternatives](#ccu-alternatives)
* [Alternative Sensors and Actuators](#alternative-sensors-and-actuators)
* [CCU Addons](#ccu-addons)
* [Interfacing Software](#interfacing-software)
* [Misc Software](#misc-software)
* [Software Modules](#software-modules)
* [Smart Home Software](#smart-home-software-supporting-homematic)
* [Verschiedenes](#misc)
* [License](License)

## Community Ressources (mostly german language)

* [Haus Automatisierung](https://haus-automatisierung.com/) - News, Blog, Youtube, Tutorials, ...
* [Homematic Forum](https://homematic-forum.de/forum/) - Diskussions-Foren
* [Homematic Forum: Link/Skript-Sammlung](https://homematic-forum.de/forum/viewtopic.php?f=26\&t=27907) - Curated link list by AndiN.
* [Homematic Forum: Addons & Tools Übersicht](https://homematic-forum.de/forum/viewtopic.php?t=46890) - Übersicht über Addons und Tools für CCU / OpenCCU.
* [Homematic Forum: HomeMatic - Tipps für Anfänger](https://homematic-forum.de/forum/viewtopic.php?f=31\&t=22801) - Pflichtlektüre für Einsteiger von Sammy
* [Homematic Guru](https://homematic-guru.de/) - News, Blog, Tutorials und mehr.
* [Homematic Inside](https://www.homematic-inside.de/) - News, Blog, Tutorials und mehr (wird nicht weitergeführt, bleibt als Archiv online).
* [Homematic Blog Lison](https://homematic-blog.lison.ch/) - Blog, Tutorials und mehr..
* [Technikkram](https://technikkram.net) - News, Blog, Tutorials und mehr.
* [Verdrahtet](https://www.verdrahtet.info/) - News, Blog, Youtube, Tutorials, ...
* [Wikimatic](http://www.wikimatic.de/wiki/Hauptseite) - Community Wiki.

## Documentation

* [OpenCCU Wiki](https://github.com/OpenCCU/OpenCCU/wiki) ⭐ 1,826 | 🐛 195 | 🌐 JavaScript | 📅 2026-09-05 - Installation, Administration und Nutzung von OpenCCU.
* [ccu-addon-howto](https://github.com/homematic-community/ccu-addon-howto) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2026-09-05 - Howto für die Entwicklung von Addons für die Homematic CCU und OpenCCU.
* [Direktverknüpfungen im Expertenmodus](https://www.youtube.com/watch?v=1B4iwtK1Rmo) - Vortrag von Frank Grass.
* [Dissecting HomeMatic AES](https://git.zerfleddert.de/hmcfgusb/AES/) - BidCos Protocol AES Handshake description.
* [HomeMatic-Script Dokumentation](https://www.eq-3.de/downloads/download/homematic/hm_web_ui_doku/HM-Skript_Teil_1_Sprachbeschreibung_V2.3.pdf) - Offizielle Dokumentation von eQ-3: [Teil 1 Sprachbeschreibung](https://www.eq-3.de/downloads/download/homematic/hm_web_ui_doku/HM-Skript_Teil_1_Sprachbeschreibung_V2.3.pdf), [Teil 2 Objektmodell](https://www.eq-3.de/Downloads/eq3/download%20bereich/hm_web_ui_doku/HM_Script_Teil_2_Objektmodell_V1.2.pdf), [Teil 3 Beispiele](https://www.eq-3.de/Downloads/eq3/download%20bereich/hm_web_ui_doku/HM_Script_Teil_3_Beispiele_V1.1.pdf), [Teil 4 Datenpunkte](https://www.eq-3.de/Downloads/eq3/download%20bereich/hm_web_ui_doku/HM-Script_4-Datenpunkte.pdf).
* [HomeMatic XML-RPC API](https://www.eq-3.de/Downloads/eq3/download%20bereich/hm_web_ui_doku/HM_XmlRpc_API.pdf) - Offizielle Spezifikation der XML-RPC Schnittstelle der Interface-Prozesse von eQ-3.
* [Keymatic Konfiguration](https://homematic-forum.de/forum/viewtopic.php?f=31\&t=19196) - Beitrag von rewe0815 im Homematic Forum.
* [Script Documentation](http://www.wikimatic.de/wiki/Script_Dokumentation) - Inoffizielle Homematic Script Referenz.
* [Virtuelle Aktorkanäle](https://www.youtube.com/watch?v=Cwxwtig6Q1I) - Vortrag von Frank Grass.

## Mobile Apps

* [@home](https://www.athomeapp.de/) - iOS - (💵 inApp-Purchase um Werbung zu entfernen)
* [HistClient](https://www.sa-com.de/smarthome-special/histclient-handbuch/) - (💵 inApp-Purchase) - CCU-Historian Client mit erweitereten Features für iOS und Android
* [TinyMatic](https://www.tinymatic.de/) - 💵 Android (ehemals: HomeDroid)
* [Pocket Control](https://www.penzler.de) - 💵 iOS
* [Battery Status for HomeMatic](https://zeezide.com/en/products/hmbattery/) - 💵 iOS

## CCU Alternatives

* [OpenCCU](https://github.com/OpenCCU/OpenCCU) ⭐ 1,826 | 🐛 195 | 🌐 JavaScript | 📅 2026-09-05 - Lightweight, OCCU and Linux/buildroot-based distribution for running a HomeMatic CCU on embedded devices like the RaspberryPi, x86/ARM or as virtual appliance (formerly known as RaspberryMatic).
* [piVCCU](https://github.com/alexreinert/piVCCU) ⭐ 315 | 🐛 10 | 🌐 C | 📅 2026-04-16 - Install the original Homematic CCU firmware inside a virtualized container (lxc) on Raspbian or Armbian.
* [OCCU](https://github.com/eq-3/occu) ⭐ 213 | 🐛 65 | 🌐 Tcl | 📅 2026-07-15 - The HM-OCCU-SDK published by eQ-3, the base of debmatic, piVCCU and OpenCCU.
* [debmatic](https://github.com/alexreinert/debmatic) ⭐ 201 | 🐛 5 | 🌐 Shell | 📅 2025-12-08 - Install the Homematic OCCU on Debian based amd64, armhf and arm64 systems (Debian, Ubuntu, Raspbian, Armbian)
* [Homegear](https://homegear.eu/index.php/Main_Page) - Free and open source program to interface your smart home devices with your home automation software or your own scripts.

## Alternative Sensors, Actuators and Hardware Modifications

* [Beispiel\_AskSinPP](https://github.com/jp112sdl/Beispiel_AskSinPP) ⭐ 95 | 🐛 3 | 📅 2025-06-29 - Beispiel Sketche für die Verwendung der [AskSinPP](https://github.com/pa-pa/AskSinPP) ⭐ 109 | 🐛 21 | 🌐 C++ | 📅 2024-07-07 Bibliothek
* [HB-UNI-Sen-WEA](https://github.com/jp112sdl/HB-UNI-Sen-WEA) ⭐ 69 | 🐛 0 | 🌐 C++ | 📅 2024-12-04 - Selbstbau-Wetterstation für HomeMatic.
* [HB-RF-ETH](https://github.com/alexreinert/HB-RF-ETH) ⭐ 58 | 🐛 3 | 🌐 C++ | 📅 2026-07-21 - Platine und Firmware um ein Homematic Funkmodul (HM-MOD-RPI-PCB, RPI-RF-MOD) per Netzwerk an debmatic oder piVCCU anzubinden.
* [HB-RF-ETH-ng](https://github.com/Xerolux/HB-RF-ETH-ng) ⭐ 14 | 🐛 1 | 🌐 C++ | 📅 2026-09-04 - Modernisierte Next-Generation-Firmware für die HB-RF-ETH Platine mit neuer Weboberfläche und MQTT-Monitoring.
* [AskSin++](https://asksinpp.de/) - Dokumentation, Sketche und Community-Projekte rund um Selbstbau-Komponenten für HomeMatic auf Basis von Arduino/STM32 und CC1101.
* [AskSinPPCollection](https://jp112sdl.github.io/AskSinPPCollection/) - Einführung, Dokumentation und Projekte rund um Selbstbau-Komponenten mit AskSinPP
* [HAUS-BUS.DE](http://www.haus-bus.de/) - 💵 Homematic Wired kompatible Geräte.
* [Homematic Wired Hombrew Hardware](https://github.com/jfische) - Verschiedene Homebrew Sensoren/Aktoren für Homematic Wired.
* [stall.biz](https://www.stall.biz/) - 💵 Alternative Antennen, Multi Sensor für das Wohnzimmer, Wetterstation, ...

## CCU Addons

* [RedMatic](https://github.com/rdmtc/RedMatic) ⭐ 530 | 🐛 1 | 🌐 Shell | 📅 2026-09-05 - [Node-RED](https://nodered.org/) als Addon für die Homematic CCU3 und OpenCCU. Liefert u.A. komfortable HomeKit-Integration und spezielle Nodes zur Anbindung der CCU an MQTT mit.
* [HAP-HomeMatic](https://github.com/thkl/hap-homematic) ⚠️ Archived - OpenCCU / CCU3 addon to access your HomeMatic devices from HomeKit. Its much like <https://github.com/thkl/homebridge-homematic> ⚠️ Archived but without homebridge (archived).
* [XML-API](https://github.com/homematic-community/XML-API) ⭐ 128 | 🐛 16 | 🌐 Tcl | 📅 2024-03-14 - Vereinfachter CCU Zugriff via HTTP/XML.
* [hm\_pdetect](https://github.com/homematic-community/hm_pdetect) ⭐ 73 | 🐛 49 | 🌐 Tcl | 📅 2023-07-13 - Anwesenheitserkennung über die FRITZ!-Box
* [CUxD](https://github.com/jens-maus/cuxd) ⭐ 67 | 🐛 0 | 🌐 C | 📅 2023-04-05 - Der "Leatherman" für die CCU. Verbindet FS20, ... (💵 EnOcean, ...), stellt virtuelle Geräte und hilfreiche Tools zur Verfügung.
* [JP-HB-Devices-addon](https://github.com/jp112sdl/JP-HB-Devices-addon) ⭐ 57 | 🐛 0 | 🌐 Tcl | 📅 2025-09-18 - Addon das über 80 Selbstbau-Geräte (AskSinPP HomeBrew) in die CCU/OpenCCU Firmware integriert.
* [HQ-WebUI](https://github.com/homematic-community/hq-webui) ⭐ 50 | 🐛 8 | 🌐 JavaScript | 📅 2022-06-17 - Schnelles alternatives WebUI für die Homematic CCU mit Skript-Editor (verwaist, Maintainer gesucht).
* [Homematic-addon-hue](https://github.com/j-a-n/homematic-addon-hue) ⚠️ Archived - HomeMatic Addon für Philips Hue (archiviert).
* [Email](https://github.com/homematic-community/hm_email) ⭐ 47 | 🐛 15 | 🌐 HTML | 📅 2023-01-05 - HomeMatic CCU Addon für den Email Versand.
* [Mosquitto](https://github.com/homematic-community/ccu-addon-mosquitto) ⭐ 33 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-05 - Mosquitto packaged as Addon for the Homematic CCU3 and OpenCCU
* [WebMatic](https://github.com/ldittmar81/webmatic) ⭐ 27 | 🐛 21 | 🌐 JavaScript | 📅 2020-01-12 - Alternative, für Mobilgeräte optimierte Bedienoberfläche, läuft direkt auf der CCU.
* [hm-tools](https://github.com/fhetty/hm-tools) ⭐ 26 | 🐛 5 | 🌐 C | 📅 2023-07-30 - Sammlung von Tools für OpenCCU.
* [homematic\_check\_mk](https://github.com/alexreinert/homematic_check_mk) ⭐ 22 | 🐛 8 | 🌐 Tcl | 📅 2022-01-12 - Addon for the Homematic CCU2 or an OpenCCU device which acts as an check\_mk\_agent.
* [hm-sonos](https://github.com/homematic-community/hm-sonos) ⭐ 17 | 🐛 22 | 🌐 Tcl | 📅 2023-05-13 - HomeMatic CCU Addon zur Steuerung von Sonos Playern.
* [CUxD-Highcharts](https://github.com/homematic-community/CUxD-Highcharts) ⭐ 16 | 🐛 8 | 🌐 JavaScript | 📅 2019-10-21 - Visualisiert CUxD DEVLOGS mit Highcharts/Highstock (verwaist, Maintainer gesucht).
* [ScriptParser](https://github.com/homematic-community/scriptparser) ⭐ 13 | 🐛 2 | 🌐 JavaScript | 📅 2022-06-17 - Addon zur Syntaxprüfung von HomeMatic Skripten.
* [hm-print](https://github.com/homematic-community/hm-print) ⭐ 12 | 🐛 10 | 🌐 CSS | 📅 2022-12-13 - CCU Programme drucken.
* [ccu-addon-mui](https://github.com/firsttris/ccu-addon-mui) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-18 - Moderne, responsive Progressive Web App (PWA) für die CCU3 mit integriertem WebSocket-Server.
* [homematic-node-exporter](https://github.com/jaroschek/homematic-node-exporter) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2026-07-15 - Prometheus Node Exporter packaged as Addon for the Homematic CCU3 and OpenCCU.
* [Redis](https://github.com/hobbyquaker/ccu-addon-redis) ⚠️ Archived - Redis packaged as Addon for the Homematic CCU3 and OpenCCU
* [hm-influxdb2](https://github.com/cthil/hm-influxdb2) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2024-02-11 - Addon for the CCU3/OpenCCU to log data from devices into an InfluxDB2.
* [Patcher](https://github.com/hobbyquaker/Patcher) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2020-01-01 - CCU3 Addon zur komfortablen Anwendung von Patches.
* [jq](https://github.com/hobbyquaker/ccu-addon-jq) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2019-09-26 - jq packaged as Addon for the Homematic CCU3.
* [CCU Historian](https://ccu-historian.de/) - Langzeit Archiv und Graphen.

## Interfacing Software

* [homematicip\_local](https://github.com/SukramJ/homematicip_local) ⭐ 591 | 🐛 0 | 🌐 Python | 📅 2026-09-04 - [Home Assistant](https://www.home-assistant.io/) Custom Component zur lokalen Anbindung von CCU/OpenCCU (Homematic und Homematic IP), basiert auf aiohomematic.
* [homebridge-homematic](https://github.com/thkl/homebridge-homematic) ⚠️ Archived - [Homebridge](https://github.com/nfarina/homebridge) ⭐ 25,475 | 🐛 17 | 🌐 TypeScript | 📅 2026-08-30 Plugin zur Einbindung von Homematic Geräten in HomeKit.
* [CCU-Jack](https://github.com/mdzio/ccu-jack) ⭐ 146 | 🐛 32 | 🌐 Go | 📅 2026-08-30 - CCU-Jack bietet einen einfachen und sicheren REST-basierten Zugriff auf die CCU, auch als Addon verfügbar.
* [homebridge-homematicip](https://github.com/marcsowen/homebridge-homematicip) ⭐ 86 | 🐛 18 | 🌐 TypeScript | 📅 2026-08-28 - [Homebridge](https://github.com/nfarina/homebridge) ⭐ 25,475 | 🐛 17 | 🌐 TypeScript | 📅 2026-08-30 Plugin zur Einbindung von Homematic IP mit HmIP-HAP via Cloud.
* [homematicip-hcu](https://github.com/Ediminator/homematicip-hcu) ⭐ 73 | 🐛 6 | 🌐 Python | 📅 2026-09-05 - [Home Assistant](https://www.home-assistant.io/) Integration zur lokalen Anbindung der Homematic IP Home Control Unit (HCU) ohne Cloud.
* [node-red-contrib-ccu](https://github.com/rdmtc/node-red-contrib-ccu) ⭐ 69 | 🐛 18 | 🌐 JavaScript | 📅 2026-09-04 - [Node-RED](https://nodered.org) Nodes for the Homematic CCU.
* [RedMatic-HomeKit](https://github.com/rdmtc/RedMatic-HomeKit) ⭐ 58 | 🐛 25 | 🌐 JavaScript | 📅 2026-09-05 - HAP-Nodejs basierte Node-RED Nodes um (Homematic-)Geräte in HomeKit einzubinden.
* [hm2mqtt.js](https://github.com/hobbyquaker/hm2mqtt.js) ⭐ 23 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-02 - Node.js based interface between Homematic and MQTT.
* [ccu-mcp](https://github.com/claymore666/ccu-mcp) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-02 - MCP server enabling AI assistants to control Homematic devices via the CCU's JSON-RPC API, no addon required.
* [OpenCCU-Loom](https://github.com/SukramJ/openccu-loom) ⭐ 5 | 🐛 2 | 🌐 Go | 📅 2026-09-05 - Standalone Go daemon bridging Homematic / Homematic IP CCUs to MQTT (with Home Assistant Discovery), REST + WebSocket, an MCP server and a native Matter bridge.
* [matterbridge-homematic](https://github.com/hobbyquaker/matterbridge-homematic) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-16 - [Matterbridge](https://github.com/Luligu/matterbridge) ⭐ 965 | 🐛 7 | 🌐 TypeScript | 📅 2026-09-05 Plugin to bridge a Homematic CCU's devices to the Matter ecosystem.
* [CCU-AI-MCP](https://github.com/mdzio/ccu-ai-mcp) ⭐ 3 | 🐛 1 | 🌐 Go | 📅 2026-09-05 - MCP-Server für OpenCCU/CCU, gibt KI-Assistenten (LLMs) über konfigurierbare HM-Skripte Zugriff auf das Smart Home.
* [RedMatic-Matter](https://github.com/rdmtc/RedMatic-Matter) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-04 - Matter.js basierte Node-RED Nodes, die Homematic-Geräte und beliebige Node-RED-Daten als Matter-Bridge bereitstellen.

## Misc Software

* [homematic-manager](https://github.com/hobbyquaker/homematic-manager) ⭐ 197 | 🐛 55 | 🌐 JavaScript | 📅 2026-09-05 - Manage homematic interface processes (rfd/hs485d/homegear).
* [HMDeviceFirmware](https://github.com/OpenCCU/HMDeviceFirmware) ⭐ 33 | 🐛 0 | 🌐 Shell | 📅 2026-09-05 - Archive of current and past firmware update files for HomeMatic and Homematic IP devices.
* [HomeHub](https://github.com/homematic-community/homehub) ⭐ 18 | 🐛 0 | 🌐 PHP | 📅 2026-08-23 - PHP/XML-API basiertes Webfrontend. [Forum](https://homematic-forum.de/forum/viewtopic.php?f=41\&t=50538)
* [pydevccu](https://github.com/SukramJ/pydevccu) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-09-02 - Virtual HomeMatic CCU XML-RPC and JSON-RPC server with fake devices for development and testing.
* [HM-Explorer](https://github.com/thkl/HM-Explorer) ⭐ 8 | 🐛 8 | 🌐 JavaScript | 📅 2023-10-05 - Electron based helper app for the Homematic CCU (macOS/Windows).
* [check\_homematic](https://github.com/hobbyquaker/check_homematic) ⭐ 6 | 🐛 3 | 🌐 JavaScript | 📅 2018-11-04 - Nagios/Icinga Plugin for checking Homematic CCU.
* [language-homematic](https://github.com/Ayngush/language-homematic) ⭐ 5 | 🐛 0 | 📅 2017-06-17 - Adds syntax highlighting and snippets to HomeMatic Script files in Atom.
* [hm-buildroot](https://github.com/homematic-community/hm-buildroot) ⭐ 4 | 🐛 2 | 🌐 C++ | 📅 2016-01-05 - Buildroot environments / cross compiler toolchains to build native applications for the CCU and OpenCCU.
* [hm-simulator](https://github.com/hobbyquaker/hm-simulator) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2019-10-02 - Simulates (partly) a Homematic CCU.
* [ReGaHss-Test](https://github.com/OpenCCU/ReGaHss-Test) ⭐ 3 | 🐛 6 | 🌐 JavaScript | 📅 2026-07-13 - Automated System Tests of ReGaHss - the HomeMatic (O)CCU "Logic Layer" (formerly occu-test).
* [godevccu](https://github.com/SukramJ/godevccu) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2026-08-16 - Virtual HomeMatic CCU with XML-RPC and JSON-RPC servers written in Go, single static binary for testing integrations.
* [hmGetInfo](https://github.com/homematic-community/hmGetInfo) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2020-11-19 - Collect paramsets and paramsetDescriptions from your Homematic CCU as JSON.
* [hmcfgusb](https://git.zerfleddert.de/cgi-bin/gitweb.cgi/hmcfgusb) - Utilities to use the HM-CFG-USB(2) on Linux/Unix.
* [HMScriptEditor](https://zeezide.com/en/products/hmscripteditor/) - A very simple macOS editor and runner for HomeMatic ("Rega") scripts.
* [Homematic Script Language](https://marketplace.visualstudio.com/items?itemName=HeadCrash.hmscript-language-vscode) - Visual Studio Code extension providing syntax highlighting for HomeMatic Script (.hms) files.

## Software Modules

* [homematicip-rest-api](https://github.com/hahn-th/homematicip-rest-api) ⭐ 239 | 🐛 3 | 🌐 Python | 📅 2026-09-04 - Python wrapper for the homematicIP REST API (Cloud / Access Point Based).
* [aiohomematic](https://github.com/SukramJ/aiohomematic) ⭐ 167 | 🐛 1 | 🌐 Python | 📅 2026-09-04 - Python 3 interface to interact with Homematic devices via XML-RPC and JSON-RPC, successor of [pyhomematic](https://github.com/danielperna84/pyhomematic) ⚠️ Archived and base of homematicip\_local.
* [pmatic](https://github.com/LarsMichelsen/pmatic) ⭐ 35 | 🐛 15 | 🌐 Python | 📅 2022-01-26 - Python API for Homematic. Easy to use.
* [Homematic IP Connect API](https://github.com/homematicip/connect-api) ⭐ 34 | 🐛 0 | 🌐 HTML | 📅 2025-10-20 - Official WebSocket API and example plugins (Java, Node.js) for developing plugins for the Homematic IP Home Control Unit (HCU).
* [binrpc](https://github.com/hobbyquaker/binrpc) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-01 - Xmlrpc\_bin protocol client and server Node.js module.
* [homematic-rega](https://github.com/hobbyquaker/homematic-rega) ⭐ 8 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-28 - Node.js Homematic CCU ReGaHSS Remote Script Interface.
* [hm-discover](https://github.com/hobbyquaker/hm-discover) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2022-08-15 - Node.js module to discover Homematic CCUs and interfaces.
* [homematic-xmlrpc](https://github.com/hobbyquaker/homematic-xmlrpc) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-28 - Xmlrpc client and server Node.js module.
* [go-hmccu](https://github.com/mdzio/go-hmccu) ⭐ 5 | 🐛 1 | 🌐 Go | 📅 2026-08-18 - Go library for interfacing the CCU.
* [homematic-gqls](https://github.com/martin-riedl/homematic-gqls) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-07-06 - A GraphQL service to query Homematic IP components based on [homematicip-rest-api](https://github.com/hahn-th/homematicip-rest-api) ⭐ 239 | 🐛 3 | 🌐 Python | 📅 2026-09-04.
* [openccu-loom-client](https://github.com/SukramJ/openccu-loom-client) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-04 - Async Python REST + WebSocket client for the OpenCCU-Loom daemon.

## Smart Home Software supporting Homematic

* [Home Assistant](https://www.home-assistant.io/) - via [homematicip\_local](https://github.com/SukramJ/homematicip_local) ⭐ 591 | 🐛 0 | 🌐 Python | 📅 2026-09-04 (CCU/OpenCCU) oder [homematicip-hcu](https://github.com/Ediminator/homematicip-hcu) ⭐ 73 | 🐛 6 | 🌐 Python | 📅 2026-09-05 (HCU).
* [ioBroker](https://www.iobroker.net/?lang=de) - via [hm-rpc](https://github.com/ioBroker/ioBroker.hm-rpc) ⭐ 61 | 🐛 81 | 🌐 HTML | 📅 2026-09-04 (Interface-Prozesse) und [hm-rega](https://github.com/ioBroker/ioBroker.hm-rega) ⭐ 43 | 🐛 25 | 🌐 TypeScript | 📅 2026-08-31 (ReGaHSS) Adapter, [hmip](https://github.com/iobroker-community-adapters/ioBroker.hmip) ⭐ 31 | 🐛 38 | 🌐 JavaScript | 📅 2026-09-03 für den Homematic IP Cloud Access Point.
* [SmartHomeNG](https://www.smarthomeng.de/) - via [Plugins](https://github.com/smarthomeNG/plugins) ⭐ 44 | 🐛 9 | 🌐 Python | 📅 2026-09-04.
* [FHEM](https://fhem.de/) - via [HMCCU](https://wiki.fhem.de/wiki/HMCCU) Modul.
* [IP-Symcon](https://www.symcon.de/) - 💵
* [Mediola](https://www.mediola.com/) - 💵
* [OpenHAB](https://www.openhab.org/) - via [Homematic Binding](https://www.openhab.org/addons/bindings/homematic/).
* [Pimatic](https://pimatic.org/)

## Misc

* [AskSinAnalyzer](https://github.com/jp112sdl/AskSinAnalyzer) ⭐ 78 | 🐛 3 | 🌐 C | 📅 2023-09-10 - Funktelegramm-Dekodierer für den Einsatz in HomeMatic Umgebungen, hilfreich zur Fehlersuche, z.B. wenn der DutyCycle zu hoch ist.
* [AskSinAnalyzerXS](https://github.com/psi-4ward/AskSinAnalyzerXS) ⭐ 51 | 🐛 19 | 🌐 Vue | 📅 2023-03-04 - AskSinAnalyzer als Desktop App, verzichtet auf den Einsatz eines ESP.
* [eagle-homematic](https://github.com/dersimn/eagle-homematic) ⭐ 1 | 🐛 0 | 📅 2020-10-01 - Homematic Modul Eagle Bibliothek.
* [Tablet Wallmount](https://homematic-forum.de/forum/viewtopic.php?f=18\&t=49421) - Rahmen für Unterputzmontage von Tablets.
* [Homematic 3D Druck Collection auf Thingiverse](https://www.thingiverse.com/hobbyquaker/collections/homematic) - Diverse Teile rund um Homematic zum selbst drucken.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[Public Domain CC0](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-05._
