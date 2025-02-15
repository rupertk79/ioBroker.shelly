![Logo](admin/shelly.png)

# ioBroker.shelly

[![NPM version](https://img.shields.io/npm/v/iobroker.shelly?style=flat-square)](https://www.npmjs.com/package/iobroker.shelly)
[![Downloads](https://img.shields.io/npm/dm/iobroker.shelly?label=npm%20downloads&style=flat-square)](https://www.npmjs.com/package/iobroker.shelly)
![Snyk Vulnerabilities for npm package](https://img.shields.io/snyk/vulnerabilities/npm/iobroker.shelly?label=npm%20vulnerabilities&style=flat-square)
![node-lts](https://img.shields.io/node/v-lts/iobroker.shelly?style=flat-square)
![Libraries.io dependency status for latest release](https://img.shields.io/librariesio/release/npm/iobroker.shelly?label=npm%20dependencies&style=flat-square)

![GitHub](https://img.shields.io/github/license/iobroker-community-adapters/iobroker.shelly?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/iobroker-community-adapters/iobroker.shelly?logo=github&style=flat-square)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/iobroker-community-adapters/iobroker.shelly?logo=github&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/iobroker-community-adapters/iobroker.shelly?logo=github&style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/iobroker-community-adapters/iobroker.shelly?logo=github&style=flat-square)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/iobroker-community-adapters/iobroker.shelly/Test%20and%20Release?label=Test%20and%20Release&logo=github&style=flat-square)
![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/iobroker-community-adapters/iobroker.shelly?label=repo%20vulnerabilities&logo=github&style=flat-square)

## Versions

![Beta](https://img.shields.io/npm/v/iobroker.shelly.svg?color=red&label=beta)
![Stable](http://iobroker.live/badges/shelly-stable.svg)
![Installed](http://iobroker.live/badges/shelly-installed.svg)

The adapter communicates with Shelly devices by REST API and the CoAP or MQTT protocol.

Uses the default Shelly firmware (no flashing of firmware needed!). You will find more and detailed information about the device here : [Shelly](https://shelly.cloud/)

## Documentation

[🇺🇸 Documentation](./docs/en/README.md)

[🇩🇪 Dokumentation](./docs/de/README.md)

## Supported devices (Gen 1)

| Shelly Device                        | CoAP      | MQTT      | Tested firmware version                 |
| ------------------------------------ | --------- | --------- | --------------------------------------- |
| Shelly 1 (SHSW-1)                    | >= v3.3.0 | >= v3.3.0 | 20220809-123240/v1.12-g99f7e0b          |
| Shelly 1 1PM (SHSW-PM)               | >= v3.3.0 | >= v3.3.0 | 20220809-124723/v1.12-g99f7e0b          |
| Shelly 1L (SHSW-L)                   | >= v4.0.5 | >= v4.0.5 | n/a                                     |
| Shelly 2 (SHSW-21/SHSW-22)           | >= v3.3.0 | >= v3.3.0 | 20220809-123410/v1.12-g99f7e0b          |
| Shelly 2.5 (SHSW-25)                 | >= v3.3.0 | >= v3.3.0 | 20220809-123456/v1.12-g99f7e0b          |
| Shelly 4 Pro (SHSW-44)               | >= v3.3.5 | >= v3.3.5 | n/a                                     |
| Shelly Dimmer (SHDM-1)               | >= v3.3.0 | >= v3.3.0 | 20220825-080609/v1.12-Dimmer1-g0ed8d76  |
| Shelly Dimmer 2 (SHDM-2)             | >= v3.3.4 | >= v3.3.4 | n/a                                     |
| Shelly RGBW (SHRGBWW-01)             | < v3.4.0  | < v3.4.0  | n/a                                     |
| Shelly RGBW 2 (SHRGBW2)              | >= v3.3.0 | >= v3.3.0 | 20220809-124336/v1.12-g99f7e0b          |
| Shelly i3 (SHIX3-1)                  | >= v3.3.0 | >= v3.3.0 | 20220809-125301/v1.12-g99f7e0b          |
| Shelly EM (SHEM)                     | >= v3.3.0 | >= v3.3.0 | n/a                                     |
| Shelly 3EM (SHEM-3)                  | >= v3.3.0 | >= v3.3.0 | n/a                                     |
| Shelly H&T (SHHT-1)                  | >= v3.3.0 | >= v3.3.0 | 20220324-134040/v1.11.8-HT-fix-g60b9bd1 |
| Shelly Smoke (SHSM-01)               | >= v3.3.0 | >= v3.3.0 | 20220809-123549/v1.12-g99f7e0b          |
| Shelly Flood (SHWT-1)                | >= v3.3.0 | >= v3.3.0 | 20220809-123830/v1.12-g99f7e0b          |
| Shelly Gas (SHGS-1)                  | >= v3.3.3 | >= v3.3.3 | 20220809-125346/v1.12-g99f7e0b          |
| Shelly Door/Window Sensor (SHDW-1)   | >= v3.3.0 | >= v3.3.0 | n/a                                     |
| Shelly Door/Window Sensor 2 (SHDW-2) | >= v3.3.5 | >= v3.3.5 | 20220209-093605/v1.11.8-g8c7bb8d        |
| Shelly2LED (SH2LED)                  | >= v3.3.0 | >= v3.3.0 | n/a                                     |
| Shelly Plug (SHPLG-1)                | >= v3.3.0 | >= v3.3.0 | n/a                                     |
| Shelly Plug S (SHPLG-S)              | >= v3.3.0 | >= v3.3.0 | 20220809-124506/v1.12-g99f7e0b          |
| Shelly Plug 2 (SHPLG-2)              | >= v3.3.0 | >= v3.3.0 | n/a                                     |
| Shelly Sense (SHSEN-1)               | >= v3.3.0 | >= v3.3.0 | n/a                                     |
| Shelly Bulb (SHBLB)                  | >= v3.3.0 | >= v3.3.0 | n/a                                     |
| Shelly Bulb Duo (SHBDUO-1)           | >= v3.3.0 | >= v3.3.0 | 20220809-123026/v1.12-g99f7e0b          |
| Shelly Color Bulb (SHCB-1)           | >= v4.0.5 | >= v4.0.5 | 20220809-122808/v1.12-g99f7e0b          |
| Shelly Vintage (SHVIN-1)             | >= v3.3.0 | >= v3.3.0 | n/a                                     |
| Shelly Uni (SHUNI-1)                 | >= v4.0.4 | >= v4.0.4 | 20220809-125434/v1.12-g99f7e0b          |
| Shelly Button (SHBTN-1)              | >= v3.3.3 | >= v3.3.3 | 20220809-124206/v1.12-g99f7e0b          |
| Shelly Button (SHBTN-2)              | >= v4.0.5 | >= v4.0.5 | n/a                                     |
| Shelly Motion (SHMOS-01)             | >= v4.0.6 | >= v4.0.6 | 20220811-152232/v2.1.8@5afc928c         |
| Shelly TRV (SHTRV-01)                | >= v6.0.0 | >= v6.0.0 | 20220811-152343/v2.1.8@5afc928c         |
| Shelly Motion 2 (SHMOS-02)           | => v6.2.0 | >= v6.2.0 | 20220811-152232/v2.1.8@5afc928c         |

NOT Supported:

- USB powered UVC LED strip

## Supported devices (Gen 2)

| Shelly Device                    | CoAP | MQTT      | Tested firmware version         |
| -------------------------------- | ---- | --------- | ------------------------------- |
| Shelly Plus 1 (shellyplus1)      | ❌   | >= v5.0.0 | 20221004-113139/0.11.2-g2ea2af3 |
| Shelly Plus 1 PM (shellyplus1pm) | ❌   | >= v5.0.0 | 20221004-113326/0.11.2-g2ea2af3 |
| Shelly Plus 2 PM (shellyplus2pm) | ❌   | >= v5.2.0 | 20221004-113507/0.11.2-g2ea2af3 |
| Shelly Plus i4 (shellyplusi4)    | ❌   | >= v5.3.0 | n/a                             |
| Shelly Plus i4 DC (shellyplusi4) | ❌   | >= v5.3.0 | 20220830-130959/0.11.0-gfa1bc37 |
| Shelly Pro 1 (shellypro1)        | ❌   | >= v5.2.0 | 20221004-114457/0.11.2-g2ea2af3 |
| Shelly Pro 1 PM (shellypro1pm)   | ❌   | >= v5.2.0 | 20221004-114624/0.11.2-g2ea2af3 |
| Shelly Pro 2 (shellypro2)        | ❌   | >= v5.2.0 | 20221004-114751/0.11.2-g2ea2af3 |
| Shelly Pro 2 PM (shellypro2pm)   | ❌   | >= v5.2.0 | 20221004-114917/0.11.2-g2ea2af3 |
| Shelly Pro 3 (shellypro3)        | ❌   | >= v6.2.0 | 20221004-115048/0.11.2-g2ea2af3 |
| Shelly Pro 4 PM (shellypro4pm)   | ❌   | >= v5.0.0 | 20221004-115342/0.11.2-g2ea2af3 |
| Shelly Plus H&T (shellyplusht)   | ❌   | >= v6.2.0 | 20220830-130838/0.11.0-gfa1bc37 |

NOT Supported:

- Shelly Plus Wall Dimmer US
- Shelly Plus Plug US

## Sentry

**This adapter uses Sentry libraries to automatically report exceptions and code errors to the developers.** For more details and for information how to disable the error reporting see [Sentry-Plugin Documentation](https://github.com/ioBroker/plugin-sentry#plugin-sentry)! Sentry reporting is used starting with js-controller 3.0.

## Troubleshooting after installation

### TypeError: xmlserializer.Builder is not a constructor

execute

`cd /opt/iobroker/node_modules/iobroker.shelly npm install xml2js@0.4.23`

## Changelog

<!--
  Placeholder for the next version (at the beginning of the line):
  ### **WORK IN PROGRESS**
-->
### 6.2.4 (2022-10-23)

* (klein0r) IP address of CoAP devices is unknown in some cases
* (klein0r) Optimized destroy process

### 6.2.3 (2022-10-20)

* (klein0r) Use unique ID for each command - generation 2 devices
* (klein0r) Fix: Ack state if value is unchanged

### 6.2.2 (2022-10-13)

* (klein0r) Fixed state updates for CoAP integration

### 6.2.1 (2022-10-11)
* (klein0r) Warn user if a device is not protected via restricted login
* (klein0r) Added duration for generation 2 devices in cover mode
* (klein0r) Added temperature data of Shelly Motion 2
* (klein0r) Added knowledge base urls for all devices

### 6.2.0 (2022-09-15)
* (klein0r) Added Shelly Motion 2
* (klein0r) Added Shelly Plus H&T
* (klein0r) Added Shelly Pro 3
* (klein0r) Fixed channel name and long push duration handling for Shelly i3
* (klein0r) Fixed (automatic) firmware update process for generation 2 devices
* (klein0r) Get correct IP address in Docker environment
* (klein0r) Added temperature offset configuration for Shelly UNI
* (klein0r) Updated online indicator handling
* (klein0r) Fixed temperature of Shelly Door / Window 2
* (klein0r) Added icons for some states
* (klein0r) Translated (some) object names

## License

The MIT License (MIT)

Copyright (c) 2018-2022 Thorsten Stueben <thorsten@stueben.de>,
                        Apollon77 <iobroker@fischer-ka.de> and
                        Matthias Kleine <info@haus-automatisierung.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
