# Dotfiles Installation

## Overview

This repository contains configuration files (dotfiles) for your system.

### Installation

1.  **Backup your existing configuration** (optional but recommended):
    ```bash
    cp -r ~/.config ~/.config.bak
    ```

2.  **Install the configuration files**:
    ```bash
    cp -r * ~/.config/
    ```

3.  **Apply changes**:
    Restart Thunar to load the new actions.
    ```bash
    thunar -q
    ```

4. **Set up Swww**:
   Apply wallpaper.
   ```bash
   swww img ~/Pictures/wallpaper.png
   ```

### Use optional install.sh.
   ```bash
   ./install.sh
   ```

### Install dependencies (Arch Linux)
    sudo pacman -S kitty hyprland swww rofi brightnessctl nwg-displays fastfetch btop waybar cava thunar hyprlock
