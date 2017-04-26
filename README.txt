/*
* ORIGINAL AUTHOR: DR. CHENG LIU
* EDITING AUTHOR : LANE MILLS
* LAST UPDATED README : 20170425 (YYYMMDD)
*/

INTRODUCTION
The purpose of this file is to assist in the running of the tmp36.cpp code.

INFORMATION
This was orignially written to be compiled on Angstrom linux running on a Beaglebone Green Wireless.
Because of this, some portions of this code may fail to compile on other systems, and will require 
modification to function.

REQUIREMENTS
1x Beaglebone Green Wireless
1x g++ compiler
1x tmp36 temperature sensor - this is a physical sensor
3x jumper wires
1x breadboard

STEPS:
1. Connect the Beaglebone Green Wireless via USB to your computer.
2. Wait for the blinking lights (the 4 near the micro USB port) to assume a sweeping pattern.
3. (OPTIONAL: SSH into the BBGW. If you do this, skip to step 7).
4. The BBGW should show up on your computer as a directory. Open the directory, and double click/run the START.html file.
5. Follow the on-screen steps to install any necessary drivers.
6. Navigate to the Cloud9 code editor.
7. Navigate to a directory where you would like the tmp36.cpp code to live.
8. (OPTIONAL: if you connected your BBGW to a wireless netowrk, install git, then run 
