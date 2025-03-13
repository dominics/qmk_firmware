# Dom's instructions for update

- Copy in new firmware zip file contents (or make changes to keymap.c manually), merge, commit
- Change the serial number in config.h so Keymapp will see the right layout (it downloads it from Oryx)
- make zsa/moonlander:dom
- Flash zsa_moonlander_dom.bin to the keyboard
