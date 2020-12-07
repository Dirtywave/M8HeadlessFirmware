# M8 Headless Firmware for Teensy 4.1
M8 Headless Precompiled Firmware. Used for Teensy 4.1 connected to a host computer via USB.
Read the included instructions and see also https://github.com/DirtyWave/M8DisplayTouchdesigner

For optimal performance of the SD card should be formatted FAT32 using the SD formatting tool - https://www.sdcard.org/downloads/formatter/
As well the random read speed of the card must be very good. Testing has shown two cards that are currently suggested: 
- Transcend 300s 32GB Micro SD
- Sandisk 32gb ultra microsdhc

## About samples on the SD card ##
Samples should be located in /Samples on the card in mono or stereo wav format. Try to use mono where you can to reduce load on the SD card if you're playing back multiple channels of samples. Subdirectories are supported but the maximum file path length (including the name and extension) is 127 characters.

## Preliminary user-contributed manual ##
A user contribted manual is available here: https://www.notion.so/M8-manual-ae3cb262908840b4b834c7485d3d4fb6

## More help is availble on our discord server ##
Join us on Discord! https://discord.gg/7SVuZe9
