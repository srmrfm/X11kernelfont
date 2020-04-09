# X11kernelfont
It looks like a standard linux kernel font, but works in X11 and aims for full unicode support.
Chromium won't use it (bitmap fonts not supported?), but it works with i3bar, dmenu, rofi, and
every terminal emulator I tried. Nearly all glyphs are straight from /usr/share/consolefonts.

Note: Using the .bdf version is *highly* recommended on capable systems, it's much sharper than the OpenType (.otb) 
version, which is quite blurry. I will try to fix this, but I suspect it is a problem with OpenType bitmap fonts, or 
possibly a font render issue. This may take some time, as I am unfamiliar with Opentype and with the .otb format.


standard ascii: DONE

M$DOS extended ascii/cp437: DONE

Cyrillic: mostly complete, needs further testing

Extended latin charset: complete (iirc), needs testing.

Hebrew: incomplete(missing characters probably rarely used), needs testing

Greek: incomplete(missing characters probably rarely used), needs testing

Box drawing etc.: good enough for Midnight Commander, but glyphs not present in consolefonts may be missing.

Mathematical symbols: very incomplete, need help

Bold and Italic: Use the OpenType version if you really need these, the .bdf ones are WIP and likely to be 
latin-only for readability reasons. Files currently lost.

Emoji: Contributions welcome!

Misc unicode: eventually

Truetype: ~~lol no... OK, maybe.~~ Assimilated by the OpenType Collective.
