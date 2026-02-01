# 🔀 Multiple Zigbee2MQTT

Home Assistant *does* allow you to run multiple Zigbee2MQTT add-ons — but setting this up can be a bit hacky 🤕
On top of that, all instances end up with the same name, which gets confusing *fast*.

This add-on exists for one simple reason: **to make that experience smoother** ✨

> [!TIP] 💡
> Got questions or feedback?
> Find me on the Home Assistant Community: [studioIngrid](https://community.home-assistant.io/u/studioingrid)
> Or reply in the discussion [tread](https://community.home-assistant.io/t/add-connection-state-online-offline-to-every-z2m-device-or-other-mqtt-device)

This repository acts as a **small configuration wrapper** around
`hassio-zigbee2mqtt/zigbee2mqtt`.

It **only changes the add-on name**. 🚫 No behavior is modified. ✅ Zigbee2MQTT works exactly the same.

🔗 For the Zigbee2MQTT project itself, visit the developer’s GitHub:
[https://github.com/Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt)

🔗 For the original Home Assistant add-on configuration, see:
[https://github.com/zigbee2mqtt/hassio-zigbee2mqtt](https://github.com/zigbee2mqtt/hassio-zigbee2mqtt)

## ✨ Features

* 🔄 Follows official Zigbee2MQTT releases
* 🏷️ Supports multiple clearly named instances

  * Zigbee2MQTT 1
  * Zigbee2MQTT 2
  * Zigbee2MQTT 3
  * Zigbee2MQTT 4
  * Zigbee2MQTT 5
  * Zigbee2MQTT Hub
  * Zigbee2MQTT Dev
