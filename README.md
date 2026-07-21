# Ps2-OPL-connect-to-POP-Os-Linux
Hopefully this will expose some of the pitfalls and traps.
Pop OS ver 22 is still able to use smb1
smb1 is an insecure pretty old server
PS2 is what is known as old legacy.
nothing is plug n play .. it will only do what you tell it within the confines of its own system. So you have to configure your samba server to use smb1. even linux has evolved beyond the old legacy stuff, so you have to force samba to use smb1.

the image that i have posted here is the conf setup that i used for setting up samba in POP Os
there are only 2 variables, the path to your share folder must be exactly as it is in your system. right click on the folder and look in properties for the full path.

Then the force user must be your user name for the linux pc .. mine is rocket.

To keep this page as short as possible 
instead of posting linux cli etc, use Chatgpt to assist you with setting up samba on your machine, I use it a lot.  the tricky part for getting ps2 to work will probably be more related to issues with file and folder permissions for the PS2SMB folder on linux system. You have to setup the folder for network sharing. right click on the folder and set the relevant buttons and read write permissions for Ps2 to work. i recommend just making it all read and write.
