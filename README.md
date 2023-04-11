# CherryB Works Freyr TKL files
![image](https://user-images.githubusercontent.com/64993772/230959743-d857d0b2-b724-40c8-876d-46bd66a202b4.png)

CherryB Works might have gone under, so in order to make sure the Freyr TKL can live I gathered all files related to it here.

## Plate files

The Freyr TKL uses what's known as the Jane V1 plate top mount, which means that Jane V1 plates fit on it as well.

The community has also done multiple plate files including half and full plates in both ISO and ANSI formats. The "Plates" folder has both of these.
The ISO files currently only have .DXF files, so no FR4 option unless someone wants to do it. If someone does end up doing the Gerber files for them, please let me know!

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

## Pictures from the original GeekHack thread
https://geekhack.org/index.php?topic=109124.0

Dimensions
![image](https://user-images.githubusercontent.com/64993772/231069383-c0624fc1-a59e-422d-9d4c-ae32cf6abfe1.png)

Original CB87 PCB layout
![image](https://user-images.githubusercontent.com/64993772/231069405-f2730426-282a-4896-960d-9e824819d5bb.png)

![image](https://user-images.githubusercontent.com/64993772/231069440-89d630da-dcbb-4cd6-94d7-5f36cb3e39ac.png)

![image](https://user-images.githubusercontent.com/64993772/231069508-c6b11505-1f68-4c73-8880-87c36c76f421.png)

![image](https://user-images.githubusercontent.com/64993772/231069660-de80f1c5-15ba-42ef-b5ec-456eca12dd2c.png)
