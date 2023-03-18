# Inventory Filter mod for Fallout 2

A mirror repository of the Inventory Filter mod for Fallout 2 by Mr.Stalin, based on the idea of JimTheDinosaur's [Inventory Sort Buttons mod](https://www.nma-fallout.com/threads/inventory-sort-buttons-mod.203180).

## Features
* Quickly find ammo for weapons from tons of junk in the inventory: if you click the middle mouse button on the "Weapons" and "Ammo" menu buttons, these items will be displayed simultaneously in the player's inventory.
* Money is always shown at the top when bartering, or if the "All" filter is selected (the feature does not work right after opening the inventory).
* Quickly exchange your party members when bartering or opening containers.
* Displays the weight value for items in the selected category, as well as the amount of money the merchant has in barter.
* The **"Drop All"** button.
* Hotkeys to switch between the selected categories.

## Installation
1. Download `F2-InventoryFilter_v*_<language>.rar` from the [release archive](archive).
2. Extract the `mods` folder to your main game directory.
3. Inventory Filter v2.0.2 requires [**sfall**](https://github.com/sfall-team/sfall) (`ddraw.dll`) version 4.2.8.1/3.8.37 or later. The **AllowUnsafeScripting** option in `ddraw.ini` must be enabled for the filter to function correctly.
4. Edit `mods/InventoryFilter.dat/InvenFilter.ini` to configure the behavior of the filter.

This is how it's supposed to look like when installed:
![installed](pics/installed.png)

* Note for the hi-res patch by Mash: DirectDraw 7 graphics mode is known to cause some display glitches with the filter. It is recommended to use **DirectX 9** mode.
* Note for sfall 3.8.38+: The path to the mod folder needs to be set in the **[ExtraPatches]** section in `ddraw.ini`. Add `PatchFile[number]=mods\InventoryFilter.dat` at the end of the "PatchFile" list. If there are more than one additional mod, make sure to correctly number the "PatchFileX" entries (0, 1, 2, 3, ...).

## Usage Notes
* Click the middle mouse button on the "Weapons" and "Ammo" menu buttons to display items from these categories simultaneously in the player's inventory. Also, clicking the middle mouse button on the "Weapons" menu button will display only the "Guns" type of weapons.
* To quickly switch between filter categories, use the hotkeys:
  ```
  Player: Q, 1, 2, 3, 4, 5
  NPC:    W, 6, 7, 8, 9, 0
  ```
  You can change the hotkeys in `InvenFilter.ini`.
* To turn the filter on or off, use the F11 key.

## Uninstallation
Delete `mods/InventoryFilter.dat` folder.

## Screenshots
![Player's inventory](pics/scr_player_inv.png)

![Opening containers](pics/scr_loot.png)

![Barter screen](pics/scr_barter.png)
