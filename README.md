![Logo](admin/homepilot.png)
# ioBroker20.homepilot

![Number of Installations](http://iobroker.live/badges/homepilot20-installed.svg) ![Number of Installations](http://iobroker.live/badges/homepilot20-stable.svg) [![NPM version](http://img.shields.io/npm/v/iobroker.homepilot20.svg)](https://www.npmjs.com/package/iobroker.homepilot20)
[![Downloads](https://img.shields.io/npm/dm/iobroker.homepilot20.svg)](https://www.npmjs.com/package/iobroker.homepilot20)

[![NPM](https://nodei.co/npm/iobroker.homepilot20.png?downloads=true)](https://nodei.co/npm/iobroker.homepilot20/)

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/41e0e541711c47b996f11a2439a6663c)](https://www.codacy.com/app/homecineplexx/ioBroker.homepilot20?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=homecineplexx/ioBroker.homepilot20&amp;utm_campaign=Badge_Grade)

**Tests:** Linux/Mac: [![Travis-CI](http://img.shields.io/travis/homecineplexx/ioBroker.homepilot20/master.svg)](https://travis-ci.com/homecineplexx/ioBroker.homepilot20)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/homecineplexx/ioBroker.homepilot20?branch=master&svg=true)](https://ci.appveyor.com/project/homecineplexx/ioBroker-homepilot20/)


:de: [Dokumentation](/docs/de/doc_homepilot20_de.md)


## Changelog
### 0.0.31
* (homecineplexx) Fixed issues with motion detector

!!! Attention !!! do the following before the update
1) Stop the Homepilot20 instance
2) delete the complete Homepilot20 object tree (all data points)
3) Upgrade Homepilot20
4) Start the instance


### 0.0.30
* (homecineplexx) added slatposition to device 35000662

### 0.0.29
* (homecineplexx) fix some issues found by adapter checker

### 0.0.28
* (homecineplexx) fix some issues found by adapter checker

### 0.0.27
* (homecineplexx) Update Readme

### 0.0.26
* (homecineplexx) fix warnings during startup

### 0.0.25
* (homecineplexx) fix warnings during startup

### 0.0.24
* (homecineplexx) fix timestamp min value

### 0.0.23
* (homecineplexx) Update Readme

### 0.0.22
* (homecineplexx) fixed some issues

### 0.0.21
* (homecineplexx) Added devices: RolloTube S-line Sun DuoFern SLDSM 30/40/50

### 0.0.20
* (homecineplexx) Update Readme

### 0.0.19
* (homecineplexx) fix issue for missing common.type

### 0.0.18
* (homecineplexx) fix issue with Brdige and automatic modes

### 0.0.17
* (homecineplexx) added autmatic mode for two more devices:
* 16234511 DuoFern-RolloTron-Comfort-1800/1805/1840
* 23602075 DuoFern-S-Line-Motor-Typ-SLDM-10/16-PZ

### 0.0.16
* (homecineplexx) correction of slatposition command (SET_SLAT_POS_CMD) 

### 0.0.15
* (homecineplexx) bugfix - write permissions for slatposition

### 0.0.14
* (homecineplexx) added autmatic mode to following devices:
* 35003064 DuoFern-Heizkörperstellantrieb-9433
* 35000262 DuoFernUniversal-Aktor2-Kanal-9470-2
* 14234511 DuoFern-RolloTronStandard
* 14236011 DuoFern-RolloTron-Pro-Comfort-9800
* 35000864 DuoFern-Connect-Aktor-9477
* 32000064 DuoFern-Umweltsensor-9475
* 32501812 DuoFern-Raumthermostat-9485
* 35001164 DuoFern-Zwischenstecker-Schalten-9472
* 35000662 DuoFern-Rohrmotor-Aktor
* 35002414 ZWave-RepeaterMitSchaltfunktion-8434

### 0.0.13
* (homecineplexx) added SLATPOSITION setting for DuoFern-TrollBasis-5615 (testversion)

### 0.0.12
* (homecineplexx) Support of the Bridge

### 0.0.11
* (homecineplexx) Support for INC_CMD and DEC_CMD

### 0.0.10
* (homecineplexx) bugfix for version 0.0.9

### 0.0.9
* (homecineplexx) bugfix for version 0.0.8

### 0.0.8
* (homecineplexx) added 1 more devices:
* 99999982 Philips Hue Ambiance Spot
* changed the warn log to debug for not included devices

### 0.0.7
* (homecineplexx) added 1 more devices:
* 99999981 Philips Hue White Lamp

### 0.0.6
* (homecineplexx) added 5 more devices:
* 99999980 Philips Hue Bridge
* 99999983 Philips Hue RGB Lamp
* 32004219 HD Kamera (innen) 9486
* 32501973 DuoFern Wandtaster 1-Kanal 9494-3
* 23602075 DuoFern-S-Line-Motor-Typ-SLDM-10/16-PZ

### 0.0.5
* (homecineplexx) added 3 more devices:
* 32480361 DuoFern Handsender Standard 9491-2
* 32004119 IP Kamera 9483
* 45059071 RolloPort SX5 DuoFern RP-SX5DF-900N-3

### 0.0.4
* (homecineplexx) fixed wrong unreach state of Homepilot 2

### 0.0.3
* (homecineplexx) added device error messages to datapoints
* (homecineplexx) added scenes from Homepilot2
* (homecineplexx) documentation adapted (README)

### 0.0.2
* (homecineplexx) a lot of bug fixes

### 0.0.1
* (homecineplexx) initial release

## License
MIT License

Copyright (c) 2021 homecineplexx <chris.homecineplexx@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
