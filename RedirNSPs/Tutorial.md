Download devKitPro and Msys2 if you do not have them

If you are doing this for the first time, follow the step below. Otherwise just skip till after the ='s

Open up CMD and type these commands: 

=================================

pacman -S switch-sdl2_mixer

y

pacman -S switch-libmodplug

y

pacman -S switch-mpg123

y

pacman -S switch-libvorbisidec

y

pacman -S switch-libogg

y

==================================

Download forwarder-creation-kit from here:

https://snip.li/forwarder-creation-kit

open the "exefs-creation" folder

open the "sample_hbmenu_loader" folder

right click "Makefile"

select "Edit with Notepad++"

replace what you need to

right click "hbmenu.json"

select "Edit with Notepad++"

replace what you need to

open the "source" folder

right click "main.c"

select "Edit with Notepad++"

go to line 210

edit the path to your .nro

go up a folder

open that folder with CMD

type "make"

open the "build" folder

right click and copy "exefs"

go up three folders

open the "nsp-creation" folder

right click and paste

open the "template" folder

right click "npdm.json"

select "Edit with Notepad++"

edit the needed things

go up two folders

open the "nacp-creation" folder

open CMD in that folder

Open this site in Chrome and right click

https://pastebin.com/raw/ULdLvMck

click "save as" 

change "text document" to "all files"

save the file as "input.json" in the "nacp-creation" folder

edit the "input.json" file with the necessary things

open the CMD window we opened earlier

type "linkle nacp input.json control.nacp" 

copy the "control.nacp" file

go up a folder 

open the "nsp-creation" folder

open the "control" folder

paste in the "control.nacp" file

get a 256x256 .jpg and open it with paint

click "file"

"save as"

change the .jpg or .png at the bottom to 24 bit .bmp

save it in "icon-creation"

open the new .bmp with paint

click "file"

"save as" 

save it as "icon_AmericanEnglish.jpg"

save it in "icon-creation"

open the "icon-creation" folder

right click the .jpg file we just made and click "Rename"

change the .jpg part to .dat and click yes when prompted (you may need to follow this if there is no .jpg at the end: https://www.itsupportguides.com/knowledge-base/windows-7/windows-7-how-to-display-file-extensions/)

copy the "icon_AmericanEnglish.dat" file to your "control" folder

go up a folder

open CMD in this folder

type "hacbrewpack.exe --noromfs --nologo"

==================================================

Your NSP Has Been Created! Use it however you want.
