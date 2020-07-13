X9SD DLDI Driver
Hardware driver to facilitate SD card access for Ninjapass X9

Version: 0.5:
06/30/2020
- Remove static DLDI allocation, all compiled objects are ordered the way they should: dynamically, while filling DLDI binary to 16K


Version: 0.4
06/29/2020

- Compile with dkARM r43: Makefile_dkarm (rename it to Makefile) -> make clean -> make
- Compile with TGDS 1.6: Makefile -> make clean -> make

Changes:

Version: 0.3
09/16/2019

- Remove DMA dependency, use a faster ARM memcpy. Improves stability.
- A bit faster performing writes to SD / less resource intensive
- Fix/remove warnings


Version: 0.2
09/23/2016
- Fixed proper DLDI support for most if not all LIBNDS homebrew, everything I have tried works


Coto.

-

Version: 0.1
Copyright (C) 2007 by CJ Bell
siegebell at gmail dot com


This software is provided 'as-is', without any express or implied warranty.  In
no event will the author be held liable for any damages arising from the use of
this software.  Permission is granted to anyone to use this software for any
purpose, including commercial applications, and to alter it and redistribute it
freely, subject to the following restrictions:

 1. The origin of this software must not be misrepresented; you must not claim
    that you wrote the original software. If you use this software in a
    product, an acknowledgment in the product documentation would be
    appreciated but is not required.

 2. Altered source versions must be plainly marked as such, and must not be
    misrepresented as being the original software.

 3. This notice may not be removed or altered from any source distribution.

