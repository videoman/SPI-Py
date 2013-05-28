Added code for SM16716 Addressable LEDs.  They use 25-bit words- one 1 bit is the start bit, and then 3 8-bit words to control the RGB for each LED. 

Please check out the Strange Attractors python code in my repo to control this arry of 400 addressable LEDs

--- from SPI-Py module ---
SPI-Py: Hardware SPI as a C Extension for Python
======

COPYRIGHT (C) 2012 Louis Thiery. All rights reserved. Further work by Connor Wolf.

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License V2 as published by the Free Software Foundation.

LIABILITY  
This program is distributed for educational purposes only and is no way suitable for any particular application,
especially commercial. There is no implied suitability so use at your own risk!
