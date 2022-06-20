# intercom2wifi

Intercom to WiFi for JB-2201-F03 over ESP8266 on Home Assistant.

JB-2201-F03 门禁话机，通过 D1-Mini 开发板 (ESP8266) 连接到 Home Assistant 实现开门与铃声推送。

## configure

Copy `secrets.sample.yaml` to `secrets.yaml`, and update secrets data.

## deploy

```bat
esphome run --device DEVICE_NAME intercom.yaml
```

`DEVICE_NAME` can be `COM Port` or `IP Address`, for example:

```bat
esphome run --device COM5 intercom.yaml
esphome run --device 192.168.0.201 intercom.yaml
```
