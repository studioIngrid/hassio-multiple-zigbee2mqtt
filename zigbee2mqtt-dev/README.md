# Multiple Zigbee2MQTT

Home Assistant *does* allow you to run multiple Zigbee2MQTT add-ons, but setting this up can be a bit hacky — and all instances end up with the same name, which gets confusing fast.

This add-on exists for one simple reason: to make that experience smoother.

It acts as a small configuration wrapper around `hassio-zigbee2mqtt/zigbee2mqtt` and will **only change the add-on name** .
No behavior is changed.

🔗 For the Zigbee2MQTT project itself, visit the developer’s GitHub:
[https://github.com/Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt)

🔗 For the original Home Assistant add-on configuration, see:
[https://github.com/zigbee2mqtt/hassio-zigbee2mqtt](https://github.com/zigbee2mqtt/hassio-zigbee2mqtt)
