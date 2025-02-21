# Endgame

This is my rmk configuration for the engame keyboard

# RMK

RMK is a feature-rich and easy-to-use keyboard firmware.

## Use the template

1. Install [probe-rs](https://github.com/probe-rs/probe-rs)

   ```shell
   # Linux/macOS
   curl --proto '=https' --tlsv1.2 -LsSf https://github.com/probe-rs/probe-rs/releases/latest/download/probe-rs-tools-installer.sh | sh

   # Windows
   irm https://github.com/probe-rs/probe-rs/releases/latest/download/probe-rs-tools-installer.ps1 | iex
   ```

2. Build the firmware

   ```shell
   cargo make uf2 --release
   ```

3. Drag and drop the `Endgame.uf2` firmware to rp2040
