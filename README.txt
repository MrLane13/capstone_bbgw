/*
* ORIGINAL AUTHOR: DR. CHENG LIU
* EDITING AUTHOR : LANE MILLS
* LAST UPDATED README : 20170425 (YYYMMDD)
*/

INTRODUCTION
The purpose of this file is to assist in the running of the tmp36.cpp code.

GIT
git clone https://github.com/MrLane13/capstone_bbgw.git

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

STEPS
01. Connect the Beaglebone Green Wireless via USB to your computer.
02. Wait for the blinking lights (the 4 near the micro USB port) to assume a sweeping pattern.
03. (OPTIONAL: SSH into the BBGW. If you do this, skip to step 7).
04. The BBGW should show up on your computer as a directory. Open the directory, and double click/run the START.html file.
05. Follow the on-screen steps to install any necessary drivers.
06. Navigate to the Cloud9 code editor.
07. Navigate to a directory where you would like the tmp36.cpp code to live.
08. (OPTIONAL: if you connected your BBGW to a wireless netowrk, install git, run the code in the above GIT section, then proceed to step 10. If you don't have any wireless connection, proceed to step 9.)
09. Run 'g++ tmp36.cpp -o tmp36' without the single quotes.
10. Run './tmp36' without the single quotes to test the code.

DONE
