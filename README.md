# My Personal Build of St

This build of the suckless terminal has been expanded upon to match my personal, opinionated
preferences &mdash; suckless philosophy be damned.

# Patches

- [Alpha](https://st.suckless.org/patches/alpha/): Transparency for the terminal
- [Alpha-focus-highlight](https://st.suckless.org/patches/alpha_focus_highlight/): Distinguish between focused and unfocused windows via two distinct opacity values
- [Anysize](https://st.suckless.org/patches/anysize/): Allow st to be rendered at any pixel size
- [Blinking cursor](https://st.suckless.org/patches/blinking_cursor/): Set blinking cursor
- [Bold is not Bright](https://st.suckless.org/patches/bold-is-not-bright/): Bold text is rendered as bold, leaving color unaffected.
- [Boxdraw](https://st.suckless.org/patches/boxdraw/): Adds special box-drawing characters for cleaner graphics
- [Columns](https://github.com/bakkeby/st-flexipatch/issues/34): Allow st to be resized without cutting off text. Doesn't work for vertical?
- [Font2](https://st.suckless.org/patches/font2/): Set backup fonts besides the default
- [Wide-Glyph Support](https://github.com/Dreomite/st/commit/e3b821dcb3511d60341dec35ee05a4a0abfef7f2): Workaround for Nerd Font glyphs to not get cut off
- [Ligatures](https://st.suckless.org/patches/ligatures/): Ligature support via Harfbuzz library
- [Scrollback](https://st.suckless.org/patches/scrollback/): Scroll back through terminal with `Alt+j / Alt+k` or mouse wheel
- [Selection colors](https://st.suckless.org/patches/selectioncolors/): Adds *selectionfg* and *selectionbg* to define fore- and background colors when selecting text with the mouse
- [Undercurl](https://st.suckless.org/patches/undercurl/): Undercurl support for programs which support it

# Dependencies

- [libxft-git](https://aur.archlinux.org/packages/libxft-git)
- [harfbuzz](https://archlinux.org/packages/extra/x86_64/harfbuzz/)
