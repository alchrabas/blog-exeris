Title: Animals system
Date: 2017-01-23 22:45:00
Category: Preview
Tags: exeris, preview, development, animals
Authors: Aleksander Chrabąszcz
Summary: Overview of the wild and domesticated animals system

In Exeris I want to feature as many interesting in-game systems as possible. All of that is in order to give vast amount of possibilities to play the game and organize the societies.

The animals system is going to be a prominent one. People should be able to interact with them in many different ways to both realize their goals and animate the world. That said, it should be necessary to protect themselves against ferocious animals and it should be possible to hunt to get food and hide.

It should also be possible to tame the beasts to use them in a variety of new ways: ride a horse, use a dog as a support in combat, milk a cow, herd the sheep to get wool and breed the pigs to obtain bacon. Different types of animals have different abilities and can obviously be used in different activities. Also male and female animals of the species have different characteristics and that needs to be taken into account.

# Hunting
One of my great quests when developing the game is to eliminate duplication of similar mechanisms to make things easier to learn and understand. As a result, both hunting and defending against an animal uses exactly the same combat system as character versus character. It means that any bugs and problems need to be addressed just once and once you know how to fight against humans you'll know how does it work for animals. In certain circumstances it's possible to have an animal fight on your side, but the combat system is still on the works so I can't describe all the details yet, as they might be subject of change. After the animal dies, it's necessary to butcher it to be able to get the animal resources.

# Domestication
Domestication is naturally the most complex part of the animal system. The first thing a character needs to do to get an animal is to find a wild one and tame it successfully. It has two important results: the wild animal is converted to the domesticated one, e.g. a wild boar becomes a pig. Moreover, the animal starts to trust the initiator of the taming activity.

## What is trust?
Trust system is a way of maintaining ownership over animals. Every character can tame a domesticated animal in order to earn its trust. Taming an animal by a certain character reduces animal's trust to all the other owners. Also trust level decreases over time for everyone except the most trusted character. It means it may be hard to 'share' an animal between a group of people. The specifics can differ for every animal type. Trust is generally needed for special actions, like riding a horse or being helped in combat.

# Eating
One of randomly thrown ideas of things I'd like to make possible was being a shepherd and travelling across the hills with a group of sheep. In Exeris a path between fun ideas and their implementation is very short, so I've decided to incorporate it into the game. So, the domesticable animals can eat fresh food, especially grass, when they are outside and it's available in the area. But this source of wild plants is very limited, so when they are consumed or inaccessible, you need to resort to growing crop on your own which can be stockpiled and then used to fed the animals.

# Objectives
I've said what mechanics I find important, but I didn't say which ones I find less important. I'm going to focus on **social implications** of existence of animals, which means I'm not focusing on creating a balanced simulation of animal ecosystem. I'm also going to keep quality and uniqueness of every animal species, so don't expect too many types of animals. I don't expect to have more than ten species, at least in the current version of the game.

# Current progress & conclusion
I hope all of these ideas sound quite cool, but the important question is whether it's possible to implement then into the game. The good news is that most of it is already done, in particular:

 - hunting on wild animals
 - taming animals
 - feeding domesticated animals
 - milking cows
 - hens laying eggs
 - butchering wild and domesticated animals

There are still some things left to do, especially:

 - domesticated animals reproduction and inheritance of traits
 - animals AI (now they are unable to act on their own)
 - special features of horseback riding (now it's like a normal vehicle)
 - lots of small fixes

So the work is not over yet, but I'm pretty content about the recent progress. You can check it on [dev.exeris.org](https://dev.exeris.org) (remember to first create an account on [users.exeris.org](http://users.exeris.org)).

# A side note about the recent progress
I've started rewriting user interface to use React (as I've mentioned [in my previous post]({filename}progress-in-2016.md)). So far I've completed the works on the events page and created mockups of the other pages. You can see them [here](https://tree.taiga.io/project/greekpl-exeris/wiki/ui).

I plan to finish the work this week, so it'll become available on [dev.exeris.org](https://dev.exeris.org).
