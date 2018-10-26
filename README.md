# English keyboard with Czech dead keys

English keyboard layout with Czech specific characters accessible via AltGr (right alt). This layout is suitable for programmers since it doesn't block symbols above the number keys.

## Usage

- AltGr+{letter} => á, é, í, ó, ú, č, ď, ň, ř, š, ť, ž
- AltGr+F => ě
- AltGr+V => ů
- AltGr+5 => €

For capital letters add Shift modifier as usual.

## Installation

Tested on Ubuntu/Gnome but should work on most Linux distributions. On Mac and Win it can be done too, [duckduckgo](https://duckduckgo.com/) for it :-)

1. Insert the content of `altgr-cz` file  into `/usr/share/X11/xkb/symbols/us` (or wherever your OS stores keyboard layouts)
2. Edit files `/usr/share/X11/xkb/rules/xorg.lst` and `/usr/share/X11/xkb/rules/evdev.xml` and add altgr-cz variant (it is self-explanatory)
3. Go to your OS settings and choose the new keyboard layout
