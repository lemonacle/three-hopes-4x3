# Three Hopes 4:3

A 4:3 patch for **Fire Emblem Warriors: Three Hopes** on Switch emulators. It targets a 1280×960 display and was tested in Eden Nightly.

## Install

1. Install the game's **1.0.2** update and download the mod ZIP. [Latest release](https://github.com/lemonacle/three-hopes-4x3/releases/latest)
2. Import the ZIP in Eden, or extract the `Three Hopes 4x3` folder into the game's mod data folder. The patch should sit at `Three Hopes 4x3/exefs/1.0.2.pchtxt`.
3. Enable the mod, disable competing aspect-ratio or resolution mods, and set Eden to **4:3**, **Docked**, and **1×** resolution. Restart the game.

To revert, disable the mod and restart the game.

## What the patch changes

- Adapts the gameplay view and selected menus to a 4:3 frame.
- Anchors the battle and camp HUD, dialogue, and map overlays to the appropriate edges.
- Center-crops the shared pre-battle and Battle Results backdrop to fill the frame.
- Preserves letterboxing for chapter title cards and videos.

## Compatibility

| Setting | Value |
| --- | --- |
| Game version | `1.0.2` |
| Title ID | `010071F0143EA000` |
| Main NSO build ID | `F62A7D41CAAC7D6D22D5E1384CEE3720C12D7D02` |
| Tested configuration | Eden Nightly, Docked, 1×, 4:3 |

The first public release follows nearly five hours of in-game testing. Coverage on other emulator configurations and native Switch hardware is unverified.

The release contains an IPSwitch patch and requires your own copy of the game.
