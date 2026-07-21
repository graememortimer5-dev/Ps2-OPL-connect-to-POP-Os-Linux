# Ps2-OPL-connect-to-POP-Os-Linux
Hopefully this will expose some of the pitfalls and traps.
Pop OS ver 22 is still able to use smb1
smb1 is an insecure pretty old server
PS2 is what is known as old legacy.
nothing is plug n play .. it will only do what you tell it within the confines of its own system. So you have to configure your samba server to use smb1. even linux has evolved beyond the old legacy stuff, so you have to force samba to use smb1.

the image is the conf setup that i used for setting up samba in POP Os
there are only 2 variables, the path to your share folder must be exactly as it is in your system.
Then the force user must be your user name for the linux pc .. mine is rocket. 
