# ESP32 CanAirIO Loader

This project will able to upload the latest version of [CanAir.IO firmware](https://github.com/kike-canaries/canairio_firmware#canairio-firmware)
automatically via a simple Arduino sketch.

## General steps

You can run it from your **Arduino IDE** or from your **Android** phone
using [ArduinoDroid](https://play.google.com/store/apps/details?id=name.antonsmirnov.android.arduinodroid2&hl=en&gl=US)
app (**recommended**) with a simple **OTG** cable connected to your board. (see the video below)

- [ ] Install the Arduino Json Library from Arduino Library Manager (ArduinoDroid or Arduino IDE)
- [ ] Configure your board: ESP32 Dev Module or similar board with
- [ ] Select partion schema to **minimal** ([OTA with 1.9Mb to app 190kbs to SPIFFS](https://codeblog.dotsandbrackets.com/arduino-cli-partition-scheme/))
- [ ] Configure your WiFi credentials in the sketch
- [ ] Build and upload, wait for, the last version of CanAirIO will be installed
- [ ] (optional) see the progress on Serial console or monitor.
- [ ] Android app guide for using the device like a [mobile or fixed air quality station](https://github.com/kike-canaries/canairio_firmware/blob/master/README.md#android-canairio-app)

## Video step by step 

[![Youtube CanAirIO basic loader guide](http://img.youtube.com/vi/FjfGdnTk-rc/0.jpg)](http://www.youtube.com/watch?v=FjfGdnTk-rc "Youtube CanAirIO basic loader guide")

---

#  Troubleshooting

- In Arduino IDE, some users comments that you need comment the first line `#include <Arduino.h>`
- We have a [Telegram group](https://t.me/canairio) for support, maybe the community can help you.
