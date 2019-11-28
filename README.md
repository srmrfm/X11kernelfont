# X11kernelfont
It looks like a standard linux kernel font, but works in X11 and aims for full unicode support.
Chromium won't use it (bitmap fonts not supported?), but it works with i3bar, dmenu, rofi, and
every terminal emulator I tried. Nearly all glyphs are straight from /usr/share/consolefonts.

standard ascii: DONE

M$DOS extended ascii/cp437: DONE

Cyrillic: mostly complete, needs further testing

Extended latin charset: complete (iirc), needs testing.

Hebrew: incomplete(missing characters probably rarely used), needs testing

Greek: incomplete(missing characters probably rarely used), needs testing

Box drawing etc.: good enough for Midnight Commander, but glyphs not present in consolefonts may be missing.

Mathematical symbols: very incomplete, need help

Bold and Italic: WIP, likely to be latin-only for readability reasons. Files currently lost.

Emoji: Contributions welcome!

Misc unicode: eventually

Truetype: lol no... OK, maybe.
