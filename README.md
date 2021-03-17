# ESP32 CanAirIO Loader

This project will able to upload the latest version of [CanAir.IO firmware](https://github.com/kike-canaries/canairio_firmware#canairio-firmware)
automatically via a simple Arduino sketch.

## General steps

You can run it from your **Arduino IDE** or from your **Android** phone
using [ArduinoDroid](https://play.google.com/store/apps/details?id=name.antonsmirnov.android.arduinodroid2&hl=en&gl=US)
app (**recommended**) with a simple **OTG** cable connected to your board. (see the video below)

- [ ] Please first install Arduino Json Library from Arduino Library Manager
- [ ] Configure your board: ESP32 Dev Module or similar board
- [ ] Select partion schema to **minimal** with OTA (1.9Mb to app 190kbs to SPIFFS, [see documentation](https://codeblog.dotsandbrackets.com/arduino-cli-partition-scheme/) for details)
- [ ] Configure your WiFi credentials below
- [ ] Build and upload, wait for, the last version of CanAirIO will be installed
- [ ] (optional) see the progress on Serial console or monitor.

## Video step by step 

[![Youtube CanAirIO basic loader guide](http://img.youtube.com/vi/FjfGdnTk-rc/0.jpg)](http://www.youtube.com/watch?v=FjfGdnTk-rc "Youtube CanAirIO basic loader guide")

#  Troubleshooting

We have a [Telegram group](https://t.me/canairio) for support, maybe the community can help you.
