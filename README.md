![Header](pictures/mainheader.png)
<br>

<div align="center">
  
  ## ⬆ Update Highlights 04/26/24 — Marauder v0.13.10 ⬆

</div>

- **RGB LED enabled for builds w/o GPS thanks to [**lsdlsd88**](https://github.com/lsdlsd88)**

- **Detect Pwnagotchi [enabled](https://github.com/Fr4nkFletcher/ESP32-Marauder-Cheap-Yellow-Display/blob/master/screenshots/pwn2.jpg) in the WiFi Sniffers submenu. (currently for builds without GPS. Fix hopefully soon)**
    
- **SwiftPair Spam now 100% functional** — Samsung, Google, and BLE spam crashing should now be nonexistent.

- **<a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff>Evil Portal storage adjustment</a>** — Moves all portals into a folder instead of root of sd card.

- **For info on adding an external antenna, click [here](https://github.com/Fr4nkFletcher/ESP32-Marauder-Cheap-Yellow-Display/blob/master/AntennaMod.md).**

<hr>
<br>


<b>A beautiful fork of wifi Marauder 13.10, a suite of WiFi/Bluetooth offensive and defensive tools for the 2.8'' ESP32 Module ESP32-2432S028R WiFi+BT Dual-core 240X320 Smart Display.</b>
<b>This fork features a few great fixes and customzations.</b>
  
  <br>
  
  
## To build this fork of Marauder from source

- Head over to <a href=https://github.com/smoochiee/Marauder-FOR-CYD---CHEAP-YELLOW-DISPLAY>smoochiee's tutorial</a> and start from step 1 in his tut.
- When you get to the "LIBRARIES" section you can use the libs he has linked or the ones in this repo which are the same.
- Now on the step in smoochiee's tutorial where he mentions to download the source code for Marauder, use the files from <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/esp32_marauder>esp32_marauder</a> instead (These files contain the sketch edits already). Then head back to <a href=https://github.com/smoochiee/Marauder-FOR-CYD---CHEAP-YELLOW-DISPLAY>smoochiee's tutorial</a> and Follow the rest of the steps provided by the legend himself and you should be good to go. I will be adding my own tutorial for flashing this build to your CYD very shortly.

<br>

## Web-flasher tool
 <a href=https://atomnft.github.io/CM-Box/flash0.html>Custom Marauder Flasher tool for CYD</a>
 <b>Instructions are simple. Choose your hardware, and then hit connect.</b>
  
  <br>
  <br>
  <br>
  
  
## Fixes (These are included in this fork)
  
  - `BLE swift pair fix` [BLE FIX](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/BLE%20Swiftpair%20Fix)

  - `Evil Portal storage fix` [Evil Portal SD fix](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff)
  
  - `RGB LED fix` [RGB LED fix]( https://github.com/lsdlsd88/ESP32-Marauder-Cheap-Yellow-Display/commit/2b206c2deac19cdd6e9836a7d4e7446e263ac672?diff=split&w=0#diff-9bf7e9e1cf160aa5fb95103a7c21a502bc264a3d66a0b9f48e646781af0d4d81)
  
 
 
 <br>
 
## SD portal fix
  <b> This fix is to relocate all the portals for evil portal to a folder on the sd card. When you install Marauder on the CYD all the protals used in evil portal get stored on the root of the sd card. To me this is a nuisance as all the pcap and other files that are captured while sniffing get thrown on the root of the sd as well. I have gone through and adjusted the code so you may create a folder titled "portals" and store the html files there.<br>In the <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff>Evil Portal</a> section are the files needed along with directions on usage. </b>
 
 <br>
 <br>
 <br>

## Shoutouts! 📢
<b>A huge thank you goes to two wonderful people whom without I would have not made it as far as I  did learning.</b> 
<br>
<b>Thanks to <a href=https://github.com/Fr4nkFletcher>Fr4nkFletcher</a> for all your guidance and late night replies.</b>
<br>
<b>And thank you to <a href=https://github.com/smoochiee>smoochiee</a> for helping with the bootscreen and the badass tuts for building our own Marauder.</b>
<br>
<b>Also thanks to 3DJoe for figuring out the touch functions for marauder on the CYD..</b>
<br>


  
  
  