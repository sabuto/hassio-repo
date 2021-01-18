# All Changes will be posted here

## 0.5.6 - 18/01/2021
* Enable prometheus exporter output for telegraf (#32) @fliphess
* Update telegraf to 1.17.0 (#31) @fliphess
* Version skipped because of ocnfig mess up

## 0.5.4 - 23/02/2020
- forgot to update ver in config

## 0.5.3 - 23/02/2020
- chore: update custom config to copy instead of moving
-[See full Changelog](https://github.com/Sabuto/hassio-telegraf/releases/tag/0.5.3)

## 0.5.2 - 20/02/2020
- feature: added thhe ability to use a custom config.
-[See full Changelog](https://github.com/Sabuto/hassio-telegraf/releases/tag/0.5.2)

## 0.5.1 - 11/02/2020
- feature: add support for scrapping thermal subsystem
- enhancement: install smartmontools from backports repository
-[See full Changelog](https://github.com/Sabuto/hassio-telegraf/releases/tag/0.5.1)

## 0.5.0 - 05/02/2020
- chore: Updated the config
- chore: move to GitHub workflow (#19) @Sabuto
- feature: added support for influxDBv2 (#18) @Sabuto
- [See full Changelog](https://github.com/Sabuto/hassio-telegraf/releases/tag/0.5.0)

## 0.4.3 - 20/11/2019
- Updated bug with ipmi sensors
- made username, password and retention_policy optional as requested
- [See full changelog](https://github.com/Sabuto/hassio-telegraf/releases/tag/0.4.3)

## 0.4.2 - 13/11/2019
- Added ipmi to the config as requested in the forums
- [See full changelog](https://github.com/Sabuto/hassio-telegraf/releases/tag/0.4.2)

## 0.4.1 - 08/11/2019
- Added more config variables
- [See full changelog](https://github.com/Sabuto/hassio-telegraf/releases/tag/0.4.1)

## 0.4.0 - 06/11/2019
-Changed Dockerfile to ubuntu to fix not installing on different Arch's

## 0.3.1 - 04/11/2019
- Replaces hdd_temp for smart monitoring

## 0.3.0 - 03/11/2019
- Bumped telegraf Version to 1.12.4 (why it is 0.3.0 release)
- added support for hdd_temp
- changed formatting of config.json (also why 0.3.0)

## 0.2.20 - 02/11/2019
- Updated base images
- Fixed breaks

## 0.2.18 - 29/10/2019
- Added defualt sensors measurements (temperatures)

## 0.2.17 - 29/10/2019
- Added todo
- Added changelog
- Added request template
- Fixed type (#1)

## 0.2.16 - 28/10/2019
- Initial release after local dev
