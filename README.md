# My dwm (dynamic window manager) build

Dwm is an extremely fast, small, and dynamic window manager for X. Dwm is created by the good folks at [suckless.org](https://suckless.org).  This is my personal build of dwm.  I used a number of patches in this build to make dwm more "sensible" rather than "suckless."  The patches I added to this build include:
+ alpha (for transparency)
+ attachaside (new clients appear in the stack rather than as the master)
+ cyclelayouts (cycles through the available layouts)
+ gridmode (adding a grid layout)
+ restartsig (allows dwm to be restarted with a keybinding)
+ rotatestack (moves a window through the stack, in either direction)
+ statuspadding (horizontal and vertical padding in the status bar are now configurable options)
+ uselessgap (adding gaps when more than one window)

# Dependencies
+ libxft
+ ttf-hack
+ ttf-joypixels
+ st
+ dmenu
+ tabbed

Also, you will need to add the following from the AUR:
+ nerd-fonts-complete (optional)
+ https://aur.archlinux.org/packages/libxft-bgra/ (needed for colored fonts and emojis)

Also, if you are building this on an Ubuntu-based system, you need to install libx11-dev and xorg-dev.
