Gams-OCProgs
============

Programs for OpenComputers, by Gamax92

- loadtape.lua

Loads a block of data into a tape drive, also sets playback speed.

- formattape.lua

Clears an entire tape back to 0x00.

- dumptape.lua

Dumps a tape into a file.
Considering HDD's only go up to 4MB, this isn't that useful.

- install.lua

Copy / to a mount point, then setup a boot script to remount /.

- tapefs.lua

Provides a filesystem proxy that converts tape drives into files.
Install in /lib

- tapefsd.lua

Searches for all tape drives and mounts them with tapefs.

- fat16.lua

Provides a filesystem proxy for fat16 formatted files.
Install in /lib

- fattest.lua

Dump fat information provided by the fat16 proxy.
