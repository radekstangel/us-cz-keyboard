# English keyboard with Czech dead keys

English keyboard layout with Czech special characters accessible via AltGr (right alt)

## Installation (tested on Ubuntu Linux)

1. Insert the content of altgr-cz file  to /usr/share/X11/xkb/symbols/us (or wherever your OS stored keyboard layouts)
2. Edit files /usr/share/X11/xkb/rules/xorg.lst and /usr/share/X11/xkb/rules/evdev.xml and add altgr-cz variant (should be self-explanatory)
3. Go to your OS settings and choose the new keyboard layout
