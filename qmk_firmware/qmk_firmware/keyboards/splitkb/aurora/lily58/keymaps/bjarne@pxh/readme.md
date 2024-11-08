# Personal keyboard config

1. Set default keyboard to lily58:

`qmk config user.keyboard=splitkb/aurora/lily5`

2. Set default keymap to this one:

`qmk config user.keymap=bjarne@pxh.no`

3. Compile for liatris:

`qmk compile -e CONVERT_TO=liatris`

4. Enter bootloader: double press reset button.

5. Copy .uf2 file that was generated in 3 to the new disk.

