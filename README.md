# M8 Headless Firmware for Teensy 4.1
M8 Headless Precompiled Firmware. Used for Teensy 4.1 connected to a host computer via USB.

Read the setup guide here: https://github.com/DirtyWave/M8Docs/blob/main/docs/M8HeadlessSetup.md

See also: https://github.com/DirtyWave/M8DisplayTouchdesigner

For optimal performance of the SD card, it should be formatted FAT32 using the SD Memory Card Formatter tool: https://www.sdcard.org/downloads/formatter/.
The random read speed of the card must also be very good. Testing has shown two cards that perform well and are currently suggested: 
- Lexar Professional 1800X (Expensive but nice)
- SanDisk 32GB Ultra microSDHC (Cheaper but reliable)

## About samples on the microSD card ##
Samples should be located in the /Samples directory on the card in mono or stereo wav format. Try to use mono where you can to reduce load on the microSD card if you're playing back multiple channels of samples. Subdirectories are supported but the maximum file path length (including the name and extension) is 127 characters.

## Preliminary user-contributed manual ##
A user-contributed M8 manual is available here: https://www.notion.so/dc3fe39bbc464879ac984f0a69cc61bf

## More help is available on our Discord server ##
Join us on Discord! https://discord.gg/7SVuZe9
