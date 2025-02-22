**---File Versions--** 
1) firmware - Clean Build.bin : Clean Build of Marlin 2.1.2.5 (without MICROPROBE-V2 config) for the BIQU-B1-SKR-V1.4
2) firmware - MICROPROBE-V2.bin : MICROPROBE-V2 specific build of Marlin 2.2.2.5 for the BIQU-B1-SKR-V1.4
3) firmware - MICROPROBE-V2 - 2025-02-22.bin : MICROPROBE-V2 specific build of Marlin 2.2.2.5 for the BIQU-B1-SKR-V1.4 with a number of enhancements, which can be summarised as follows:
   - Increased the probing points from 3 x 3, to 5 x 5. This allows for more accurate AUTO Leveling
   - Added SKEW_CORRECTION to allow for skew compensation via M852 command.
   - Added PROBE OFFSET WIZARD to Marlin Menu, this is because I found the touch-screen probe-wizard to not work well so I switched to the Marlin one. 

**---Important Notes---** 
1) The files provided will only work if your BIQU-B1 printer is equipped with the **BOARD_BTT_SKR_V1_4** Motherboard.
2) Make sure you have flashed your BIQU-B1 with the latest BIGTREETECH TouchScreen Firmware; otherwise, it might not be compatible with this motherboard firmware.
3) The "MICROPROBE-V2" version of the firmware assumes you have used the probe connector at the back of the BIQU-B1.
4) Using the "MICROPROBE-V2" version of the firmware will **disable** the **Z-axis micro-switch**, and the MICROPROBE-V2 will be used for Z-Homing and leveling.
5) Make sure you adjust the **Probe Offsets** for your specific installation; mine is installed to the right of the extruder.
6) **Mesh-Bed-Leveling** will be replaced with **Auto Bed Leveling**, so make sure to enable ABL in CURA or whichever slicer you use.

**---How to use these files---** 

1) Download the file you are interested in.
2) Rename the file to "firmware.bin"
3) Copy the file to an SD-Card and Flash to your BIQU-B1-SKR-V1.4
