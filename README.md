# ESPHome Packages

A collection of simple ESPHome packages.

## iFan04-L

```yaml
api:
  encryption:
    key: !secret encryption_key

ota:
  password: !secret ota_password

wifi:
  ssid: !secret wifi_ssid
  password: !secret wifi_password

esphome:
  name: bedroom-fan
  friendly_name: "Bedroom Fan"

packages:
    ifan04: github://gagebenne/esphome/packages/ifan04.yaml # !include ifan04.yaml (locally)
```
