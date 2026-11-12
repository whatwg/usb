This repository hosts the [WebUSB Standard](https://usb.spec.whatwg.org/). It is one of [many web standards](https://spec.whatwg.org/) developed by the [WHATWG community](https://whatwg.org/).

## Code of conduct

We are committed to providing a friendly, safe, and welcoming environment for all. Please read and respect the [Code of Conduct](https://whatwg.org/code-of-conduct).

## Contribution opportunities

Folks notice minor and larger issues with the WebUSB Standard all the time and we'd love your help fixing those. Pull requests for typographical and grammar errors are also most welcome.

Issues labeled ["good first issue"](https://github.com/whatwg/usb/labels/good%20first%20issue) are a good place to get a taste for editing the WebUSB Standard. Note that we don't assign issues and there's no reason to ask for availability either, just provide a pull request.

If you are thinking of suggesting a new feature, read through the [FAQ](https://whatwg.org/faq) and [Working Mode](https://whatwg.org/working-mode) documents to get yourself familiarized with the process.

We'd be happy to help you with all of this [on Chat](https://whatwg.org/chat).

## Pull requests

In short, change `index.bs` and submit your patch, with a [good commit message](https://github.com/whatwg/meta/blob/main/COMMITTING.md).

Please add your name to the Acknowledgments section in your first pull request, even for trivial fixes. The names are sorted lexicographically.

To ensure your patch meets all the necessary requirements, please also see the [Contributor Guidelines](https://github.com/whatwg/meta/blob/main/CONTRIBUTING.md). Editors of the WebUSB Standard are expected to follow the [Maintainer Guidelines](https://github.com/whatwg/meta/blob/main/MAINTAINERS.md).

## Tests

Tests are an essential part of the standardization process and will need to be created or adjusted as changes to the standard are made. Tests for the WebUSB Standard can be found in the `usb/` directory of [`web-platform-tests/wpt`](https://github.com/web-platform-tests/wpt).

A dashboard showing the tests running against browser engines can be seen at [wpt.fyi/results/usb](https://wpt.fyi/results/usb).

## Building "locally"

For quick local iteration, run `make`; this will use a web service to build the standard, so that you don't have to install anything. See more in the [Contributor Guidelines](https://github.com/whatwg/meta/blob/main/CONTRIBUTING.md#building).

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
