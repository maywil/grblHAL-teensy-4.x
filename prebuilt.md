## Prebuilt Firmware

### Loading Firmware onto a Teensy 4.1
Follow these basic steps:
1. Download the [firmware configurations file](https://www.pjrc.com/teensy/loader.html) and extract the contents.
2. Select the .hex file that coresponds to the features you will use.
3. Obtain the Teensy Loader for your platform.
4. Use the loader to load the .hex file into your Teensy.

See the platform sections for details and hints.

#### Windows 
Download Teensy.exe from the [PJRC Website here](https://www.pjrc.com/teensy/loader_win10.html). The page may say Windows Vista but it works for all recent Windows versions.
Plug in your Teensy 4.1 via USB. Find Teensy.exe and run it.  It should open as a small window. In File/Open HEX File, select and open the .hex file you want and press OK. Then, press the button on the Teensy 4.1. You are ready to test it now. 

#### Macintosh OS X
Macintosh instructions [are here](https://www.pjrc.com/teensy/loader_mac.html). Plug in your Teensy 4.1 via USB. Follow the instructions to install and run the loader. It should open as a small window. Then, from the File name, choose "Open HEX File" and open the .hex file you want and press OK. Select "Program" from the "Operations" menu, or click the Program button on the tool bar. It should display a brief loading message. You are ready to test it now

#### Linux
Instructions for Ubuntu [are here](https://www.pjrc.com/teensy/loader_linux.html). Other Linux versions work though you will need to build the loader for your platform.  The [instructions and links to the github repository are here.](https://www.pjrc.com/teensy/loader_cli.html)