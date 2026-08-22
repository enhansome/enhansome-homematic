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
* [Homematic Forum: HomeMatic - Tipps für Anfänger](https://homematic-forum.de/forum/viewtopic.php?f=31\&t=22801) - Pflichtlektüre für Einsteiger von Sammy
* [Homematic Guru](https://homematic-guru.de/) - News, Blog, Tutorials und mehr.
* [Homematic Inside](https://www.homematic-inside.de/) - News, Blog, Tutorials und mehr.
* [Homematic Blog Lison](https://homematic-blog.lison.ch/) - Blog, Tutorials und mehr..
* [Technikkram](https://technikkram.net) - News, Blog, Tutorials und mehr.
* [OwnSmartHome](https://ownsmarthome.de/category/homematic/) - News, Blog, Tutorials und mehr.
* [Verdrahtet](https://www.verdrahtet.info/) - News, Blog, Youtube, Tutorials, ...
* [Wikimatic](http://www.wikimatic.de/wiki/Hauptseite) - Community Wiki.

## Documentation

* [Dissecting HomeMatic AES](https://git.zerfleddert.de/hmcfgusb/AES/) - BidCos Protocol AES Handshake description.
* [Direktverknüpfungen im Expertenmodus](https://www.youtube.com/watch?v=1B4iwtK1Rmo) - Vortrag von Frank Grass.
* [Virtuelle Aktorkanäle](https://www.youtube.com/watch?v=Cwxwtig6Q1I) - Vortrag von Frank Grass.
* [Script Documentation](http://www.wikimatic.de/wiki/Script_Dokumentation) - Inoffizielle Homematic Script Referenz.
* [Keymatic Konfiguration](https://homematic-forum.de/forum/viewtopic.php?f=31\&t=19196) - Beitrag von rewe0815 im Homematic Forum.

## Mobile Apps

* [@home](https://www.athomeapp.de/) - iOS - (💵 inApp-Purchase um Werbung zu entfernen)
* [HistClient](https://www.sa-com.de/smarthome-special/histclient-handbuch/) - (💵 inApp-Purchase) - CCU-Historian Client mit erweitereten Features für iOS und Android
* [Home-24](http://www.home-24.net/index.php?page=sites/home.php\&app=home24) - 💵 Android
* [HomeControl](http://www.ksquare.de/myhomecontrol/) - 💵 iOS
* [TinyMatic](https://www.tinymatic.de/) - 💵 Android (ehemals: HomeDroid)
* [Pocket Control](https://www.penzler.de) - 💵 iOS
* [Battery Status for HomeMatic](https://zeezide.com/en/products/hmbattery/) - 💵 iOS

## CCU Alternatives

* [RaspberryMatic](https://github.com/jens-maus/RaspberryMatic) ⭐ 1,824 | 🐛 187 | 🌐 JavaScript | 📅 2026-08-21 - Lightweight, OCCU and Linux/buildroot-based distribution for running a HomeMatic CCU on embedded devices like the RaspberryPi.
* [piVCCU](https://github.com/alexreinert/piVCCU) ⭐ 315 | 🐛 10 | 🌐 C | 📅 2026-04-16 - Install the original Homematic CCU firmware inside a virtualized container (lxc) on Raspbian or Armbian.
* [debmatic](https://github.com/alexreinert/debmatic) ⭐ 201 | 🐛 5 | 🌐 Shell | 📅 2025-12-08 - Install the Homematic OCCU on Debian based amd64, armhf and arm64 systems (Debian, Ubuntu, Raspbian, Armbian)
* [docker-ccu](https://github.com/angelnu/docker-ccu) ⚠️ Archived - Homematic CCU firmware running as [Docker](https://www.docker.com) container on arm and (emulated) x86.
* [Homegear](https://homegear.eu/index.php/Main_Page) - Free and open source program to interface your smart home devices with your home automation software or your own scripts.

## Alternative Sensors, Actuators and Hardware Modifications

* [AskSinPPCollection](https://jp112sdl.github.io/AskSinPPCollection/) - Einführung, Dokumentation und Projekte rund um Selbstbau-Komponenten mit AskSinPP
* [Beispiel\_AskSinPP](https://github.com/jp112sdl/Beispiel_AskSinPP) ⭐ 94 | 🐛 3 | 📅 2025-06-29 - Beispiel Sketche für die Verwendung der [AskSinPP](https://github.com/pa-pa/AskSinPP) ⭐ 109 | 🐛 21 | 🌐 C++ | 📅 2024-07-07 Bibliothek
* [HAUS-BUS.DE](http://www.haus-bus.de/) - 💵 Homematic Wired kompatible Geräte.
* [Homematic Wired Hombrew Hardware](https://github.com/jfische) - Verschiedene Homebrew Sensoren/Aktoren für Homematic Wired.
* [stall.biz](https://www.stall.biz/) - 💵 Alternative Antennen, Multi Sensor für das Wohnzimmer, Wetterstation, ...

## CCU Addons

* [RedMatic](https://github.com/rdmtc/RedMatic) ⭐ 532 | 🐛 178 | 🌐 HTML | 📅 2026-07-18 - [Node-RED](https://nodered.org/) als Addon für die Homematic CCU3 und RaspberryMatic. Liefert u.A. komfortable HomeKit-Integration und spezielle Nodes zur Anbindung der CCU an MQTT mit.
* [HAP-HomeMatic](https://github.com/thkl/hap-homematic) ⚠️ Archived - RaspberryMatic / CCU3 addon to access your HomeMatic devices from HomeKit. Its much like <https://github.com/thkl/homebridge-homematic> ⚠️ Archived but without homebridge.
* [XML-API](https://github.com/hobbyquaker/xml-api) ⭐ 128 | 🐛 16 | 🌐 Tcl | 📅 2024-03-14 - Vereinfachter CCU Zugriff via HTTP/XML.
* [hm\_pdetect](https://github.com/jens-maus/hm_pdetect) ⭐ 73 | 🐛 49 | 🌐 Tcl | 📅 2023-07-13 - Anwesenheitserkennung über die FRITZ!-Box
* [Homematic-addon-hue](https://github.com/j-a-n/homematic-addon-hue) ⚠️ Archived - HomeMatic Addon für Philips Hue.
* [Email](https://github.com/jens-maus/hm_email) ⭐ 47 | 🐛 15 | 🌐 HTML | 📅 2023-01-05 - HomeMatic CCU Addon für den Email Versand.
* [rmupdate](https://github.com/j-a-n/raspberrymatic-addon-rmupdate) ⚠️ Archived - RaspberryMatic Addon das RaspberryMatic selbst aktualisieren kann, vereinfacht die WLAN Konfiguration mit GUI und kann andere Addons ohne Zwangsreboot installieren und aktualisieren
* [Mosquitto](https://github.com/hobbyquaker/ccu-addon-mosquitto) ⭐ 33 | 🐛 13 | 🌐 Shell | 📅 2022-06-18 - Mosquitto packaged as Addon for the Homematic CCU3 and RaspberryMatic
* [hm-tools](https://github.com/fhetty/hm-tools) ⭐ 26 | 🐛 5 | 🌐 C | 📅 2023-07-30 - Sammlung von Tools für RaspberryMatic.
* [homematic\_check\_mk](https://github.com/alexreinert/homematic_check_mk) ⭐ 22 | 🐛 8 | 🌐 Tcl | 📅 2022-01-12 - Addon for the Homematic CCU2 or a Raspberrymatic device which acts as an check\_mk\_agent.
* [hm-print](https://github.com/litti/hm-print) ⭐ 12 | 🐛 10 | 🌐 CSS | 📅 2022-12-13 - CCU Programme drucken.
* [Redis](https://github.com/hobbyquaker/ccu-addon-redis) ⭐ 2 | 🐛 1 | 🌐 Shell | 📅 2018-07-29 - Redis packaged as Addon for the Homematic CCU3 and RaspberryMatic
* [Patcher](https://github.com/hobbyquaker/Patcher) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2020-01-01 - CCU3 Addon zur komfortablen Anwendung von Patches.
* [jq](https://github.com/hobbyquaker/ccu-addon-jq) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2019-09-26 - jq packaged as Addon for the Homematic CCU3.
* [CCU Historian](https://ccu-historian.de/) - Langzeit Archiv und Graphen.
* [CUxD](https://www.homematic-inside.de/software/tag/Zusatzsoftware) - Der "Leatherman" für die CCU. Verbindet FS20, ... (💵 EnOcean, ...), stellt virtuelle Geräte und hilfreiche Tools zur Verfügung.
* [Homeputer](https://www.contronics.de/shop/HomeMatic-System/Zentralen-und-Software.html) - 💵

## Interfacing Software

* [homebridge-homematic](https://github.com/thkl/homebridge-homematic) ⚠️ Archived - [Homebridge](https://github.com/nfarina/homebridge) ⭐ 25,460 | 🐛 17 | 🌐 TypeScript | 📅 2026-08-22 Plugin zur Einbindung von Homematic Geräten in HomeKit.
* [CCU-Jack](https://github.com/mdzio/ccu-jack) ⭐ 145 | 🐛 33 | 🌐 Go | 📅 2026-08-22 - CCU-Jack bietet einen einfachen und sicheren REST-basierten Zugriff auf die CCU, auch als Addon verfügbar.
* [homebridge-homematicip](https://github.com/marcsowen/homebridge-homematicip) ⭐ 86 | 🐛 80 | 🌐 TypeScript | 📅 2026-08-21 - [Homebridge](https://github.com/nfarina/homebridge) ⭐ 25,460 | 🐛 17 | 🌐 TypeScript | 📅 2026-08-22 Plugin zur Einbindung von Homematic IP mit HmIP-HAP via Cloud.
* [node-red-contrib-ccu](https://github.com/rdmtc/node-red-contrib-ccu) ⭐ 69 | 🐛 62 | 🌐 JavaScript | 📅 2026-07-18 - [Node-RED](https://nodered.org) Nodes for the Homematic CCU.
* [hvl - Homematic Virtual Interface](https://github.com/thkl/Homematic-Virtual-Interface) ⚠️ Archived - Bindet Fremdgeräte (z.B. Hue, Harmony, Netatmo, Sonos) über Plugins ein, auch als Addon verfügbar.

## Misc Software

* [homematic-manager](https://github.com/hobbyquaker/homematic-manager) ⭐ 197 | 🐛 55 | 🌐 JavaScript | 📅 2024-07-23 - Manage homematic interface processes (rfd/hs485d/homegear).
* [HomeHub](https://github.com/Gerti1972/homehub) ⭐ 18 | 🐛 0 | 🌐 PHP | 📅 2026-08-19 - PHP/XML-API basiertes Webfrontend. [Forum](https://homematic-forum.de/forum/viewtopic.php?f=41\&t=50538)
* [check\_homematic](https://github.com/hobbyquaker/check_homematic) ⭐ 6 | 🐛 3 | 🌐 JavaScript | 📅 2018-11-04 - Nagios/Icinga Plugin for checking Homematic CCU.
* [language-homematic](https://github.com/Ayngush/language-homematic) ⭐ 5 | 🐛 0 | 📅 2017-06-17 - Adds syntax highlighting and snippets to HomeMatic Script files in Atom.
* [hm-simulator](https://github.com/hobbyquaker/hm-simulator) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2019-10-02 - Simulates (partly) a Homematic CCU.
* [occu-test](https://github.com/hobbyquaker/occu-test) ⭐ 3 | 🐛 6 | 🌐 JavaScript | 📅 2026-07-13 - Automated System Tests of ReGaHss - the HomeMatic (O)CCU "Logic Layer".
* [hmcfgusb](https://git.zerfleddert.de/cgi-bin/gitweb.cgi/hmcfgusb) - Utilities to use the HM-CFG-USB(2) on Linux/Unix.
* [HMScriptEditor](https://zeezide.com/en/products/hmscripteditor/) - A very simple macOS editor and runner for HomeMatic ("Rega") scripts.

## Software Modules

* [pyhomematic](https://github.com/danielperna84/pyhomematic) ⚠️ Archived - Python 3 Interface to interact with Homematic devices.
* [pmatic](https://github.com/LarsMichelsen/pmatic) ⭐ 35 | 🐛 15 | 🌐 Python | 📅 2022-01-26 - Python API for Homematic. Easy to use.
* [binrpc](https://github.com/hobbyquaker/binrpc) ⭐ 15 | 🐛 1 | 🌐 JavaScript | 📅 2019-05-12 - Xmlrpc\_bin protocol client and server Node.js module.
* [homematic-rega](https://github.com/hobbyquaker/homematic-rega) ⭐ 8 | 🐛 2 | 🌐 JavaScript | 📅 2020-08-03 - Node.js Homematic CCU ReGaHSS Remote Script Interface.
* [hm-discover](https://github.com/hobbyquaker/hm-discover) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2022-08-15 - Node.js module to discover Homematic CCUs and interfaces.
* [homematic-xmlrpc](https://github.com/hobbyquaker/homematic-xmlrpc) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2021-08-09 - Xmlrpc client and server Node.js module.
* [homematicip-rest-api](https://github.com/coreGreenberet/homematicip-rest-api) ⭐ 2 | 🐛 0 | 📅 2022-07-12 - Python wrapper for the homematicIP REST API (Cloud / Access Point Based).
* [homematic-gqls](https://github.com/martin-riedl/homematic-gqls) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-07-06 - A GraphQL service to query Homematic IP components based on [homematicip-rest-api](https://github.com/coreGreenberet/homematicip-rest-api) ⭐ 2 | 🐛 0 | 📅 2022-07-12.

## Smart Home Software supporting Homematic

* [everHome](https://everhome.de) - 💵
* [FHEM](https://fhem.de/)
* [Home Assistant](https://www.home-assistant.io/)
* [ioBroker](https://www.iobroker.net/?lang=de)
* [IP-Symcon](https://www.symcon.de/) - 💵
* [Mediola](https://www.mediola.com/) - 💵
* [OpenHAB](https://www.openhab.org/)
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

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._
