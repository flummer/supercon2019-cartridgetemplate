# Unofficial KiCad template for a 2019 Hackaday Superconference Badge Cartridge

![Cartridge template render](https://raw.githubusercontent.com/flummer/supercon2019-cartridgetemplate/master/IMAGES/front_back_render.png "Cartridge template render")

This template can be used as a starting point to make a cartridge for the Supercon badge, that will mate with the 40 pin expansion connector on the back of the badge.

| WARNING: This design is unofficial, and has NOT been tested |
| --- |

It's using an angled 2x20 pin male header, a w25q128 SPI flash and a 100nF cap. The schematic has the pins named using global nets, so it's easy to simply add in your own stuff.

## Version 1.2 update

This updated version fixes an error in the pin connections on the cartridge connector (the two columns was flipped for some signals) and adds a copper pour (connected to GND) on the bottom layer too.

## Special note about the original version

If you want to use a PCB based on the original version with incorrect connections, it is possible to make a hardware hack on the 20x2 angeled header, where you move the pins around and bend some of them a bit, very precisely.

## License

The contents of this repository is released under the following licence:

 * the "Creative Commons Attribution-ShareAlike 4.0 International License"
   (CC BY-SA 4.0) full text of this license is included in the LICENSE file
   and a copy can also be found at
   http://creativecommons.org/licenses/by-sa/4.0/
