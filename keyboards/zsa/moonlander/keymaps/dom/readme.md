# Dom's instructions for update

- Copy in new firmware zip file contents (or make changes to keymap.c manually), merge, commit
- Change the serial number in `config.h` so Keymapp will see the right layout (it downloads it from Oryx)
- `make zsa/moonlander/reva:dom` for black Moonlander, and `make zsa/moonlander/revb:dom` for white Moonlander
- Flash `zsa_moonlander_revx_dom.bin` to the keyboard
