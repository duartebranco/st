# duarte's st build

This is my personal build of st (simple terminal), forked from Luke Smith's build, with several patches and customizations applied.

You probably should make your own builds, since it's in the "suckless" mindset to know your programs and have only exactly what you want in them.

## Patches / Changes Included

- **Custom fonts:** Uses `Liberation Mono` at a larger default size and includes `NotoColorEmoji` and `FiraCode Nerd Font` for full emoji and programming ligature support.
- **Keybindings:** Reworked/modded keybindings for zoom (font size), scrollback, alpha adjustment, copy/paste, and more. Notably, some key combinations differ from Luke’s defaults.
- **Scrollback:** Scrollback patch with mouse and keyboard (Shift+PageUp/PageDown and Ctrl+Shift+J/K, etc).
- **Alpha/transparency:** Easy runtime adjustment and Xresources support.
- **Boxdraw and ligatures:** Full boxdraw/ligature support enabled.
- **Color scheme:** Still uses Gruvbox by default, with full Xresources and pywal compatibility.
- **Minimal border:** Thin border for a modern look.

(See the source and `config.h` for details.)

## Compilation

To build and install st, run:

```
make clean install
```

You might need to use `sudo` for installation.
