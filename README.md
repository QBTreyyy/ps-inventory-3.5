# ps-inventory-3.5
ps-inventory 3.5 Inspired With Protected Slots

# JOIN OUR DISCORD AT https://discord.gg/2vAxvqEX


# PS-Inventory Edit  --ALL CREDITS GO TO PROJECT SLOTH THIS WAS JUST EDITED FOR GHOSTED RP WITH ADDED FEATURES

lj-Inventory has been fully redesigned by [OK1ez](https://github.com/OK1ez), under the name ps-inventory.

Future updates will be coming and we will of course support all normal monitor sizes.

# Previews

### Simple item guidelines (found in main directory ps-inventory)


### Full Inventory

![image](https://i.ibb.co/nr0jW6q/invvvv.png).

### Custom Edits 

![image](https://i.ibb.co/qrc1dZv/jewlery.png)

### Store Preview

![image](https://i.ibb.co/NKsQgFZ/hardware.png)

### Hotbar Slots

![image](https://i.ibb.co/R0KT2md/hotbar.png)

### Inventory Glovebox

![image](https://i.ibb.co/YXy8N6Y/glovebox.png)

### Inventory Trunk

![image](https://i.ibb.co/d7Sdyc7/trunk.png)

# Key Features

* 5th slot removed
* Protected slots and jewelry slots 
* INVENTORY BUFF SYSTEM CONNECTED (custom weight buff system)
* ALL IMAGES FOLLOW THE SAME DIMENSIONS
* Easy Photoshop guideline template for creating custom images within ps-inventory
* Custom brand logo above option buttons
* Options menu
* Help box 
* Custom inventory images (more always being added in each new update)
* Default weight icon easily changeable with Font Awesome icons
* Hotkey numbers visible in inventory and hotbar slots
* Weight progress bar
* Tooltip has a determined height (so it won't ever go higher than visible or cut off)
* Text overflow ellipsis used (so your product titles with never overlap the containers and instead do "...")
* Blurred inventory background
* Elements of NoPixel 3.5 design ideas interwoven

# How to install ps-inventory (Latest QBCore Update)

* Download `ps-inventory` from our GitHub
* Make sure you have the latest update of [qb-core](https://github.com/qbcore-framework/qb-core)
* Make sure you have the latest update of [qb-smallresources](https://github.com/qbcore-framework/qb-smallresources)
* Make sure you have the latest update of [qb-weapons](https://github.com/qbcore-framework/qb-weapons)
* Drag `ps-inventory` into your resources folder or any subfolder
* Make sure that the folder is named `ps-inventory` and **not** `ps-inventory-main`
* Replace all occurrences of `qb-inventory` with `ps-inventory`.<br>The example below uses Visual Studio Code to replace all instances.

![ps-inv setup](https://github.com/Project-Sloth/ps-inventory/assets/9503151/f95ceacb-09fa-4619-bd1c-7b7524f4f282)


## Set up the decay system

If you want the decay system to work, then please read the information below, otherwise it won't work.

You need to add a decay value for all items in your `qb-core/shared/items.lua` file, the variable stands for the number of days it takes to decay.

### Examples:

#### Example of what you have to add

```lua
-- decay = The number of days it takes for an item to decay
-- delete = If set to true, the item will be removed once it decays
["decay"] = 28.0, ["delete"] = true
```

#### Example with the full item in QB-Core's shared file

```lua
['sandwich'] = {['name'] = 'sandwich', ['label'] = 'Sandwich', ['weight'] = 200, ['type'] = 'item', ['image'] = 'sandwich.png', ['unique'] = false, ['useable'] = true, ['shouldClose'] = true,	['combinable'] = nil, ['description'] = 'Nice bread for your stomach', ["decay"] = 3.0, ["delete"] = true},
```

In this example, the sandwich item would take 3 days to decay and once it does, it would be removed.

# Dependencies

* [qbcore framework](https://github.com/qbcore-framework)
* [qb-target](https://github.com/BerkieBb/qb-target)
* [qb-core](https://github.com/qbcore-framework/qb-core)
* [qb-logs](https://github.com/qbcore-framework/qb-logs)
* [qb-traphouse](https://github.com/qbcore-framework/qb-traphouse)
* [qb-radio](https://github.com/qbcore-framework/qb-radio)
* [qb-drugs](https://github.com/qbcore-framework/qb-drugs)
* [qb-shops](https://github.com/qbcore-framework/qb-shops)

## Performance

Runs at ~ 0.00 to 0.01 ms if you have more optimization suggestions feel free to reach out

# Credits

* [OK1ez](https://github.com/OK1ez) for full redesign. 
* ihyajb (Aj) for [original version](https://github.com/ihyajb/aj-inventory)
* Jay for [decay](https://github.com/tnj-development/inventory)
* i-kulgu for [updated decay](https://github.com/i-kulgu/qb-inventory-decay)
* [OnlyCats](https://github.com/onlycats) who helped reorganize and also created some custom images.

# Issues and Suggestions

Please use the GitHub issues system to report issues or make suggestions, when making suggestions, please keep [Suggestion] in the title to make it clear that it is a suggestion.

