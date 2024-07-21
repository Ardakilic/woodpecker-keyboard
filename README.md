# Woodpecker Keyboard
5 row ortholinear keyboard, based on [Lumberelite](https://github.com/tjeffree/lumberelite) and [Lumberjack](https://github.com/peej/lumberjack-keyboard).

The fork is done in a way that a wireless controller such as [nice!nano](https://nicekeyboards.com/nice-nano/) or [alternatives](https://github.com/joric/nrfmicro/wiki/Alternatives) could be utilized, and OLED module, Pimoroni Trackball or Cirque Trackpad could be applied over to the central area of the keyboard.

![Preview0](https://i.imgur.com/R7WR0xK.jpeg "preview 0")

![Preview1](https://i.imgur.com/HB0lnEA.jpeg "preview 1")

All work on the PCB is done by [Özkan Çelik](https://github.com/ozkan), he made this due to my request.

Shields are done by Kazim Kaba and [Ender Piyale](https://github.com/enderpiyale/).

[The plates of Lumberjack Keyboard](https://github.com/peej/lumberjack-keyboard/tree/master/plates) work nicely. I'm currently using the `lumberjack-split` flavour on my board, which you can also find [here](./plates-shields/plates/lumberjack-split.dxf).

Additionally, the board is compatible with 60% cases. My case is a wooden one from a Chinese e-commerce website. I raised the micro controller with sockets to not to drill a hole into my case.

## Firmware

* QMK: Keyboard definition and userspace
    * https://github.com/Ardakilic/qmk_firmware/tree/master/keyboards/woodpecker
    * https://github.com/Ardakilic/qmk_userspace/tree/main/keyboards/woodpecker
* ZMK: https://github.com/ardakilic/zmk-config-woodpecker
