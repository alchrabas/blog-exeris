Title: Open development server
Date: 2016-09-28 1:00:00
Category: Preview
Tags: exeris, development
Authors: Aleksander Chrabąszcz
Summary: It's now possible to enter the Exeris development server


First of all, I need to say I won't keep the word I gave in [project's readme on GitHub](https://github.com/alchrabas/exeris/blob/master/README.md#plans):

> There is no goal to run pre-alpha version of the game as soon as possible. Most of the backend code is validated by automatic tests, so there's no need to have a running game server.

I didn't mean to focus on the idea of a development server, but I was already running one locally in order to make sure that everything works, so I've seized the opportunity of setting up a permanent game server on a machine which is available all the time. So I'm pretty happy I did it, because I was going to need it eventually.

The game is often the subject of radical changes, so all the data from the dev database is frequently wiped out, including game accounts.

![Current development server interface needs some polishing](/images/dev-server/interface.png)

# Exeris accounts management
The important reason of spending my time on setting up the server was my dream of introducing *'one to rule them all'* game accounts. I want every user have a single account which can be used to log into the game, but also on forum, chat and for other auxiliary services (like the development server, which I'll explain shortly). Such ability is called [Single Sign-on](https://en.wikipedia.org/wiki/Single_sign-on).

To enable it I had to enable registration on the game server and make sure the accounts won't disappear.  
That's why I had to set up two servers:

 - the main server (**[users.exeris.org](https://users.exeris.org)**) - currently used only to register the account
 - the development server (**[dev.exeris.org](https://dev.exeris.org)**) - allows to test the game using the same credentials as on **users.exeris.org**

In short: you register on **users.exeris.org** and then log in on **dev.exeris.org** using the same username and password. Synchronization of the new accounts between these servers can take about one minute.

# Join Exeris forum
Having an account on users.exeris.org is enough to join Exeris forum. Just go to forum.exeris.org and click *"Log in"*, which will attempt to create an account on forum using credentials from [users.exeris.org](https://users.exeris.org). You just need to make sure you are already logged in on [users.exeris.org](https://users.exeris.org) so these credentials can be transferred. Your game account's username (ID) will be used as a nick on the forum.

I'd like to have the same system for Exeris chat (powered by [Mattermost](https://www.mattermost.org/)), but game--chat integration is much harder than the one between the game and forum. The chat won't be publicly available before I sort out the problems. In the mean time you can join #exeris IRC channel on Freenode to ask me some questions.

By the way, all auxiliary services cooperating with the game are open-source, just like Exeris is. I hope to keep it this way.

# Setting your own development server
When I was setting up the servers I had to make some things more configurable, which makes setting up your local development server a much easier task. I guess not many people would need it, but basic Linux administration skills are enough to start. More info in [game server install guide](https://tree.taiga.io/project/greekpl-exeris/wiki/game-server-install-guide) (page is still in construction).

# Blog comments section
As you can see I've integrated the forum with the blog's comments section. It's possible to read comments either there or in the associated thread in the [**Blog** category](https://forum.exeris.org/c/blog) of the [Exeris forum](https://forum.exeris.org). First I was pretty suspicious and overwhelmed by the Discourse forum software, but now I keep liking it more and more. ;)
