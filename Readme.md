<img width="902" height="243" alt="banner" src="https://github.com/user-attachments/assets/e0752819-14d6-491c-866d-1c5be08bf07d" />

# Better Wii Menu - macOS Edition

A custom Dolphin build for macOS that lets disc image files (.rvz, .iso, .wbfs, .gcz, .ciso, .wia) work as channels on the Wii System Menu.

Switching between games has never been easier!

> This is the macOS port of [Better Wii Menu DE](https://github.com/Gavin-S-Dev/Better-Wii-Menu-DE) by Gavin S Dev.

### Features

- Automatically syncs your Dolphin game library with the Wii Menu

- Switching between games is now possible with only the Wii Remote

- Right-click any game in the Dolphin game list to manually add or remove it from the Wii Menu

- **Toolbar "Wii Menu" button** — launch the Wii System Menu instantly from the main toolbar without navigating menus

- **Riivolution / GameModDescriptor support** — `.json` mod descriptor files can be added as their own unique Wii Menu channels, so modded versions of a game launch with Riivolution patches applied automatically

- Visually replicates the same experience as if game files are .wad on the Wii Menu

- Only games with a valid animated banner (`opening.bnr`) can be installed as channels — invalid discs are blocked with a clear error rather than crashing the Wii Menu

### How to use
1. Download and open the `.dmg`
2. Drag **Dolphin** into your Applications folder
3. Launch Dolphin, then click **Wii Menu** in the toolbar (or go to Tools → Load Wii System Menu)
4. Your game library will sync automatically — enjoy easier game switching!

### Requirements

- macOS 12 Monterey or later (Apple Silicon and Intel supported)
- A Wii NAND dump and keys (required by Dolphin for Wii Menu functionality)
