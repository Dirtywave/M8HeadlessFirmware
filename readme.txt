----------------------------------------------------------------------------------
FIRMWARE UPDATE INSTRUCTIONS
----------------------------------------------------------------------------------

Windows (7/8/10/11) and MacOS:
Download & Install TyTools (Note for Mac: Move it to the Applications folder):
https://github.com/Koromix/tytools/releases

1. Unzip the Firmware. (Yay you did this!)
2. Plug in M8 via USB DO NOT USE A USB HUB IF IT CAN BE AVOIDED
3. Turn M8 on.
4. Close all other applications
5. Open "TyUploader" - Note: "TyCommander" was also installed, don't use that.
6. Make sure "M8 [xxxxxxxx]" is selected in the dropdown.
7. Click "Upload" select the correct model hex file from this zip.


Note for Windows 7 - Download and install Teensyduino to install the USB 
driver needed for flashing M8 firmware:
https://www.pjrc.com/teensy/td_download.html


----------------------------------------------------------------------------------
M8 HEADLESS
LIMITATIONS AND IMPORTANT NOTES
----------------------------------------------------------------------------------

BACKGROUND

M8 Headless was originally created to allow access for users who could not afford
the physical M8 hardware, and to provide a backup and continuity option for owners 
of the hardware. While it shares the same core firmware, M8 was fundamentally 
designed as a tightly integrated hardware instrument.

The physical M8 hardware enables a level of performance, immediacy, and reliability
that is not achievable in a USB-only environment. Continued development of M8 
including over five years of free firmware updates has been made possible through
the support of the physical hardware.

SUMMARY

M8 Headless provides access to the M8 workflow outside of the physical device, 
but it comes with significant trade-offs in latency, audio capability, 
responsiveness, and overall experience.

LIMITATIONS OF HEADLESS MODE

AUDIO AND LATENCY

- Significantly higher latency. M8 hardware is ~2.3ms physical input to output
- No physical audio input or output support
- USB audio limitations:
  - 16-bit only
  - Stereo only
  - No multichannel USB audio support
  - No USB audio rerouting support

MIDI

- No physical MIDI input or output
- USB MIDI only, dependent on host system behavior

DISPLAY AND USER INTERFACE

- Display drawing is handled over serial resulting in reduced refresh rates

STORAGE

- No MSC support - SD card cannot be mounted as a USB drive for file transfer

POWER AND STATE

- No instant on or off operation
- No automatic resume to the previous state without saving
- Startup and shutdown behavior is dependent on the host operating system

PHYSICAL EXPERIENCE

Headless does not provide the physical experience of the M8 hardware, including
its mechanical keys, machined aluminum enclosure, integrated controls, 
and long battery life.

DEVELOPMENT EXPECTATIONS

Headless development may experience delays or extended gaps between updates
Feature parity with the hardware version is not guaranteed

PERSONAL NOTE

It has been disheartening to see headless increasingly used on Linux gaming 
handhelds, as this was not its original intended use. Headless was created as an 
accessibility and backup option, not as a substitute for the physical device.
While it has been genuinely nice to see the community flourish around headless, 
and it has not been a financial burden, continuing support in this context 
has been challenging on an emotional level.

SUPPORT AND LICENSING DISCLAIMER

Headless builds are not officially supported.
Issues specific to headless operation, host operating systems, USB audio behavior, 
or third-party devices are not guaranteed to be addressed. The Headless M8
firmware is provided free of charge.

Permission is not granted for commercial products or services involving 
distribution of the firmware, whether bundled, preinstalled,
or sold in any form.

There are no guarantees or commitments regarding future development, fixes, 
or feature additions for headless.


