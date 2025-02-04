# SNES2CDi Controller Adapter
Original Project & Instructions: https://github.com/anarterb/SNEStoCDi

Program Flashing Guide (for testers and DIY'rs: https://docs.google.com/document/d/1Fmiw_veQGTTWU_O_yBOA6g7UhlBHqrEB8uqCt-3lErI/edit?usp=sharing

Small Batch Production Interest Form: https://forms.gle/BDZ2jHTWuCF3Lbzz9

This PCB allows users to create their own controller adapter by soldering components to one location. Using an SNES controller port and an Arduino Nano, you can choose to make a MiniDIN adapter. This is still a work in progress and has not been tested. Original documentation can be found in the author's GitHub.

3D printed housing and a BOM are now available (above and below).

# Known Issues
The current iteration of the SNEStoCDi code does not support the SNES mouse or other pointing devices. This is currently being worked on and will be available in a future software revision.

# FragolTech Specific Instructions
Custom code for this adapter PCB is available in the Arduino Code folder above. Load the sketch and the SNESPad library into the Arduino IDE and flash it to your Nano or Nano clone. This adapter should work without further configuration, just plug and play!

Please note that Nano clones may require a different configuration in the Arduino IDE. Check to make sure appropriate drivers are installed. If you have issues flashing the program, check your board settings and use the OLD version of the bootloader. If you have other issues, feel free to reachout to me at fragolroc@gmail.com

# Assembly

*Assembly reference pictures can be found in the above folder.

**PCB designs can be found at:**
  <br>OSH Park: https://oshpark.com/shared_projects/f0KiejEZ
  <br>EasyEDA:

**Arduino Nano (Clone):** <br>
https://bit.ly/3HXlJSC

**SNES Connectors:**<br>
https://bit.ly/34AOFBq

**8 Pin Mini DIN Jack:**<br>
https://www.digikey.com/en/products/detail/adam-tech/MDJ-008-FS/9832482

**8 Pin Mini DIN Cables:** <br>
  https://www.kraydad.com/mini-din-minidin-8-pin-cables/

**M2 or M2.5 Screws**
<br>Use 8mm-10mm M2 or M2.5 screws for this project<br>
https://www.amazon.com/m2-screws/s?k=m2+screws
