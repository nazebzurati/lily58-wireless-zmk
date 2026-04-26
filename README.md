# Lily58 Wireless ZMK

Custom ZMK firmware for Lily58 featuring a central dongle with a Prospector display.

## Keymap
Located at `config/lily58.keymap`:
- **Base**: Standard QWERTY.
- **Func**: Navigation, Function keys, and Studio Unlock.

## Building & Flashing
Builds are automated via GitHub Actions.

1. **Download**: Get the latest artifacts from the `Build` action.
2. **Bootloader**:
   - **Split Halves**: Double-tap the reset button (connected via USB).
   - **Dongle**: Short `GND` + `RESET` twice.
3. **Flash**: Drag the appropriate `.uf2` file to the `NICENANO` drive.

> [!IMPORTANT]
> Controllers reboot immediately after receiving a `.uf2`. Copy files one at a time.
