# Team Fortress 2 Configuration Files
*My Team Fortress 2 custom configuration files.*

## Installation
Click [Here](https://github.com/JAH94/tf2-config/releases/latest) for the latest release -> `Source code (zip)`.  
Extract the ZIP file and Copy and Paste the folders contents into `tf\custom`, found in the `Team Fortress 2` folder.  
Inside `tf\custom` should be the file `base_configuration.vpk` and the folder `user_configuration`.

## Config Features
* **Auto Crouch-Jump:** Automatically crouch-jump when pressing the spacebar.
* **Class Viewmodel:** Displays a viewmodel based on the class and its weapon.
* **Custom Closed Captions:** Uses custom closed captions to display text on screen. e.g.: Soldier's Rocket Jump script is on/off.
* **Debug Console Output:** Displays output of user configuration settings in the developer console.
* **Function Key Class Switcher:** Uses the function keys F1 through F9 to quickly switch class.
* **Graphics Switcher:** Switches between quality presets or a user customisable one.
* **Loutout Switcher:** Binds `ALT` + keys 1 through 4 to switch loadouts.
* **Medic/Über Switch:** Switches between Medic or Übercharge based on if `SHIFT` is being held down or not.
* **Null Cancelling Movemen:** Lets you immediately change direction.
* **Viewmodel Toggling:** Toggles the display of the active weapons' viewmodel by pressing the `DELETE` key.
* **Wait Tester:** Checks to see if the server has the wait command enabled.
* **Zoom In/Out:** Zoom in/out by pressing `F`.

## Class Specific Features
* **Soldier: Rocket Jump:** A simple rocket jump script that doesn't use the wait command but still provides a decent jump. Jump script bound to `MOUSE2` when toggled on (use `R` to toggle).
* **Engineer: Quick Build/Destory:** Binds keys 6 through 9 to the Engineer's buildings, automatically destroying any existing buildings when pressed. You can also disable the PDAs; doing so will shift the building bindings keys from 6-9 to 4-7.
* **Engineer: Eureka Effect Teleport:** Press `Q` to go to spawn. Hold `SHIFT` and Press `Q` to go to the teleporter exit.
* **Medic: Move Spawn Location:** Changes your loadout to its second preset, then back to your first. Pressing `F4` twice to move spawn.
* **Spy: Taunt:** Automatically declocks the spy before performing a taunt. Bound to `G`.
* **Spy: Keypad Disguise:** Quickly disguide as a class by pressing `1-9` on the keypad. Pressing the `DELETE` keypad key will switch teams (Default is RED).
* **Spy: Auto Disguise:** Automatically disguises the Spy when clicking `MOUSE1`. If this is not desirable, use `MOUSE3` to perform a normal left-click. Press `R` at any time to disable all auto disguise functions. This script also automatically changes the disguise's current weapon when switching weapons.

## Settings
The config comes with several user editable settings; edit them in `user_configuration\cfg\user\settings.cfg`:
* `AUTO_CROUCH_JUMP`
* `CLEAR_CONSOLE_ON_START`
* `CONSOLE_FILTER`
* `CUSTOM_CLOSED_CAPTIONS`
* `DEBUG_CONSOLE_OUTPUT`
* `DEV_INFO`
* `DOWNLOAD_FILES`
* `FUNCTION_KEYS_CLASS_SWITCHER`
* `GRAPHICS_CONFIG_SWITCHER`
* `LOADOUT_SWITCH`
* `MUSIC_PLAYER_CLASSES`
* `NULL_CANCELLING`
* `OPTIMISE_OPENGL`
* `PACKET_RATE`
* `PACKET_SIZE`
* `SHOW_NETGRAPH`
* `SNAPSHOTS`
* `SUICIDE`
* `VIEWMODEL_TOGGLING`
* `WAIT_TESTER`
* `ZOOM_IN_HIDE_WEAPON`
* `ZOOM_IN_SENSITIVITY`
* `ZOOM_OUT_SENSITIVITY`

For class-specific config settings you can find them in the folder `user_configuration\cfg\class`:
* `CLASS_SPECIFIC_BINDS`
* `CLASS_VIEWMODEL`
* `DISGUISED_WEAPON_SWITCHING`
* `ENGINEER_PDA`
* `EUREKA_EFFECT`
* `KEYPAD_DISGUISE`
* `MOVE_SPAWN_LOCATION`
* `SOLDIER_ROCKET_JUMP`
* `SPY_AUTO_DISGUISE`
* `SPY_TAUNT`

## Mods (Recommended)
* [Disable Incoming Message](https://drive.google.com/file/d/12EYvAGVP4W4OX7dves0kpylp-4v2ioCB/view)
    * Removes Miss Pauling's voice lines for quests.
    * Removes the incoming message HUD panel.
* [No Hats Mod](https://github.com/Fedora31/no-hats-bgum/tree/master) removes cosmetics and other things, such as: 
    * `no_botkiller.vpk` Removes Botkiller Weapons.
    * `no_bugged_misc.vpk` Removes bugged Miscs.
    * `no_christmas_light.vpk` Removes Christmas Festiviziers *NOT* Festive Weapons.
    * `no_hats_bgum.vpk` Removes Hats.
    * `no_skins.vpk` Removes Skins.
    * `no_unusuals.vpk` Removes Unsuals.
    * `no_zombie_skins.vpk` Removes Zombie Skins.

## Mods (Optional)
* [Old Sticky Jumper and Rocket Jumper Skins](https://gamebanana.com/mods/198851)
* [70 FOV Fix Pack](https://gamebanana.com/mods/198862) **Note:** Doesn't work on Valve servers.
* [Missing Killicons Pack](https://steamcommunity.com/sharedfiles/filedetails/?id=2156604959)
* [Improved and Aligned Medic Heal Beam](https://gamebanana.com/mods/12020)

## Credits
* Config based on [Lyrositor](https://github.com/Lyrositor)'s [TF2 Scripts](https://github.com/Lyrositor/TF2-Scripts).
* [Team Fortress 2 Wiki](http://wiki.teamfortress.com) for their scripting tutorials.
* [clovervidia](https://steamcommunity.com/id/clovervidia) for their [Close Captions in TF2](https://steamcommunity.com/sharedfiles/filedetails/?id=167785751s) guide.
* [Dewgmztv](https://gamebanana.com/members/1432181)'s [Toggle Auto Disguise on attack](https://gamebanana.com/scripts/8925) spy script.
* [TheFifthWheel](https://gamebanana.com/members/1350351)'s [TF2 Jukebox Script](https://gamebanana.com/scripts/8268).
* [Tiagoquix](https://gamebanana.com/members/1543592)'s [Null-Cancelling Movement](https://gamebanana.com/scripts/9842) script.