# intercom2wifi
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

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

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://haoc.wang"><img src="https://avatars.githubusercontent.com/u/16266909?v=4?s=100" width="100px;" alt=""/><br /><sub><b>叶踏池</b></sub></a><br /><a href="https://github.com/tinymins/intercom2wifi.esp/commits?author=whc2001" title="Code">💻</a></td>
    <td align="center"><a href="https://zhaiyiming.com/"><img src="https://avatars.githubusercontent.com/u/1808990?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Emil Zhai</b></sub></a><br /><a href="https://github.com/tinymins/intercom2wifi.esp/commits?author=tinymins" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!