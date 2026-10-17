# AoE III DE Unlocker — Portraits & Level

An in-game panel for **Age of Empires III: Definitive Edition** that unlocks all profile portraits and sets your Home City level.

**Download:** grab the latest `AoE3-Portrait-Unlocker.zip` from the [Releases](../../releases) page.

## Features

- **Portraits:** permanently unlocks every profile portrait and saves it to your profile.
- **Home City level:** set any level from 1 to 999,999,999 for all civs or a single civ. The required XP and a correct checksum are written for you.
- In-game overlay panel: press **Insert** to show / hide it; it never steals focus from the game.

## Requirements

- Windows 10/11, 64-bit
- Age of Empires III: Definitive Edition (Steam)
- The game in **windowed** or **borderless** mode. In exclusive fullscreen the panel can't appear on top.

## How to use

1. Start the game and go to the **main menu**.
2. Run `AoE3-Portrait-Unlocker.exe`. It finds the game, loads the panel, and closes itself after a few seconds.
3. In the game, press **Insert** to open the panel.
4. **Portraits** tab → **Permanent + Save** (click twice to confirm).
5. **Home City** tab → pick a level (buttons, mouse wheel, or click the number and type it). Optionally pick a civ, then **Apply level** (click twice to confirm).
6. Restart the game to see the new Home City level.

If the game runs as administrator, run the unlocker as administrator too.

| Key | Action |
|---|---|
| Insert | Show / hide the panel |
| F8 | Permanent portrait unlock + save |
| End | Remove the panel from the game |

## Backups & restoring

- Before the first portrait save, your profile is backed up as `jrgb.to.bak` next to the original.
- Before the first level change, each Home City file is backed up as `<file>.orig`.
- To restore, close the game and replace the modified file with its backup (remove the read-only flag first if needed).

Home City files are marked **read-only** after a level change so the game doesn't write the old level back. Clear the read-only flag in the file's properties if you want the game to save normally again.

## Notes

- Some antivirus programs flag tools that load code into another process. This is a false positive caused by how the panel is loaded into the game. If you're unsure, don't run it.
- Single-player profile modification. **Use at your own risk** and keep your backups.
- Not affiliated with or endorsed by Microsoft, World's Edge, or Forgotten Empires.

---
Made by **Gökbörü**
