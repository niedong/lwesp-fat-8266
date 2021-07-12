# LwESP For Ai-thinker ESP8266

[lwesp-fat-8266](https://github.com/niedong/lwesp-fat-8266), which stands for `LwESP For Ai-thinker ESP8266`, is a variation of [lwesp](https://github.com/MaJerle/lwesp). The original [lwesp](https://github.com/MaJerle/lwesp) library mostly targets on [Espressif](https://github.com/espressif) ESP8266 and ESP32 devices, which use a slightly different and larger range of AT commands.

This repository targets specifically at [Ai-thinker](https://github.com/Ai-Thinker-Open) ESP8266, and should work well with other device that use Ai-thinker ESP8266 as a solution, such as ESP-01S, ESP-07, etc. You can find more information about your device on [Ai-thinker website](https://docs.ai-thinker.com/en/esp8266).

Follow original [documentation](https://docs.majerle.eu/projects/lwesp/) for information on implementation and details.

## Usage & Examples

The usage of [lwesp-fat-8266](https://github.com/niedong/lwesp-fat-8266) is exacly the same as [lwesp](https://github.com/MaJerle/lwesp). There is also an important repository [stm32f769xx](https://github.com/niedong/stm32f769xx), which demonstrates  configuration and usage for [lwesp-fat-8266](https://github.com/niedong/lwesp-fat-8266) based on stm32f769, [Ai-thinker](https://github.com/Ai-Thinker-Open) ESP8266 and FreeRTOS. You can even find more examples and resources in [lwesp](https://github.com/MaJerle/lwesp) repository.

## Fix & Changes

- Fix `AT+CIPSTART` for [Ai-thinker](https://github.com/Ai-Thinker-Open) ESP8266 where `+LINK_CONN` is not supported.
- Remove macro, options & modules which are not supported by [Ai-thinker](https://github.com/Ai-Thinker-Open) ESP8266.
- Minor optimization, improvement and more.

All modification and changes on original source code are clearly marked. You can find them on top of corresponding files.

## Contribute

Contributions are always welcome. Please follow [C style & coding rules](https://github.com/MaJerle/c-code-style) used by original library.

## License

This software is double-licensed under MIT license, with copyright by [MaJerle](https://github.com/MaJerle) (see LICENSE), and copyright by [niedong](https://github.com/niedong) (see LICENSE.niedong).
