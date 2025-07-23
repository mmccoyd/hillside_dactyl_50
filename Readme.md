# Hillside Dactyl 50

![D50 above](https://github.com/mmccoyd/hillside_dactyl_50/wiki/image/d50_both_above.png)

The Hillside Dactyl 50 is a small contoured-keywell ergonomic keyboard
    with three choc-spaced rows of six per side.
This repository has the [body files](./stl/),
    and describes parts and assembly in the 
    [wiki](https://github.com/mmccoyd/hillside_dactyl_50/wiki).

Two other repositories have the PCB files

-   [Amoeba Choc14](https://github.com/mmccoyd/hillside_amoeba_choc14)
    to wire the switches and diodes to create the key matrix.
-   [Hillside Dactyl Shield](https://github.com/mmccoyd/hillside_dactyl_shield)
    to connect the MCU, keys, display, and LEDs.

Though still in development, it has been reliable and comfortable.
See the [Chgange log](./ChangeLog.md) for known issues, but
    I hope you find the board useful.


## Features

-   Three main rows of six, a lower row of two, five thumb keys, and 50 keys
    total.
-   A keywell with 15° column curve, and 15° tent built in.
-   A [Dactyl](https://github.com/adereth/dactyl-keyboard) style thumb cluster
    with a pressing-down motion not a
    gripping one.
-   Choc v1 18 x 17 mm spacing, often nicer for medium or smaller hands.
-   Wireless focused, yet with a wired split USB-C with ESD protection.
-   An external switches header for foot pedals, but case drilling would be
    needed.
-   Default key maps for
    [ZMK](https://github.com/mmccoyd/zmk-hillsideD50) as an external module and
    [QMK](https://github.com/mmccoyd/qmk_firmware/tree/hillside_d50/keyboards/hillside/d50)
    as a branch on a fork.


### Non-Features

-   Switch insertion or replacement externally.
    The case needs to be open to press the amoebas up onto the switches.
    The switches snap into the case, but the amoeba don't.
    The amoeba are held in place by a tight grip on the switch's plastic posts.
    Switches popping out is rare when dropped, but is possible.
    Iterating on this is on my list of longer term items.
-   Per key RGB.
    The amoebas don't have much space.
    It would be cool and might be possible, but is low on my priority list.


## Future

For non-breaking changes:
    the display corner could use more smoothing,
    front magnets spots would allow a palm rest,
    and, as a larger change, a CNC steel bottom plate would give a wider
    base for tenting adjustments and could lower the height a few mm.

The development branch folder
    [stl_dev/](https://github.com/mmccoyd/hillside_dactyl_50/tree/dev/stl_dev)
    may have *untested* files with some of these changes.

Eventually there will be a breaking change to eliminate the external recesses
    for the USB plug overmolding.
A matching new shield design will be needed that extends the USB into the
    inner walls.
But this will be a while.

I don't foresee changes to the basic key configuration,
    such as a five column version.
But I'm working to release STEP and source files for the amoeba socket
    to help others who want to create small choc dactyls.

## License

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](
https://creativecommons.org/licenses/by-nc-sa/4.0/) license.


## See also

This Dactyl evolved from my ergonomic but flat
    [Hillside keyboards](https://github.com/mmccoyd/hillside),
    which offer easier starting points for those new to small choc-spaced
    ergonomic boards.

The general reasons for
    [split contoured-keywells](https://www.ergocanada.com/detailed_specification_pages/kinesis_corporation_advantage360_pro_contoured_keyboard.html#benefits)
    and [small keyboards](https://40s.wiki/en/why) may explain why
    this board can be nice to use.

This Dactyl fits me well and I think likely others with medium hands.
But a roughly good fit is important in a Dactyl, so the below are valuable
    alternatives.

Some prebuild Dactyls include
    the larger [Kinesis Advantage 360](https://kinesis-ergo.com/shop/adv360pro/)
    and [MoErgo Glove 80](https://www.moergo.com/);
    while [Bastard Keyboards](https://bastardkb.com/) has prebuilt
    medium to small
    [Dactyl Manuforms](https://github.com/abstracthat/dactyl-manuform).
Some argue that the original
    [Dactyl](https://github.com/adereth/dactyl-keyboard)
    is gentler on the thumb joint and wrist than the
    [Dactyl Manuform](https://github.com/abstracthat/dactyl-manuform) is.
The Glove 80 is the only of these prebuilt with choc spaced switches, 
    which are nice for medium or smaller hands.

[Cosmos](https://ryanis.cool/cosmos/) is a great generator for custom Dactyl
    Manuform bodies that can do choc vertical but gives thickness warnings for
    choc horizontal spacing.
It offers a prebuilt option and allows broad changes to board parameters.
Including changing the position and angle of the entire thumb
    cluster, with the select cluster and edit cluster controls,
    to make it more original Dactyl like or not.

Two choc v1 boards with contoured body columns,
    though no home-row height variation, are the
    [juriform36](https://github.com/jurica/juriform36) and the
    [rkbrd3](https://github.com/prepor/rkbrd/tree/main/3).
YellowAfterlife's
    [ergonomic keyboard list](https://yal-tools.github.io/ergo-keyboards/)
    shows a few more contoured keywell options and many flat options.
