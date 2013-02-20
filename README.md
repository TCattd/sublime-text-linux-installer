sublime-text-3-bash-installer
=============================

Sublime Text 3 Ubuntu/Linux Bash Installer

A *really* simple bash installer for Sublime Text 3, to deploy (install/upgrade) it on Ubuntu/Linux.
The bash script will check www.sublimetext.com/3, auto-grab the lastest build url depending your system (x86 or x86_64), download the tarball, unpack it, install it and create a .desktop file... all in one step.

It's a little ugly, but... it works. I'm not any bash-scripting master on Linux.
So, any comment, improvement or help is welcome.

## USAGE:
```
sudo bash st3install
```

This can be used to upgrade and existing Sublime Text 3 installation made by the same script.
No more upgrade worries ;)

Tested on Ubuntu/Xubuntu 12.10

## License

All source code is released under the open source [WTFPL license](http://en.wikipedia.org/wiki/WTFPL).
