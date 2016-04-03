### Roaddog Labs Bart Pro XL Firmware
### 
__Not for production use – use with caution!__

This fork is configured specifically for the Roaddog Labs Pro XL.  It's
currently based on Marlin 1.1.0-RC3 that was pushed 01 Dec, 2015.  This build is configured for a Mini Rambo controller using 360 mm x 240 mm print bed and Reprap Discount GLCD display

This build defaults to an induction probe in place of a mechanical Z end stop. The file [Configuration_mechanical_z.txt](../blob/master/BartProXL%20firmware%20/Bart_Pro_XL/Configuration_mechanical_z.txt) contains the settings for using a mechanical end stop in the A position.  To use this configuration rename the file to Configuration.h  and build the firmware.

The [original README.md](../blob/master/BartProXL%20firmware%20/Orig_README.md) from the fork.