# BioShock 2 Multiplayer Unofficial DLC


## Features

1. **New Weapon - Melee Weapon**
   - This weapon utilizes your character's unique melee attack as a primary weapon.

2. **New Plasmid - Poison Quills**
   - Grants the unused plasmid Poison Quills which disables other players' plasmids for 10 seconds.

3. **New Tonics**
   - **Cold Punch**: Adds a freezing effect to your melee swings, allowing you to freeze enemies and turrets / vending machines.
   - **Fire Punch**: Adds a burning effect to your melee swings, setting enemies and objects on fire.
   - **Zap Punch**: Adds a stunning effect to your melee swings, stunning enemies.
   - **Adrenaline Eve**: Provides Eve in return for any damage taken in a 1-to-1 ratio.
   - **Super Health**: Grants 10 additional bonus health, allowing you to survive most one-shot attacks.

4. **New Loading Screen Thumbnail**
   - Fixes a Day 1 Bug with Mercury Suites where the Loading thumbnail incorrectly showcases the Apartment Lobby's thumbnail.
   - Now Showcases the proper thumbnail.

5. **New FOV Fix**
   - The included UserMP.ini now has a new FOV fix which will work 100% of the time and changes the FOV immediately once pressed.
   - Note: The ForegroundFOV still requires correct timing. But there are now more opportunities to trigger the fix before spawning.


## DLC Installation

1. **Read the DLC Known Issues** section below before starting.
2. **Backup Files:**
   - Backup `ConfigureLoadout.swf`, `SharedLibrary.swf`, and `Loading.swf` from `SteamLibrary\steamapps\common\BioShock 2\MP\Content\FlashMovies` by copying them to a new folder.
3. **Replace Files:**
   - Drag and drop the new `ConfigureLoadout.swf`, `SharedLibrary.swf`, and `Loading.swf` from the downloaded folder into the directory listed in step 1.
   - Click "Replace" on any existing files popup.
4. **Backup `UserMP.ini`:**
   - Backup your `UserMP.ini` file from `\AppData\Roaming\Bioshock2Steam` by copying it into a new folder.
5. **Replace `UserMP.ini`:**
   - Drag and drop the new `UserMP.ini` file to replace the existing file.
6. **Update `UserMP.ini`:**
   - Read the `USERMP` section below and make any changes to your `UserMP.ini`.
7. **Launch the Game.**
8. **Activate the DLC:**
   - Press '`' (tilde) at the main menu to activate the DLC (you will need to do this every time at launch).
9. **Confirm New Items:**
   - Check the Loadout menu to confirm the new items have been added.
10. **Need Help?**
    - If you have any questions or concerns, please join the Bioshock 2 Multiplayer Official Discord for help installing. [Bioshock 2 Multiplayer Discord Server](https://discord.gg/4ydTGHfFPQ)
11. **Wanna Uninstall the DLC?**
    - To uninstall the DLC and revert to the vanilla version, simply replace the downloaded files with your backups.
    - If this doesn't work, you can verify the integrity of the game files within your Steam library.
    - If verifying still does not work, you will need to reinstall the game.

## USERMP Configuration

1. **Re-apply Your Binds In-Game:**
   - After updating the UserMP.ini file, re-apply your binds within the game.

2. **Modify Sensitivity Settings:**
   - A new sensitivity modifier has been added to the `UserMP.ini` file. Search for `XSens` and `YSens` under the Aliases section.
     - Modifying these values will change your sensitivity globally.
     - The new default sensitivity has been changed from 2000.0 to 200.0. Modify both to your preference.

3. **Adjust Field of View (FOV) Settings:**
   - A new FOV modifier has been added and is bound to the `-` (minus) key and D-PAD Up on Controller, using console FOV values.
     - This includes an improved FOV fix, ensuring the FOV bind works correctly.
     - You can modify the FOV values by searching for `FOV` under the Aliases section.
     - `DesiredFOV` and `DefaultFOV` adjust the background (Map/World) FOV.
     - `ForegroundFOVAngle` and `DefaultForegroundFOV` adjust the foreground (Gun/Arms) FOV.
     - The background FOV modification is guaranteed to work, while the foreground FOV might still fail if not timed correctly.
     - The FOV values have been changed from 75/60 (PC FOV) to 75/70 (XBOX/PS3 FOV).

4. **Mouse Acceleration Fix:**
   - The mouse acceleration fix has been automatically applied to your `UserMP.ini` under the `MoveForward` alias.
     - This includes the `MouseAccelThreshold` and `MouseSmoothingMode` values.


# DLC Known Issues

1. **Game Crash with Poison Quills:**
   - Highlighting over Poison Quills in the Loadout Configurator will crash your game unless you trigger the DLC at least once with '`' (tilde).
     - The earliest point where you can trigger the bind is at the main menu with the BioShock 2 logo.
     - The promotional video does not trigger the binds.

2. **Melee Weapon Loadout Issue:**
   - You are unable to run the Melee Weapon by itself without having another primary weapon within the loadout.
     - This will cause no issues as the game will indicate your loadout is invalid beforehand. Simply give yourself another primary weapon to fix this.

3. **New Items Not Saving:**
   - The new items will not save into the loadout and will only save for the current session.
     - This is due to the game not having valid IDs for the given items, so it can't save across game launches.
     - They will remain in the loadout until you close the game.

4. **Elemental Melee Tonics Limitation:**
   - You cannot run multiple Elemental Melee Tonics (Cold Punch, Fire Punch, Zap Punch) simultaneously.
     - This is intended behavior as the game crashes if you try equipping more than one into your loadout.
     - The game will lock the other two tonics to prevent you from accidentally selecting more than one.

5. **Compatibility with Other Languages:**
   - The configuration does not work properly with other languages.
     - The new DLC Flash Files may break the game as I do not have access to SWF files for other languages.
     - Currently, only English is supported. User discretion is advised when attempting to use the DLC with non-English languages.


## Screenshots

### New DLC Items
![New Items In Loadout](https://github.com/SnowTempest/Bioshock-2-Multiplayer-DLC/blob/main/Screenshots/NewDLCItems.jpg)

### New DLC Items In-Game
![Poison Quills and the New Melee Weapon Primary](https://github.com/SnowTempest/Bioshock-2-Multiplayer-DLC/blob/main/Screenshots/PoisonQuills.jpg)

### Mercury Suites Thumbnail
![The Original Mercury Suites Thumbnail](https://github.com/SnowTempest/Bioshock-2-Multiplayer-DLC/blob/main/Screenshots/MercurySuitesThumbnail.jpg)
