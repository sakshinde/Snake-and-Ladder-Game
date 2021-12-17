# Snake-and-Ladder-Game
The designed snake and ladder game retains all the elements used in the classic version, only with some minor and healthy variations in the style.
Gaming is one of the most looked after part time hobby or a stress buster, so making it a real stress buster is the main aim of this game.
The bot challenges you to win the game before it wins.
It’s a modern snake and ladder game which is even more reliable than any other game as there’s no brainer required. 

for setup:
Step 1 : Download codeblocks-20.03-setup.exe from https://sourceforge.net/projects/codeblocks/files/Binaries/20.03/Windows/codeblocks-20.03-setup.exe/download. 
Step 2 : Download MinGW from https://sourceforge.net/projects/mingw/.
Step 3 : Download Supported files for graphics from  https://drive.google.com/drive/folders/1762UAzYtrSXdhgWMsYoLSBCSilpPwSoJ?usp=sharing.
Step 4 : Copy & Paste “graphics.h” and “winbgim.h” into your
    C:\MinGW\include folder.
Step 5 : Copy & Paste “libbgi.a” into your C:\MinGW\lib folder.
Step 6 : Open your codeblocks and go to Settings -> Compiler -> Linker 
    Setting -> Other linker options and paste 
   “-lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32” into it.
