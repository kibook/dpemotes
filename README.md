# dpemotes
Emotes / Animations for fiveM, now with with prop support for humans and dogs.

Installation Instructions:

add dpemotes to your server.cfg

start dpemotes

For all animations to work, you will be required to run the latest build on FiveM, to do so;

Set server to latest gamebuild by opening run.bat (Windows) or run.sh (Linux) with a text editor (Notepad++ for Windows, or something similar)

Add the following: +set sv_enforceGameBuild 2372 (Or newer).

2372 is the current latest supported DLC for FiveM, the MPTuners DLC.

For txAdmin, you can put in in the Settings > FXServer > Additional arguments. There is even as a placeholder at this place specifically for this.

SQL keybinds can be enabled in fxmanifest.lua, however have been commented out. Open it and remove the comment from line 6, then restart dpemotes.

These two lines:  -- dependency 'ghmattimysql'.


Other instructions please check the fivem forum thread.

https://forum.fivem.net/t/dpemotes-356ish-emotes-usable-while-walking-props-and-more/843105
