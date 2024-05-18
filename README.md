# AutoDeletus

AutoDeletus is a World of Warcraft addon designed to automatically delete or sell unwanted items based on user-defined criteria. 

It helps keep your inventory clean and organized by removing items that you don't need.

# Features

Automatically delete or sell items based on rarity, item level, and item type filters

Customizable inclusion and exclusion lists for fine-grained control over item deletion

Toggle the addon on/off and enable/disable selling to vendors

Set a selling threshold to control the minimum quality of items to be sold

Void (delete) all items of a specific rarity with a single command

Persistent configuration settings that are saved across sessions

# Installation

Download the latest release of AutoDeletus from the releases page.

Extract the AutoDeletus folder from the downloaded ZIP file.

Copy the AutoDeletus folder into your World of Warcraft addons directory (usually located at World of Warcraft\_classic_\Interface\AddOns).

Launch World of Warcraft and ensure that the addon is enabled in the character selection screen.

# Usage
AutoDeletus provides a set of slash commands to configure and control the addon. You can use the following commands:

/loot toggle - Toggle the addon on/off

/loot selltovendor - Toggle selling to vendor

/loot sellthreshold <threshold> - Set the selling threshold (0-1)

/loot include <itemName> - Add an item to the included items list

/loot exclude <itemName> - Add an item to the excluded items list

/loot removeinclude <itemName> - Remove an item from the included items list

/loot removeexclude <itemName> - Remove an item from the excluded items list

/loot rarity <rarity> - Set the item rarity filter (0-7)

/loot itemlevel <itemLevel> - Set the item level filter

/loot addtype <itemType> - Add an item type to the item type filter

/loot removetype <itemType> - Remove an item type from the item type filter

/loot void <rarity> - Delete all items of the specified rarity from the bag

/loot config - Print the current configuration
