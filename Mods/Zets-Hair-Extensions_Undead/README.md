# Zetsukaze's Hair Extensions
Hehe pun intended. Created to fix the Hairs+ mod for DeadPeopleTileset. Also, the terrible formatting was bugging me :man_shrugging:

# Dependencies
Requires [DeadPeopleTileset](https://github.com/SomeDeadGuy/Cata-MSX-DeadPeopleTileset). It's a great tileset! Try it out :satisfied:

# Usage Guide
This mod can be enabled mid-game, however you will need to debug in features for yourself and any existing NPCs. New NPCs will have their own features!
1. Unzip the downloaded file and copy the mod folder into `<CDDAInstallationFolder>\data\mods`
2. Enable in CDDA `Zetsukaze's Hair Extensions` and enjoy the variety of hairs, eyes and skins!

## Optional Steps
3. For mod support, extract the addon ZIPs of the mods you play with and enable them in CDDA
4. To enable *\~Kawaii\~* features, extract `Zets-Hair-Jp-Features`, cut and paste over the existing 3 `jp_*.json` files in the main mod folder

For example, if you play with [PKs Rebalancing](https://github.com/dissociativity/PKs_Rebalancing), then unzip the folder `Zets-Hair-PK-Rebalancing.zip` and enable `Zet's Hair - PKs Rebalancing` in CDDA. Easy right?

The Japanese features will still be available through debug if step 4 is not done, however they will not be available for selection for character creation.

## Info
Weighted chances of hair, eye and skin colour based on ethnicity statistics. If you have more accurate data statistics that I could use, please do share!
* [Race Statistics](https://statisticalatlas.com/division/New-England/Race-and-Ethnicity)
* [Hair and Eye Colour](http://www.gnxp.com/blog/2008/12/nlsy-blogging-eye-and-hair-color-of.php)


## List of Supported Mods
* More Locations
* [PK's Rebalancing](https://github.com/dissociativity/PKs_Rebalancing)

### Issues
Do let me know if there are NPCs wandering around without any hair! You have to redefine the entire NPC class with the additional traits, as `"copy-from"` does not work, unfortunately, so each mod has to have their npc classes replicated. If any mod has updated their NPC class, do let me know so I can update as well, if not they will be missing updates.

If you want support for a mod's NPCs added, feel free to let me know!

### Changelog
* Cataclysm++ has added its own patch for cosmetic support, so for those updating, disable the old one from here!

# My CDDA Mods
[Zetsukaze's Hair Extensions](https://github.com/Zetsukaze/Zets-Hair-Extensions)

[Zetsukaze's CDDA Tweaks](https://github.com/Zetsukaze/Zets-CDDA-Tweaks)
