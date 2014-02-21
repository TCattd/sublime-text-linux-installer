Sublime Text 2 & 3 Linux Installer
=============================

A *really* simple bash installer for Sublime Text 2 & 3, to deploy (install/upgrade) it on Linux.
The script will check www.sublimetext.com/2 or /3, auto-grab the lastest build url depending your system (x86 or x86_64), download the tarball, unpack it, install it and create a .desktop file... all in one step.
It also will autoinstall wbond's Package Control (https://sublime.wbond.net/) for you ;)

It's a little ugly, but... it works. I'm not any bash-scripting master on Linux.
So, any comment, improvement or help is welcome.

## USAGE:
Download a copy of st2install (for Sublime Text 2) or st3install (for Sublime Text 3; st3devinstall for Sublime Text 3 DEV) to any location (your home folder, for example).

Then from a terminal run...

For Sublime Text 3:
```
chmod +x ./st3install && sudo ./st3install
```

Sublime Text 3 DEV
```
chmod +x ./st3installdev && sudo ./st3installdev
```

or

For Sublime Text 2:
```
chmod +x ./st2install && sudo ./st2install
```


You can install both at the same time, they can live together without problems ;)

This can be used to upgrade and existing Sublime Text 2 or 3 installation made by the same script.
Just re-run the same install process. Sublime Text (2 or 3) will be upgraded automatically to lastest version on sublime's web, and none of your settings will be lost (there're located on your home folder, and this installer will not touch those folders).
No more upgrade worries ;)

Tested on Ubuntu/Xubuntu 13.04/13.10/14.04 and Fedora 19/20

You can comment about this script on: http://www.sublimetext.com/forum/viewtopic.php?f=5&t=11231

## License

All source code is released under the open source [WTFPL license](http://en.wikipedia.org/wiki/WTFPL).
