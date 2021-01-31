# dwm
My dwm build. Really novice one, I`m still working on it. Basically just a bunch of patches and keybinds.

## Requirements
* All the colors used in this build are obtained from pywal, a tool written in python to get a color pallet and apply it on your system. There is already a patch that takes the xrdb colors and apply it to dwm but I find pywal`s versatility and speed to grab new color schemes really useful and fun. If you`re using an arch based distro just get it from:
```
$ sudo pacman -S python-pywal
```
* I have a bind for ranger, really powerful and minimalist vim-based file manager (also written in python).
* Browser is Firefox
I plan to just add those binds to some variables who are easier to modify in case of different preferences on broswer, file manager and other programs.

## Patches
* vanitygaps
* restartsig
