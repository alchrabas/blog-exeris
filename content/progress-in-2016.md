Title: Progress by the end of 2016
Date: 2016-12-31 13:00:00
Category: General
Tags: development, summary
Authors: Aleksander Chrabąszcz
Summary: What was done in 2016, the recent progress and plans for the future

2016 was a busy year for me. I've spent time on many different activities, Exeris development being one of the most notable ones.


![Number of lines of code added/removed every month](/images/progress-in-2016/lines-of-code-github.png)

Number of lines of code that were added or removed in every month of 2016

You can see my activity in the last year based on [a timeline on GitHub](https://github.com/alchrabas/exeris/graphs/contributors?from=2016-01-02&to=2016-12-30&type=c), but I think [a commit history](https://github.com/alchrabas/exeris/commits/master) or even [a list of finished tasks](https://tree.taiga.io/project/greekpl-exeris/backlog) is not the most convenient way to learn about the hottest features. I know you are probably not interested in changes of the internals, even though they were substantial.

# Recent development
The last tasks have introduced the following changes or features:


 - wild and domesticated animals system (you can read about it [in my next post]({filename}animals.md))
 - creating land vehicles and ships
 - travelling, sailing and naval boarding
 - creating a vehicle consisting of multiple entities e.g. a horse with a cart
 - building and using storages
 - manufacturing keys and locks
 - character inventory with limited capacity
 - fully working coins and coin presses

There are also other important things like forum and chat integration or replacing AJAX technology with WebSockets, but they are not directly related to the game features.

# Plans for the future
After finishing my MSc thesis I'm going to have much more spare time to spend for Exeris, so I'm already seriously thinking that the game is close to entering the beta phase of development in early 2017.

To reach it, I need to manually create a bigger map and offer more items to manufacture (so testing will be more fun). It also means I need to prepare some administration tools for managing game's content.
Another important step I've decided to make is to abandon the current server-side Jinja2 templating engine and use [React](https://facebook.github.io/react/), a relatively new JavaScript library for FrontEnd development. It's going to be a lot of work, as I'm not yet experienced with it, but I think it'll help in creating a brand new user-friendly game interface.

I'll not be able to do everything I wanted before releasing the beta, so I think the rest of important things, like the world generator and the graphical map generator will become available in beta2. If everything goes well, then the world, characters and items from beta2 could be transferred to the 1.0 release, whose main feature would be the introduction of the New World and all related mechanics. Then I'd just polish and tweak the already existing systems.

# Conclusion
It was a very good year and I hope to keep the amazing pace of development from the last months.

One thing I'm not fully content about is insufficient number of posts on the blog. I'll try to get better in 2017 so you'll be able to read about all the new features. I'll start with the animals system, which will be the first post in the new year.
