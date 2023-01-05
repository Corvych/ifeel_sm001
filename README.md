# External Converter For iFEEL IFS-SM001 For Zigbee2MQTT
## Supported Devices
| Model | Photo | Is Supported |
|-----------------|:-------------------------------:|:---------:|
|iFEEL+ IFS-SM001|<img src="https://cdn1.ozone.ru/s3/multimedia-t/wc1000/6267204053.jpg" width="150">|✅|
## What works
| Function | Is working |
|-------------------|:------:|
|Motion Detection|✅|
|Low Battery alert|✅|
## How to make it work
1. Download [ifeelplus_sm_001.js](https://github.com/Corvych/ifeel_sm001/blob/stable/ifeelplus_sm_001.js) external converter
2. Bind device to your Zigbee network
3. Add this into your Zigbee2MQTT `configuration.yaml` file
```
external_converters:
  - ifeelplus_sm_001.js
```
4. Restart Zigbee2MQTT extension and you're ready to go!
