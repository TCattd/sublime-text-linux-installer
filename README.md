Sublime Text Linux Installer
=============================

A *really* simple bash installer for Sublime Text, to deploy it (install/upgrade) on Linux.
The script will check sublimetext.com downloads, auto-grab the lastest build url depending your system (x86 or x86_64), download the tarball, unpack it, install it and create a .desktop file... all in one step.

It's a little ugly, but... it works. I'm not any bash-scripting master on Linux.
So, any comment, improvement or help is always welcome.

## USAGE:
Download a copy of stinstall (for Sublime Text), st2install (for Sublime Text 2) or st3install (for Sublime Text 3) to any location (your home folder, for example).

Then from a terminal run...

```
chmod +x ./stinstall && sudo ./stinstall
```

This same script can be used to upgrade an existing Sublime Text installation made by the same script.
Just re-run the same install process. Sublime Text will be upgraded automatically to lastest version available on sublime text's web, and none of your settings will be lost (there're located on your home folder, and this installer will not touch those folders).

No more upgrade worries ;)

Tested on Ubuntu/Xubuntu 13.04/13.10/14.04 and Fedora 19/20

You can comment about this script on: https://forum.sublimetext.com/t/sublime-text-3-2-install-script-for-linux/9003

## License

All source code is released under the open source [MIT license](http://choosealicense.com/licenses/mit/).
