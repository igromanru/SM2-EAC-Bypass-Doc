# Warhammer 40k Space Marine 2 - EAC Bypass guide
## Introduction
Usually, games that can be played offline can be started without AntiCheat and EasyAntiCheat supports this as well.    
It’s up to the developers to add extra checks for whether EasyAntiCheat is running.
When Space Marine 2 starts, it checks if EAC is running and whether certain files were modified (hash comparison).    
If it finds modifications, it goes into **modded files** mode.  
Another check is for mods: if the game finds files in the *mods* directory, it goes into **mods detected** mode.

