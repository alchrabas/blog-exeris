Title: How to keep it working forever?
Date: 2016-07-30 20:00:00
Category: Preview
Tags: exeris, open-endness, production, entities, balance
Authors: Aleksander Chrabąszcz
Summary: How to keep building and production system well balanced. Today, after ten years and forever

One of the most important requirements for every game, be it single or multiplayer, is to **keep it balanced**. Things shouldn't be too hard or too easy to not discourage from the beginning and give satisfaction as a reward for completing the tasks.


# The problems of open-ended games
In a game like Exeris, where there is a single long-time server, balance of two main game aspects can be hurt due to progress made by players who joined in the early phase of the game:

1. **competition over resources** - older players can earn so much resources that it's not possible for a new player to ever catch up and stand a chance against them, which makes the game unable to attract more players. This is often countered by a reset, which can be an impulse for the old guard to stop playing.
2. **cooperation in acquiring resources** - older players can reach maximum level of development of structures which can be re-used by new players. In addition, old players can easily produce things which are far better than the ones available to new players. It sounds great at first impression, but then comes the question: what to do when everything is already done and every initiative is imitative and useless?

The first forces strict cooperation of younger players and, as it's extremely challenging, even a minor success against old players is very rewarding. But it's clear that experience/wealth shouldn't increase linearly (or superlinearly), because it would remove even this small window of opportunity.  
The second, on the other hand, discourages from doing *anything*. There's no goal in the game, nothing to rush for and compete about. It's necessary to invent artificial objectives to try to keep it entertaining.

Exeris features both player competition and cooperation, so both problems will occur. I find the second more dangerous, but both need to be addressed with care. I'll try to list the specific problems (regardless they apply to the issue of competition or cooperation) and my proposals of solutions.

# Combat
In Exeris, every character can improve the skills during their lifetime. They can also get better resources and produce better equipment.
The important issue is to guarantee balance between the old and new characters in combat. It means that difference between the old and new players shouldn't be too big.

**Solution:** Skills need to be capped and their increase will be slower than linear. A veteran fighter should be a few times (3-5) better than a greenhorn, but nobody should be able to defeat the whole army.
Of course the equipment is also important, so its defense capabilities will be limited by maximum items' quality.

# Crafting
The crafting system should make it possible to produce competitive tools by relatively new players - an infinite linear increase of all tools' quality would mean it's better to have every tool manufactured by experienced smith and *it's unwanted to get any help from the rookies*. I'd like to see the opposite: unexperienced characters being a valuable help for the old ones.

**Solution:** The skill-based item quality should be relative to the skill needed to produce it. So, it should be pretty easy to produce top level hammer (as it's a basic tool) and above certain threshold it's not important how more experienced character is.

![Skill above 0.4 doesn't increase hammer's quality, but higher skill is required to produce a sword](/images/how-to-keep-it-working-forever/skill-quality-impact.png)

Weaker assistants will also be helpful when working on stackable items, because they don't have quality, so the only difference is longer production time.

# Quality limitation
As you gain skill in crafting, you need to re-produce a better version of the item until you reach the highest possible quality.
Limit means this item quality improvement loop cannot be done infinitely, so when you reach the best skill and infrastructure needed to create the item, then it never needs to be produced again, so craftsmen have nothing to do.
As you see, the solution for the combat imbalance creates a new problem.

**Solution:** All structures in the game: tools, machines, buildings or vehicles deteriorate over time. The only way to bring them back into shape is to repair them using part of materials used for production. Such **maintenance cost** is higher for more technologically advanced items and makes it harder to keep everything everywhere. It encourages reducing number of redundant items by recycling them.

# Food
Food is a group of stackable items that aren't used to build any tools or machines, so they cannot be used to repair them. It introduces the risk of hoarding big amounts of food that is nowhere to be used.

**Solution:** Obviously, food can be eaten. Every type provides different nutritional value and affects attributes: strength, durability, fitness and perception. It's always better to eat more processed (and thus more expensive) food, which reduces risk for excessive overproduction.  
Moreover, to disallow hoarding, food ingredients and prepared dishes, unlike other stackable items, deteriorate and rot over time. Processed and more expensive food take longer to rot, so it requires some planning to prepare correct food for the journey.

# Exploration
Usually in the games there are some areas which can be explored. Sometimes new areas are added as the game expands, but soon *Tour de New Lands* is over and everyone knows everything. It's unacceptable in the **crafting and exploration game**, so dealing with this problem is one of the most fundamental issues I had to cope with when I've started the work. The most obvious solution is reset, but it also has obvious disadvantages.

**Solution:** When I had to choose between reset and lack thereof, I've decided to go with something on the middle ground. There will be two continents: one will stay forever, while the second will be removed once for a while. Then the brand new continent will be generated to be explored again. It will give everyone a chance to take part in another exploration attempt and the quest for rare resources.

# Skills limit
I've mentioned them earlier, but only regarding combat. I've already said that every single skill is capped, but why stick to specializing on this particular area, when it's possible to train another and another skill, eventually mastering all the skills in the game? It would hurt game's incentive to cooperate, because some characters would be able to do everything on their own.

**Solution:** Skills are partitioned into groups and it's much easier to learn other specialization of the same branch (e.g. confectionery for a baker) than a skill from a completely new group. It slows down the process, it's not a solution, though.  
The solution is to **limit ability to learn for old characters**. First I've thought it's necessary to introduce *death of old age*, but I've changed my mind. Now I think it's enough to make such rich and developed characters eat more and produce less, to give player the right to decide when the story should end. But I've already changed my opinion about the matter a few times, so it may still be different.

# Consumption
It's a simple observation. As many as possible items and structures should be consumable, which means they disappear when used and in exchange give some short-time benefits for the character. Examples could be: food, fuel, feed, explosives, arrows for a bow, baits for fish or game animals, animal traps. As few as possible items should give passive (eternal) buffs (as it's said in MMORPG terminology).

# Conclusion
I've spent a lot of time analyzing the game aspects which can make Exeris live longer, or maybe forever, but I'm sure that even more will have to be learned experimentally during the beta tests. Theoretical knowledge will make it significantly easier to come up with the correct solutions, but most of the work will be getting feedback from the players and tuning the game elements accordingly to make sure the game will be appealing both for new players and the ones who joined the game right in the beginning.
