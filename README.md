Sublime Text 2 & 3 Linux Bash Installer
=============================

A *really* simple bash installer for Sublime Text 2 & 3, to deploy (install/upgrade) it on Linux.
The bash script will check www.sublimetext.com/2 or /3, auto-grab the lastest build url depending your system (x86 or x86_64), download the tarball, unpack it, install it and create a .desktop file... all in one step.

It's a little ugly, but... it works. I'm not any bash-scripting master on Linux.
So, any comment, improvement or help is welcome.

## USAGE:
Download a copy of st2install (for Sublime Text 2) or st3install (for Sublime Text 3) to any location (your home folder, for example).

Then from a terminal run...
For Sublime Text 3:
```
sudo bash st3install
```
or
For Sublime Text 2:
```
sudo bash st2install
```


You can install both at the same time, they can live together without problems ;)

This can be used to upgrade and existing Sublime Text 2 or 3 installation made by the same script.
No more upgrade worries ;)

Tested on Ubuntu/Xubuntu 12.10

## License

All source code is released under the open source [WTFPL license](http://en.wikipedia.org/wiki/WTFPL).
