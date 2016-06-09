Title: Exeris - Ideas overview
Date: 2016-06-05 2:15:00
Category: Preview
Tags: exeris, preview, development
Authors: Aleksander Chrabąszcz
Summary: Overview of ideas, features and mechanics which will exist in Exeris

Hello. For quite a long time I thought I'll go without a blog, but now I've decided to give it a try.
The main reason is the fact that forum is not yet publicly available and it must wait, because I want to connect forum accounts with in-game accounts.

On this blog I'd like to explain things which aren't properly explained on the front page
and present the game features in a form interesting for a player, without going into internals.

First of all, I'd like to describe ideas and mechanics which make Exeris a crafting and an exploration game.

# Crafting
The core element of a crafting game is building or manufacturing tools or structures, which help in producing other things.

Exeris is a sandbox with almost unlimited freedom of choice, where you can travel across the map, get and use resources to create structures or destroy them.

## Resources (stackable items)
A character you control will be able to gather materials of many different groups, like stone, wood, gold or coal.
To encourage personalization of the items there are multiple resources, which are interchangeable in the group, for example:

 - oak, willow or pine for **wood**
 - sandstone or granite for **stone**
 - potatoes, beetroots or cucumbers for **vegetables**

The amount of every resource of a group needed to fulfill the requirements for manufacturing can vary.
It's a quite complex system which is already complete and will be explained more thoroghly in the future.

Resources is just a common name for items that are *stackable*, which means if you drop one in place where there's already one on the ground
then it *stacks* onto the first one and they are shown as a single entry showing quantity, for example:

 - 2 oak branches
 - 11 carrots

The example above shows how all items with quantity of more than one are presented. All stacked items consist of the finite number of individual objects.
By the way it also revals that stackable items of the same type are exactly the same - they don't have any individual properties, which is different from the rest of items, called **non-stackable items**.

Well, there's one exception from this rule - some of the stackable items can be enhanced by adding some other resources chosen by the player. This way it's possible to drastically expand creativity of cooking recipes without zillions of predefined options. For example sandwiches can be enhanced using various foods to create the following variations:

 - 3 sandwiches with cheese and ham
 - 5 sandwiches with carrots, garlic and sausage
 - a sandwich with boiled potatoes and salt

## Non-stackable items
Most of items are not stackable, which means they can have individual properties like quality, damage or used material (and many more).
This allows to give player an ability to sew a shirt using any cloth and cotton is used, then the finished item is called "a cotton shirt".
It will be explained thoroughly in an entry concerning the **recipes**.

quality, damage, fixed/portable, destruction

## Locations
**Locations** are a different class of entity than items and their main property is possibility of being entered by the characters.
The 'outside locations', called **root locations** are created when you travel and then stop somewhere to perform an action.

It's possible to build a building in a root location and then build more rooms in the building, then rooms in rooms and so on. (I'll post a pic later).

Vehicles are locations as well, but they are mobile.

# Exploration
Exploration is as importantas crafting, so much effort was spent to make it fun and interesting.

The whole idea of the Old and New World is to give everyone a chance to explore. If the world were static, then soon all its parts would be 

sailing, random map generation, survival, finding treasures


