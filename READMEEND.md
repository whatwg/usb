## Explainers

* [WebUSB in Extension Service Workers](./extension-service-worker-explainer.md)
* [Unrestricted WebUSB](./unrestricted-usb-explainer.md)

## Implementation Status

* Available in [Chromium](https://source.chromium.org/chromium/chromium/src/+/main:third_party/blink/renderer/modules/webusb/)-based browsers for Android, ChromeOS, Linux, macOS, and Windows (released in Chrome 61). See the [Chromium Issue Tracker](https://bugs.chromium.org/p/chromium/issues/list?q=component%3ABlink>USB) for implementation issues.
* The Node.js [usb](https://github.com/node-usb/node-usb) package exports a `WebUSB` object.

## Demos

* [Arduino Integration](https://github.com/webusb/arduino/)
* [WebLight](https://github.com/sowbug/weblight)
* [USB Device Firmware Upgrade (DFU)](https://github.com/devanlai/webdfu)
* [WebADB](https://github.com/webadb/webadb.js)
* [Zephyr JS IDE](https://github.com/01org/zephyrjs-ide), [hosted IDE](https://01org.github.io/zephyrjs-ide/)
* [DSLR camera control](https://web-gphoto2.rreverser.com/)

## Articles

* [Access USB Devices on the Web](https://developers.google.com/web/updates/2016/03/access-usb-devices-on-the-web)
* [The WebUSB Security Model](https://medium.com/dev-channel/the-webusb-security-model-f48ee04de0ab) (outdated)
* [WebUSB and JavaScript Robotics](http://iceddev.com/blog/webusb-and-javascript-robotics/) (PageNodes)
* [Program a smart device directly, no install needed](https://medium.com/@kennethrohde/program-a-smart-device-directly-no-install-needed-cd8b29320d76) (Arduino running Zephyr)
* [Web enabling legacy devices](https://medium.com/@larsgk/web-enabling-legacy-devices-dc3ecb9400ed) Discusses USB CDC (USB Serial devices)
