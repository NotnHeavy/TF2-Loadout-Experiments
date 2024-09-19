# (TF2) Loadout Experiment
Akin to [Shounic's experiment video](https://www.youtube.com/watch?v=OjHOAfHokqk), this plugin lets you equip any weapon for any class per command. By default, only weapons for their designated slot are allowed, however you may tweak the `loadout_allslots` keyword to allow any weapon in any slot. You can use this plugin by using the commands associated with the [Weapon Manager plugin](https://github.com/NotnHeavy/TF2-Weapon-Manager/).

## How to install
Just download the `.zip` archive and extract it to your SourceMod directory. In order to load the `Weapon Manager` config file without having it set in `weapon_manager.cfg`, you will need to type `weapon_load "NotnHeavy - Loadout Experiment"` and then `weapon_save` to save to your `autosave.cfg` file.

In order to tweak weapons for other classes, it is recommended that you use this plugin alongside [Weapon Fixes](https://github.com/NotnHeavy/TF2-Weapon-Fixes).

## Dependencies
This plugin is compiled using SourceMod 1.12, but should work under SourceMod 1.11.

The following external dependencies are mandatory for this plugin to function:
- [NotnHeavy's Weapon Manager (and its dependencies)](https://github.com/NotnHeavy/TF2-Weapon-Manager)
- [nosoop's TF2 Econ Data](https://github.com/nosoop/SM-TFEconData)