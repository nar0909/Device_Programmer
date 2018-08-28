# Device_Programmer
Device Programmer for Atmel SAM microcontrollers
This Software tool is to help people who would like to upload a compiled binary files generated from Arduino IDE or similar software into a SAMD based Arduino board.

PREFACE:
1.FEEL FREE TO DOWNLOAD FROM MY REPO.
2.THIS IS AN OPEN SOURCE TOOL, SIMPLY BUILT TO ASSIST PEOPLE TO UPLOAD/FLASH NEW ARDUINO FIRMWARES INTO YOUR BOSSA SUPPORTED BOARDS.
3.THOUGH TESTED AND VERIFIED, I/THIS TOOL WON'T BE RESPONSIBLE IN ANY MANNER FOR BRICKED BOARDS OR COMPLICATIONS WHATSOEVER.
4.PROJECT CONTAINS:
                    1."Application" Folder
                    2."Firmware_Loader" Folder
5."Application" Folder, contains a .exe based form.
  "Frimware_Loader" Folder contains three other sub folders as follows,
                    1."firmwares" (pls paste all compiled binary (.bin) files here.
                    2."outputs" (sample output screenshots from my Arduino Zero board.
                    3."tools" (bossac.exe cmd line tools for flashing/uploading)


HOW TO USE THIS TOOL:
1.IF YOU ALREADY HAVE A COMPILED BINARY FILE OF YOUR PROJECT (.bin format) THEN SKIP THIS STEP.
  IF YOU DO NOT HAVE A COMPILED BINARY FILE AND DO NOT KNOW HOW/WHERE TO FIND IT,
  OPEN ARDUINO IDE AND GOTO FILE-->PREFERENCES
  AT THE BOTTOM OF THE TAB CLICK ON THE LINK--> C:\Users\yourPC\AppData\Local\Arduino15\preferences.txt
  ADD A LINE IN THE preferences.txt as follows--> build.path=ADD YOUR PATH HERE WHERE YOU WANT THE .BIN FILE TO BE BUILD
  NOW RESTART ARDUINO AND COMPILE THE PROJECT YOU WANT FOR SAMD BOARD AND ONCE DONE NAVIGATE TO THE ABOVE FOLDER.
  YOU WILL FIND A FEW DIFFERENT FILES HERE PICK YOUR BINARY FILE OF TYPE .bin

2.NOW PLACE THE .bin into the "firmwares" folder (Note that this has to be placed before you start the .exe

3.NOW PLUG YOUR ARDUINO ZERO/SIMILAR SAMD BOARD THAT SUPPORTS BOSSAC

4.SELECT THE .bin FIRMWARE FILE FROM DROPDOWN LIST.

5.SELECT THE COM PORT FROM THE DROP DOWN LIST, For example Arduino Zero(COM 5)

6.SELECT THE BAUD RATE AS 1200bps (For triggering bootloader mode)

7.CLICK PREPARE.

8.AGAIN SELECT THE .bin FIRMWARE FILE FROM DROPDOWN LIST.

9.AGAIN SELECT THE COM PORT FROM THE DROP DOWN LIST, For example USB Serial Device(COM 6) --> bootloader triggered for programming

10.SELECT THE BAUD AS 1200bps

11.CLICK PROGRAM.

12.DONE. 

Please verify the state of the device and use "CONTINUE" for using a built in SERIAL PORT to read/write to the device.

DISCLAIMER:
This software tool is built on promoting the open source community.
If you want the source code for commercial purposes, please write to me directly.
If you have any issues with the tool, please let me know.


CONTRIBUTORS:
Device_Programmer --> Myself (Nar Prathipati (nar0909))
Serial Software(CONTINUE button in my tool) --> wterm open source vb.net project




