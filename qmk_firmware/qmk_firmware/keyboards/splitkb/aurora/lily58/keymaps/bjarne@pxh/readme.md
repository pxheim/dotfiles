# Personal keyboard config

1. Set default keyboard to lily58:

`qmk config user.keyboard=splitkb/aurora/lily5`

2. Set default keymap to this one:

`qmk config user.keymap=bjarne@pxh.no`

3. Compile for liatris:

`qmk compile -e CONVERT_TO=liatris`

4. Flash for liatris:

`qmk flash -e CONVERT_TO=liatris`

