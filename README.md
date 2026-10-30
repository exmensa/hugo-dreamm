Hugo Trilogy and Nitemare-3D for DREAMM  

Current status:  

Hugo's House of Horrors / Hugo's Horrific Adventure (1990)  
```
Detects:  
    DOS shareware v1.0 - v2.1  
    DOS registered v2.0 / 2.1  
    Windows shareware v1.4 / 1.5  
    Windows registered v1.5  
Options set for disabling sound in registered DOS versions & automatic playback in versions that include PLAYBACK.DAT 
TODO:
    Windows versions currently freeze before displaying anything; errors from windows.unexpected:  
    [    1244] [1MAINp9:1] ====> CreateFile() failed to open file C:\Program Files\hugowin\hwin_1\CONFIG.DAT: OPEN_EXISTING but file doesn't exist
    Manually adding CONFIG.DAT fixes CreateFile() but game still freezes, there are references to unimplemented APIs
```
---
Hugo II: Whodunit? / Hugo's Mystery Adventure (1991)  
```
Detects:  
    DOS shareware v1.0 / 1.1 / 1.2 / 2.0 / 2.1  
    DOS registered v2.0 / 2.1  
Options set for disabling sound in registered DOS versions & automatic playback in versions that include PLAYBACK.DAT  
TODO:
    add detection for Windows versions
```
---
Hugo III: Jungle of Doom / Hugo's Amazon Adventure (1992)  
```
Detects:  
    DOS shareware v1.0 / 1.1 / 2.0 / 2.1  
    DOS registered v2.0 / 2.1  
Options set for disabling sound & demo mode in DOS versions and automatic playback in registered DOS versions that include PLAYBACK.DAT
TODO:
    add detection for Windows versions
```
---
Nitemare-3D (1994)  
```
Detects:  
    DOS shareware v1.0 / 1.1 / 1.5 / 1.7 / 1.8 / 1.9 / 2.0  
    DOS registered v1.3 / 1.8 / 2.0  
    Windows shareware v1.6 / 1.8  
    Windows registered v1.6  
Options set for audio selection and running the map viewer included with the registered version  
TODO:
    Windows versions crash when going fullscreen:  
    EAX=00000013 EBX=0000B9A6 ECX=00000000 EDX=00000000 ESI=00000149 EDI=00000141 EBP=0000BA1E ESP=0020:00121D5C  
    FLAGS=---3---S--P- DS=013F ES=00F7 FS=003B GS=0000 0018:001208B5 001208b5: cf               iretd  
    FATAL ERROR: Unhandled 16-bit exception: EXCEPTION_PRIV_INSTRUCTION at 0107:45A2
```
