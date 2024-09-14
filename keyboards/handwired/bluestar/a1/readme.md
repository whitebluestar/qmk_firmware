# Bluestar A1

![Bluestar A1](https://imgur.com/a/HGsMmfk)


A compact ortholinear board fully designed by myself, featuring a 3d printed plate and 3d printed case. 

* Keyboard Maintainer: [Whitebluestar](https://github.com/whitebluestar)
* Hardware Supported: Handwired, using Raspberry Pi Pico W

Make example for this keyboard (after setting up your build environment):

    make handwired/bluestar/a1:default

Flashing example for this keyboard:

    make handwired/bluestar/a1:default:flash

See the [build environment setup](getting_started_build_tools) and the [make instructions](getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
