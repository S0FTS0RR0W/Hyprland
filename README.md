# Dotfiles Installation

## Thunar Custom Actions

This repository contains configuration for **Thunar** file manager custom actions.

### File: `Thunar/uca.xml`

This configuration adds an **"Open Terminal Here"** action to the context menu within Thunar. It uses `exo-open` to launch the default terminal emulator in the current directory.

**Prerequisites:**
- `thunar`: The file manager.
- `exo`: Provides the `exo-open` utility.

### Installation

1.  **Backup your existing configuration** (optional but recommended):
    ```bash
    cp ~/.config/Thunar/uca.xml ~/.config/Thunar/uca.xml.bak 2>/dev/null || true
    ```

2.  **Install the configuration file**:
    ```bash
    mkdir -p ~/.config/Thunar
    cp Thunar/uca.xml ~/.config/Thunar/uca.xml
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