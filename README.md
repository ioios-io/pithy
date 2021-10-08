

# The Pithy Range @ [ioios.io](https://ioios.io/products/pithy)

![GitHub](https://img.shields.io/github/license/ioios-io/pithy) ![GitHub repo size](https://img.shields.io/github/repo-size/ioios-io/pithy) [![GitHub Last Commit](https://img.shields.io/github/last-commit/ioios-io/pithy.svg)](https://img.shields.io/github/last-commit/ioios-io/pithy.svg) ![GitHub issues](https://img.shields.io/github/issues-raw/ioios-io/pithy) ![GitHub pull requests](https://img.shields.io/github/issues-pr/ioios-io/pithy) ![GitHub contributors](https://img.shields.io/github/contributors/ioios-io/pithy)
---
## The quickest way to add extra control to your Smart Home
[<img align="right" src="./assets/ioios-300W-inverted.png?raw=true">](https://ioios.io) The Pithy range was conceived to fill the gap in the smart home arena so as to provide simple and intuitive phyiscal controls for adjusting volume, dimming lights, changing heating settings or whatever you chose!

The Open-Source devices are centered around a Wemos D1 Mini and they all feature a rotary encoder, a side switch and a temperature/huimdity sensor. Additionally, the Pixel model has a 16 LED NeoPixel ring for a display whilst the Screen model has... you guessed it, a screen.

<img src="./assets/PithyRangeLabelled.png?raw=true">

## Pins
When writing esphome configuration for the Pithy range you will need to use the following pins for the latest board versions.

| Function         | D1 Mini PIN |
|------------------|-------------|
| I2C Clock        | D3          |
| I2C Data         | D4          |
| Side Button      | TX          |
| PIR Sensor 1*    | D1          |
| PIR Sensor 2*    | D2          |
| Rotary Encoder A | D5          |
| Rotary Encoder B | D6          |
| Rotary Switch    | D7          |
| NeoPixels*       | RX          |
| DHT22 Temp*      | D0          |

(* Denotes items that may not be installed on all versions of a given model)

## The Files
In this repo you will find both the PCB files and the cases. In both sections the files are provided in multiple formats and include the official designs and also community contributions.
##### The Design Process
The PCBs were designed in Autodesk Eagle (using a custom made component library with 100% 3D renders). They were then imported/linked to Autodesk Fusion 360 where the cases were designed to perfectly fit and compliemnt the PCBs.
<img src="./assets/PithyMounts.png?raw=true">

## Contributions
It is Open-Source for a reason! If you would like to contribute your modifications or creations to the project, please follow these steps:
1. Fork this repo
2. Create a new, descriptively-named directory within the appropriate 'community' directory
3. Create a README.md file to briefly explain your ideas and if required, instructions for use/assembly
4. Don't forget to credit yourself and anyone else involved!
4. Create a pull request

<img src="./assets/PithyRangeLogo.png?raw=true">
___

```
John Lumley
15th March 2021
```
