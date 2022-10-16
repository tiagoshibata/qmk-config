Building keymap: `qmk compile lily58-rev1-tiagoshibata-colemak.json`

Flashing:

```
sudo dfu-programmer atmega32u4 erase --force
sudo dfu-programmer atmega32u4 flash --force ~/src/qmk-config/lily58_rev1_tiagoshibata-colemak.hex
sudo dfu-programmer atmega32u4 reset
```
