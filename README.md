# CherryB Works Freyr TKL files
![image](https://user-images.githubusercontent.com/64993772/230959743-d857d0b2-b724-40c8-876d-46bd66a202b4.png)

CherryB Works seems to have gone under, so in order to make sure the Freyr TKL can live I gathered all files related to it here.

## Plate files

The community has done multiple plate files including half and full plates in both ISO and ANSI formats. The "Plates" folder has both of them. 

## PCB

There are no released PCB files, since the Freyr uses the proprietary CB87 pcb designed by CherryB Works.

The Freyr TKL is fully H87C compatible meaning you can either get a Hiney PCB for it or get some other compatible PCB for example this wonderful Open Source project: https://github.com/dededecline/SST80

## Firmware

The Firmware folder has the official PCB's VIA compatible firmware. 

Here are some instructions for flashing: 

For those who want to use Feyr with traditional QMK Configurator keymapping, now you can do it directly from QMK Configurator website. 
- Go to https://config.qmk.fm/
- Select cherrybstudio/cb87 in keyboard section.

In case you want to use VIA (preferred alternative):
1/ Quit VIA first
2/ Put your keyboard's PCB into reset/bootloader mode and run QMK Toolbox ( you can enter reset/bldmode by shorting 2 pins in the middle of the 10 pins debug pinout behind the PCB - they are near to arrow keys )
3/ Click on "Clear EEPROM" inside QMK Toolbox, and then browse to the.hex file that you've downloaded, flash it
4/ Re-plug the keyboard if nessesary, have fun.

I also added the original via_config.json file for further use in Vial or whatever.
