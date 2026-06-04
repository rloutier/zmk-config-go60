# zmk-config-go60

This repo serves as a "companion-repo" to [aekeynox], ZMK implementation of [Selenium] keymap, to declare the "hardware" config of Go60 MoErgo keyboard.  

The content of this repo is essentially a small extract of the official [MoErgo fork of ZMK][moergo-zmk]
for the specific `zephir-4-1` branch, structured as a "ZMK user config".

> [!IMPORTANT]
> - This is not a standalone repo to build firmwares from; for this purpose, you might want to have a look at the [official MoErgo Go60 configuration repo][moergo-conf], or [aekeynox] itself
> - Using this repo config along-side aekeynox, some caracteristics of Go60 keyboard will be lost :
>   - RGB backlight
>   - MagicLayer
>   - Trackpads configurations
>   - (...)

But you will enjoy the marvellous Selenium keymap, so... it's worth it, isn't it :blush:

[aekeynox]:     https://github.com/OneDeadKey/zmk-config-aekeynox
[Selenium]:     https://github.com/OneDeadKey/selenium
[moergo-zmk]:   https://github.com/moergo-sc/zmk
[moergo-conf]:  https://github.com/moergo-keyboards/go60-zmk-config
