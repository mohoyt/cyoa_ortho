# CYOA Ortho

![CYOA Ortho](https://i.imgur.com/i41MWu9.jpeg)

CYOA (Choose your own adventure) Ortho is an easy to build Ortho keyboard that you can snap to make the perfect size for you.

* Keyboard Maintainer: [mohoyt](https://github.com/mohoyt)
* Hardware Supported: Pro Micro, Elite-C, Puchi-C, Nice!Nano and more...
* Hardware Availability: [sthlm kb](https://sthlmkb.com)

Make example for this keyboard for a Pro Micro controller (after setting up your build environment):

    make sthlmkb/cyoa_ortho:vial-4x12

Make example for this keyboard for a RP2040 based controller using the built in QMK conversion (after setting up your build environment):

    make sthlmkb/cyoa_ortho:vial-4x12 CONVERT_TO=HELIOS

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

You will need to use the Vial fork of QMK and a vial keymap if you want to have Vial compatibility. 