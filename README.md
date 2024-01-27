
## Customized firmware configuration for Ender3 Pro with SKR mini E3 V3.0 and Sherpa mini extruder


This config is for [Marlin](https://github.com/MarlinFirmware/Marlin) firmware bugfix-2.1.x. Version: 02010300

## Usage

1. Clone this repository into Marlin directory
2. Install [platformio](https://platformio.org/) plugin for VSCode
3. Copy `Configuration.h`, `Configuration_adv.h`, `_Bootscreen.h` and `_Statusscreen.h` into `Marlin` directory
4. Change platformio.ini default_envs to STM32G0B1RE_btt for SKR mini E3 V3.0
5. Build marlin version with the platformio plugin
6. Copy `firmware.bin` from .pio folder to SD card and flash it

## Hardware

- Ender 3 Pro  
- BIGTREETECH-SKR-mini-E3 V3.0 - https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3  
- Sherpa mini from Annex Engineering - https://github.com/Annex-Engineering/Sherpa_Mini-Extruder  
- Mk8 hotend with Hydra setup 
- BLTouch v3.0
