# dwm
My dwm build. Really novice one, I`m still working on it. Basically just a bunch of patches and keybinds.

## Requirements
* All the colors used in this build are obtained from pywal, a tool written in python to get a color pallet and apply it on your system. There is already a patch that takes the xrdb colors and apply it to dwm but in my opinion pywal has a lot of versatility and speed to grab new color schemes. If you are using an arch based distro just get it from:
```
$ sudo pacman -S python-pywal
```
* Terminal, as probably expected, is st.
* I mainly use SXHKD for my key binds, mantaining dwm only with essential binds, such as terminal and dmenu.
* All tags are organized per function, and I keep tag masks for specific programs.

note to myself: edit the paths in config.h so it works univerally.

## Patches
* vanitygaps (I find the gaps aesthetically pleasant and really good to give your desktop a more organized feeling).
* restartsig (to restart dwm withou having to kill and startx everytime, useful for testing pywal color schemes and patches).
* actualfullscreen (just as the name says, an actual fullscreen patch).
* pertag (so I can have specific layouts for specific tags)
* statusbar padding
* preserveonrestart (preservers window layout after restarting)
