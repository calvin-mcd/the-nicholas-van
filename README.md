# The Nicholas Van
 
The Nicholas Van is an EC (topre) pcb for trashman's [v4n4g0n](https://trashman.wiki/keyboards/v4n4g0n) keyboard. The pcb supports a both the 625U spacebar, and the split 275U, 225U spacebars. But each need their own respective plate. 
Plate files for Hull and Embrace cases are available. Check the plate & hardware section for what you will need. 
The pcb comes with a usb port by default, but supports a Daughterboard connector (either jst or pico). It also supports another 5pin Jst connector for the Rotary Encoder board from the Embrace.

***VERSIONS***:
In the production folder you will find both the prototype production files and the revision files (as well as various plate files). Please be aware of their differences and what aspects have not been confirmed to work yet when ordering pcbs.
- The prototype was sporting a STM32F401 MCU and its rgb could not be made to work. This could have been a firmware issue, but hardware issues could not be ruled out. Otherwise the pcb was fully working
- The revision is using a STM32F072 MCU and simplified components and an attempt to fix the rgb hardware. The revision has not been prototyped yet and firmware needs to be adapted to its rgb hardware setup.

## Layout

![](https://github.com/calvin-mcd/the-nicholas-van/blob/main/Images/KLE.png)

[Link](http://www.keyboard-layout-editor.com/#/gists/a55206434a137895f2c476b4f5ef8018)

## Images

![](https://github.com/calvin-mcd/the-nicholas-van/blob/main/Images/top.png)  
![](https://github.com/calvin-mcd/the-nicholas-van/blob/main/Images/bottom.png)  

## Firmware

The basic EC firmware is ready to go and the source code is provided for tweaking any settings.

## Plates & Hardware

Plate files are available for OEM (original and deskey housings), for each respective bottom row choice, and for the original plate, Hull and Embrace cases.

Furthermore, you will need 26x 10mm M2 screws and M2 nuts to assemble the pcb. O-rings might help aligning the pcb and usb port in some cases, but is not required.

## Disclaimer

Please note that this project is a work in progress with no guarantees of a working outcome. No-one involved in this project is responsible for any usage issues that may arise. Order at your own risk. Support will not be provided but pull requests will be reviewed and possibly accepted.

## License

Shield: [![](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is licensed under a  
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

[![](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

## Credits

big thanks to M4NU for repeatedly begging for a topre vanagon pcb! ;)

Otherwise, many thanks for feedback, help, references go to Sporkus, Cipulot\#8455 & matthewdias\#2671.

Any questions, contact Calvin0563 on Discord. 