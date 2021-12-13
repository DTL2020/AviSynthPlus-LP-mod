# AviSynthPlus-LP-mod
LargePage support mod of AvisynthPlus
Just a place to keep source file and may be builds for release.
Currently based on Avisynth-Plus 3.7 release.

If got error: 

- CPUDevice: LargePages alloc error. Insufficient system resources exist to complete the requested service. 

 so the only known solution is to reboot Windows to get some contiguous physical pages again. Windows10 possibly reserves about 256 MB or memory for LP allocations. Or try to found and use RAM defragmentator at system runtime.
