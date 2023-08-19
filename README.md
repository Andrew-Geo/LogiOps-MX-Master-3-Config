# LogiOps-MX-Master-3-Config
A logid.cfg file for the Logitech MX Master 3, with shortcuts suitable for light Content Creation on a tenkeyless laptop.  

**Dependencies**  
This .cfg file is to be used by LogiOps by PixlOne: https://github.com/PixlOne/logiops/  

**Documentation and Resources**  
This configuration file was made by looking through these:  
https://github.com/PixlOne/logiops/wiki/Configuration  
/usr/include/linux/input-event-codes.h  or  https://github.com/torvalds/linux/blob/master/include/uapi/linux/input-event-codes.h  
https://gist.github.com/danish17/c5c5fb6eb99d452c339e393ed637640b  

**Installation**  
Place the file in /etc/  
The path to the file should be: /etc/logid.cfg  

**Features Overview**  
Forward Button:  
  Tap: Forward  
  Drag Upwards: Right Bracket (once per 25 pixels of dragging)  
  Drag Downwards: Left Bracket (once per 25 pixels of dragging)  
  Drag Rightwards: End  
  Drag Leftwards: Home  
Back Button:  
  Tap: Back  
  Drag Upwards: NUM8 (once per 50 pixels of dragging)  
  Drag Downwards: NUM2 (once per 50 pixels of dragging)  
  Drag Rightwards: NUM6 (once per 50 pixels of dragging)  
  Drag Leftwards: NUM4 (once per 50 pixels of dragging)  
Gesture Button:  
  Tap: Toggles Media Playback  
  Drag Upwards: Volume Up (one step per 50 pixels of dragging)  
  Drag Downwards: Volume Down (once per 50 pixels of dragging)  
  Drag Rightwards: Next Media in queue  
  Drag Leftwards: Previous Media in queue  
Top Button:  
  Tap: Toggles SmartShift  
  Drag Upwards: Raises DPI by 800  
  Drag Downwards: Lowers DPI by 800  

**Tested On:**  
Honor Magicbook 14, with LogiOps 0.3.3 on Wayland Gnome 43.6 on Debian 12  
  
