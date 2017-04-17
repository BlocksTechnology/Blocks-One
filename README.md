# Blocks one
In this repository you will find the firmware source code, BOM, STLs of the printed parts and frames for the [Blocks one 3D printer](http://blockstec.com/one.html)


# New Marlin firmware v1.1
The new version is based on v1.0 with some new features added:
 - New load/unload filament routine
 - Option to clean the nozzle before bed level
 - Thermal runaway safety feature
 - Filament runout (needs printing new extruder and adding a microswitch to work)

Updating the firmware:
 - Download and install [Cura 15.02.1](http://software.ultimaker.com/old/Cura_15.02.1.exe)
 - Download the [HEX file](https://github.com/BlocksTechnology/Blocks-One/blob/master/Firmware_1.1/Blocks_one_1.1.hex)
 - Connect your printer to USB port
 - Open Cura and select menu "Machine" -> "Install custom firmware"
 - Select the downloaded HEX file.
 - Wait for the upload to finish and press "OK"

In case the update does not start, please verify the "Serial port" and "Baudrate" (115200) settings in the menu "Machine" -> "Machine settings".


# License
Blocks one is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)


# Firmware
The firmware was based on Marlin from https://github.com/bq/Marlin

