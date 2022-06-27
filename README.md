# Fork Information

* This fork was created from scratch using Rory Hayes (rorosaurus)'s design as reference. 
* The BOM / part list was altered to use parts that are easy to source on digikey.

Nothing for sale here.  If you would like to purchase a board pre-made, visit [rorosaurus's github project](https://github.com/rorosaurus/gba-sp-usb-c) for links.

## This is Game Boy Advance SP mod to add a handsolderable USB-C port.

The CC resistors make this mod compatible with both common USB A chargers and modern USB C PD / Quick Charge chargers.

# How to Make:

You should be comfortable with a solder iron and have access to a 3D printer.  Hot air re-work station is optional, but recommended.

* Order PCB from OSHPark
   - Upload the .brd file to OshPark.
   - Select 2oz copper, 0.8mm thickness
* Order parts from Digikey
   - USB-C port: https://www.digikey.com/en/products/detail/cui-devices/UJC-VP-3-SMT-TR/14310511
   - 5.1K resistors: https://www.digikey.com/en/products/detail/yageo/RC0402FR-135K1L/14286364
* 3D Print the spacer from [Thingiverse](https://www.thingiverse.com/thing:4123563).
* Cleanup: Use sandpaper or dremel to remove burrs from pcb edges.
* Solder smd parts to pcb.
* See [INSTALLATION](INSTALLATION.md) for the next steps.

# Compatibility

This design is ok for the AGS-001 (2003 Front Light) and AGS-101 (2005 Back Light).

# Disclaimer

This project is MIT licensed and comes with no warranty.  Modify your console at your own risk!

# References

* https://github.com/rorosaurus/gba-sp-usb-c/
* https://www.reddit.com/r/GameBoy/wiki/mods
* https://discord.gg/gameboy
* https://docs.oshpark.com/design-tools/eagle/cutouts-and-slots/
