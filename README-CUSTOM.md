this is v3 corne! (or lower)

install qmk, might hang so fix somehow (uv python is enough) + system deps

qmk env to validate

make git-submodule

qmk setup

edit keymap/vial/rules.mk

qmk compile -kb crkbd/rev1 -km vial -e CONVERT_TO=rp2040_ce

unplug second half

enter bootloader:
- hold q/p and plug power
- hold boot button (reset is hidden?) and plug power
- 2x reset button (but is hidden?)

flash by drag&drop 

repeat for second half (always)
