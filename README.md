# Journey
Lootfilter for Diablo II: Path of Diablo

## Overview
This filter provides sane default settings in a classic style, and includes many customization options.

Most items are shown at level 1; the filter gradually becomes more strict as your character levels up to 90+. The filter file includes descriptions for what is hidden at which levels, and other descriptions are included throughout to assist with tailoring the filter to your needs.

If the in-file descriptions/options are unwanted, the [streamlined version](https://github.com/BetweenWalls/Journey/tree/streamlined#Journey-streamlined) has the same defaults at less than half the filesize. Journey shouldn't be too strict, but for a more vanilla-like experience, [Feather](https://github.com/BetweenWalls/Feather#Feather) is a minimally-strict alternative.

## Features
* mostly follows classic style (it still looks like D2)
* non-equipment more clearly distinguished from equipment (gems, jewels, charms)
* unique/set/other items highlighted based on their usefulness
* regular items displayed with amount of skills and highest skill value
* dynamic display for high-price sellable items (more prices are shown the poorer you are)
* popular crafting ingredients marked with codified recipes
* natural sockets shown for unidentified unique/set items
* enhanced damage/defense shown for superior items
* identified relics show their tier
* shopping for valuable items from merchants made easier

### Examples of optional features:
* [individual names for unidentified unique/set items](https://github.com/BetweenWalls/Journey/tree/individual-names#Journey-individual-names)
* [all individual skills shown](https://github.com/BetweenWalls/Journey/tree/all-skills#Journey-all-skills)
* all crafting ingredients with codified recipes
* item quality (normal, exceptional, elite) for uniques/rares
* quantity for keys/tomes
* extra highlighting for unique/set items changed in Path of Diablo
* textless gems
* various highlighting options for regular/magic/rare items

## Installation
Follow the [wiki instructions](https://pathofdiablo.com/wiki/index.php?title=List_of_Loot_Filters#How_to_Use) and use the direct URL: https://raw.githubusercontent.com/BetweenWalls/Journey/master/item.filter

Alternatively, [download **item.filter**](https://drive.google.com/uc?id=1jAXM-MkmWBtPZBJ40SqAmBrWv4xLKAD9) and manually copy it to your *Path of Diablo* folder. Once in-game, enable the **custom loot filter** option from the *Settings* menu. Any modifications made to the filter can be seen by refreshing the same option.

Modifications can be made with any text editor - the wiki has an introduction to [loot filtration](https://pathofdiablo.com/wiki/index.php?title=Loot_Filtration) and a list of item [codes](https://pathofdiablo.com/wiki/index.php?title=Loot_Filtration_Codes). Additionally, the Path of Diablo discord has a channel dedicated to lootfilter discussion.

## Images
![_](/images/miscellaneous_items.png)
![_](/images/unidentified_items.png)
![_](/images/uniques_special_properties.png)
![_](/images/runes.png)
![_](/images/regular_items.png)
![_](/images/regular_class_items.png)
![_](/images/gems.png)
![_](/images/unidentified_highlighting.png)

## Performance
Filter rules for Journey (and Feather) have been written and organized in ways to optimize computer performance. One factor in that performance is the effective length of the filter file - the number of lines with active rules. Following is a list of these filter lengths:

* [Feather](https://github.com/BetweenWalls/Feather#Feather) - 283
* Journey - 505
* [Journey (streamlined)](https://github.com/BetweenWalls/Journey/tree/streamlined#Journey-streamlined) - 505
* [Journey (all skills)](https://github.com/BetweenWalls/Journey/tree/all-skills#Journey-all-skills) - 516
* [Journey (individual names)](https://github.com/BetweenWalls/Journey/tree/individual-names#Journey-individual-names) - 1040
