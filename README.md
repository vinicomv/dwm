# dwm
My dwm build. Really novice one, I`m still working on it. Basically just a bunch of patches and keybinds.

## Requirements
* All the colors used in this build are obtained from pywal, a tool written in python to get a color pallet and apply it on your system. There is already a patch that takes the xrdb colors and apply it to dwm but in my opinion pywal has a lot of versatility and speed to grab new color schemes. If you`re using an arch based distro just get it from:
```
$ sudo pacman -S python-pywal
```
* I have a bind for ranger, really powerful and minimalist vim-based file manager (also written in python).
* Terminal, as probably expected, is st.
* My default browser is Brave. As redundant as it sounds having two "Chromium based browsers", there is also a bind to Chromium since I have to use it sometimes.
* I have put binds for steam and discord since I use them quite a lot. I am aware many people do not use or like those applications, so just cut them out or change them if you do not feel like using it.
* There is also a bind for pavucontrol. Honestly I feel like this is one of the most useful applications to have binded to a key.
* I am using Font Awesome on it as you can notice in the config. It is mainly due the fact that I use some font awesome characters in my dwmblocks statusbar.

I plan to just add those binds to some variables who are easier to modify in case of different preferences on broswer, file manager and other programs.


## Patches
* vanitygaps (I find the gaps aesthetically pleasant and really good to give your desktop a more organized feeling).
* restartsig (to restart dwm withou having to kill and startx everytime, useful for testing pywal color schemes and patches).
* actualfullscreen (just as the name says, an actual fullscreen patch).
