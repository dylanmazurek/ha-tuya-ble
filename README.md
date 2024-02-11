# Home Assistant support for Tuya BLE devices

## Overview

This integration supports Tuya devices connected via BLE.

_Inspired by code of [@redphx](https://github.com/redphx/poc-tuya-ble-fingerbot)_

## Installation

Place the `custom_components` folder in your configuration directory (or add its contents to an existing `custom_components` folder). Alternatively install via [HACS](https://hacs.xyz/).

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=dylanmazurek&repository=ha-tuya-ble&category=integration)

## Usage

After adding to Home Assistant integration should discover all supported Bluetooth devices, or you can add discoverable devices manually.

The integration works locally, but connection to Tuya BLE device requires device ID and encryption key from Tuya IOT cloud. It could be obtained using the same credentials as in official Tuya integration. To obtain the credentials, please refer to official Tuya integration [documentation](https://www.home-assistant.io/integrations/tuya/)

## Supported devices list

The following devices are supported:

| Category Name | Category ID | Device Name | Product ID |
| --- | --- | --- | --- |
| **Fingerbots** | `szjqr` |||
||| Fingerbot ||
||||`ltak7e1p`|
||||`yrnk7mnn`|
||||`nvr2rocq`|
||||`bnt7wajf`|
||||`rvdceqjh`|
||||`5xhbk964`|
||| Adaprox Fingerbot |
|||| `y6kttvd6` |
||| Fingerbot Plus |
|||| `blliqpsj` |
||| CubeTouch 1s |
|||| `3yqdo5yt` |
||| CubeTouch II |
|||| `xhf790if` |
| **Temp/Humidity Sensors** | `wsdcg` |||
||| Temp/humidity sensor |
|||| `ojzlzzsw` |
| **CO2 Sensors** | `co2bj` |||
||| CO2 sensor |
|||| `59s19z5m` |
| **Smart Locks** | `ms` |||
||| Smart Lock |
|||| `ludzroix` |
|||| `isk2p555` |
| **Climate** | `wk` |||
||| Thermostatic Radiator Valve |
|||| `drlajpqc` |
|||| `nhj2j7su` |
| **Irrigation** | `ggq` |||
||| Irrigation computer |
|||| `6pahkcau` |
|||| `hfgdqhho` |
||| Water valve controller |
|||| `nxquc5lb` |
| **Other** | |||
||| Smart water bottle |
|||| `cdlandip` |