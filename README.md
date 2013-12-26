iotogglem0_wspl
===============

Author: Hussam Al-Hertani

This is a Template project for the STM32F0 microcontroller. For more information 
Please read "http://hertaville.com/2013/09/03/stm32f0discovery-command-line-ide/".

The template project relies on the STM32F0 Standard peripheral library.
The included makefile can program the chip from the command line using Texane's st-flash utility or OpenOCD.
The included makefile can initiate a debug session from the command line using Texan'e st-util utility or OpenOCD
and the arm-none-eabi-gdbtui utility.

This template implements a Makefile that assumes a particular naming
conenvention regarding the file structure.

First, the top-level directory is titled:
    EmbeddedArm 
with a workspace directory insided of it:
    EmbeddedArm/workspace
To follow the naming convention, clone this repository as a directory within 
that workspace:
    EmbeddedArm/workspace/iotoggle_wspl
Finally, this Makefile also assumes that the ST-developed example code has
been downloaded from ST's website and exists as a subdirectory of EmbeddedArm:
    EmbeddedArm/STM320F030-Discovery_FW_V1.0.1
Note that the version number is subject to change.

Also note that to download ST's example code, you must be logged in with an 
account made on their website. Otherwise, the example code will be omitted
from the webpage.
