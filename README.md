# Chocofi Temper ZMK Config

ZMK config for the [Chocofi Temper](https://github.com/raeedcho/chocofi-temper). 
In addition to the original ZMK features in [raeedcho](https://github.com/raeedcho/temper-zmk-config) and [Nabizzle](https://github.com/Nabizzle/temper-zmk-config-view) repos, I have added and tested the following:

* Nice view compatibility
* Custom Nice View Adapter, just in case you need to configure a bodge wire for the fifth pin
* Nickcoutsos' [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) compatibility with custom keymap layout 
* Dongle & Dongleless configuration generation. For more information about Dongle configuration, check [SliceMK Dongle doc](https://docs.slicemk.com/firmware/zmk/wireless/dongle/)

# Attention
If you will to use the dongle using my current configuration in build.yaml, keep in mind that I have the bodge wire adapter configured for the dongle since my Nicenano used for the dongle has the cs pin changed.

# TODO
* Add Seeed Studio XIAO nRF52840 compatibility as a dongle
* Integrate an adapter for niceviews with Seeed Studio XIAO nRF52840.
* Explore different display options

# Current Keymap
![Temper Keymap](keymap_img/temper.svg)
