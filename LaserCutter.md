# Laser Cutter
### Custom built paper laser cutter from mendel 3d printer with a 405NM laser diode. 

## Index
1. Spects
2. Software Installation
3.  Software Settings
4. Hardware Settings

### Spects
**Mendel 3D chassis:** Width = W, Lenght = L, Height = H

**Raspberry Pi:**  Usine Raspberry Pi 3b

**CNC Hat:**  Using bCNC to execute the gCode

**Laser Diode:** Wave Length: 405NM Power: 500MW Electric Current: <2A Input Voltage: DC/AC 12V Working temperature: -10 ~+40℃ Size: 33*33*65MM Cable Length: 40CM Light Color Blue Purple Feature Laser Focus Adjustable If speed is slow enough , it can cut 2mm paperboard (Run it 2 times) TTL: 0-5v. 0v on; 5v off. TTL control the frequency Packing Item: (include laser protective goggles).  https://www.amazon.com/gp/product/B076FX9R2W/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1





### Software Installation
1. Install Inkscape
https://inkscape.org/release/inkscape-0.92.4/
2. Install XQuartz
https://www.xquartz.org/
2.  Install J Tech laser plug-in
https://jtechphotonics.com/?page_id=1980
* Note: Open InkScape's contents (left click), then navigate to share -> extentions -> and add J Tech files
https://www.youtube.com/watch?v=StNTZ1xeW0o

### J Tech Prefrences for Laser Cutter
1.  Laser ON NA
2. Laser OFF NA
3. Travel Speed (mm/min) 500
4. Laser Speed (mm/min) 100
5. Laser Power 255
6. Power-On Delay (ms) 0.0
7. Passes 3 For light colors 6 passes for dark color 
8. Pass Depth (mm) 1.0
9. Director /Users/sjamesparsonsjr/Desktop/LaserFiles
10. Filename .gcode
11. Add numeric suffix CHECKED
12. Units mm
13. Live Preview CHECKED
