# Rebuild ue4 project
Python automation script that deletes some folders and generates visual studio files for games made in unreal engine 4

In order for this to work properly you have to put this file in the root directory of your game, where you have files like .uproject. Then open rebuild.py file in any text editor and fill constants in lines 5 and 6. For UE4_ENGINE_PATH e.g. r'D:\Soft\UE_4.26'.

WARNING! If you have any additional extra info in following folders, know that it will get deleted:
.vs/
Binaries/
Intermediate/
Saved/

Also, if you're unfamiliar with python, you can run this file in command line just by typing in cmd "python rebuild.py". Also, idk if this would work on Mac/Linux. And ofc if you don't have python installed this won't work
