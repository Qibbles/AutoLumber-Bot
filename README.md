# AutoLumber Bot

This is a fully automated lumberjack script for the Orion client on the UO Forever Shard by Kibbles. 

The script will recall you to locations within your runebook, scan for and chop trees around you, recalls back to the bank set in your runebook (first rune), drops off the loot, and goes to the next lumber location.

Healing and fighting are also taken care of. Script will attack any mobs within 1 tile, chase it down, and loot its corpse.

Red detection is present but unreliable. Script will scan and detect Red players within 25 tiles and attempt to recall back to bank, drop off loots, and recall to the next lumber location to continue.

If you wish to contribute to the project, provide feedback, or just talk about anything, please feel free to hit me up on discord. 

My discord username is Kibbles#9429.

## Requirements:
Lumberjacker skills:
- 120 Lumberjack
- 100 Healing
- 100 Swordsmanship
- 100 Anatomy
- 100 Tactics
- 64 Magery
- Anything you wish

Spellbook:
- Recall
- Fully charged with Recall scrolls (optional)

Equipment:
- GM Axes (Double axes are the best)
- 5-10 of each Recall Reagents (Black Pearl, Blood Moss, Mandrake Root). You may set the quantity to be restocked in the script
- 40 bandaids (recommended). You may bring more if your skills are low and it takes a long time to kill the snakes
- Runebook with 6 runes (Bank rune in position 1, 5 locations to LJ). You may add as many LJ location runes as you wish

## Setup
When creating your character, the 3 skills to pick (in order of priority) are healing, Lumberjack, Magery.

Begin by macroing, in a dungeon:
1) Healing to 90 (or more). Anatomy should be 100 by then.
2) Magery to 62 (or more).

Purchase from NPC the other skills and then you may start scripting!

Character setup should take 1-2 hours at the very most.

Things to set in the script:
    1) Runebook serial (Your runebook should have a bank spot rune and a recommended 5 or more lumber spots)
    2) Reg bag serial (This is a bag in your bank with the required reagents for recalling - BP | BM | MR)
    3) Drop bag serial (This is a bag in your bank to deposit your gold and logs)
    4) Create a list called 'LumberLoot' with all the items you would like to unload to your bank
    5) Create an ignore list called 'ignoreLoot' for the items you do not wish to loot
    6) Recall to your first lumber spot, run the script (AutoLumber()), and profit!

Enjoy!

## Permissions:
This script is provided to you for free as is. 

You may use and distribute this script as you wish. For any modifications, please submit a pull request onto the github project page at: https://github.com/Qibbles/UOF-Fully-Automated-Lumberjack.

If you would like to fork this script as a base for your own, please feel free and all I ask is for some credits :)

## Links
Links to my other scripts repos (UOSteam & Orion) coming soon!
