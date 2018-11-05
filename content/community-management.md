Title: Community management
Date: 2016-06-23 1:00:00
Category: Preview
Tags: exeris, moderation, management
Authors: Aleksander Chrabąszcz
Summary: How to make Exeris administration scale with the playerbase

Administration of every internet community isn't an easy task, because usually there are many regular users and few people who manage them.
It's often necessary to act quickly and every mistake causes negative reaction of the community.

Exeris will not be an exception, so it needs some system to facilitate task of removing cheaters or trolls.
The equally important thing is to not be harsh and not waste time for policing irrelevant issues.

I like programming, but not administering, so I feel additional motivation to make these tasks as limited as possible.

# In-game crime vs Game rules breach
First of all, it's necessary to distinguish in-game crime from breaking the game rules. In-game crime like stealing, robbing characters or even killing them, which are valid game actions, is **acceptable**, as long as it's done by means provided by the game.
It's part of society simulation and obligation of in-game communities to establish a legal system and guarantee safety of people who decide to obey to it.

So there's an essential difference between *in-game crimes* (actions done by characters) and *breaking the game rules*, like exploiting the bugs or cooperation using multiple characters of one player.

## Crime and punishment
All the people who obey to the game rules should be allowed to play, as the world will be large enough so people who don't like each other will stay in different parts of it.
That suggests to embrace the idea of outlawry which was often used by communities I'd like to mimic (e.g. *skóggangur* in Viking societies).

Character who behaves incorrectly could be 'alerted' by fellow players, who would first get a private warning that some people in the area don't like them. Then, if more people report them as not welcome, they become marked as an 'outlaw'. It would be a publicly visible state which would not bring any further implications, but all the people will most likely be prejudiced to them, unless the said character leaves the region. When it doesn't work, then it's always possible to kill that character, but I feel the game should propose less violent options.

## Game rules
The game rules don't exist yet, but the forbidden things I see now are:

 - using bugs
 - using two characters of one player to help each other
 - sharing information between two characters which haven't met in the game

Reporting game rules breach will be separate from the outlawry system, so people breaking them will be eliminated quickly.
It's necessary to keep in mind that regular players must take active part in players management to keep the game fair for everyone. Otherwise it won't work.

To expand the comminity-support system, also the cases of reported players could be pre-reviewed by randomly selected expert players, who would be asked for opinion, before the decision is made by the game administrator. It would bring community supervision over the whole process and leverage part of work from the always-busy administrators.

There's nothing insightful in the idea. It's worth mentioning that forum software I've selected - Discourse - is also based around concept of community management, giving some moderator rights to the most active forum users.

# Community support in Open Source
I feel it's very important to promote good and freedom through every aspect of Exeris, and that's why the game is:

 - 100% free
 - open source ([code is available on GitHub](https://github.com/alchrabas/exeris))
 - created and run by volunteers
 - supported by voluntary donations

I do my best, but there's lots of work I'm unable to do, just to name translations of the game interface, which are the crucial part of the text game.

I've put much effort into making the game nicely internationalizable (translatable into different languages) by use of [Pyslate](https://github.com/alchrabas/pyslate), but then the whole work needs to be done by volunteer translators.
I don't want to introduce any barriers for people willing to bring the aid, so access to the translation tool will be **available for every player of the certain language**.

![Translations can be rejected by community reviewers](/images/community-management/translation-rejected.png)

Validity of every translation will need to be confirmed by different players (community reviewers) to avoid vandalism, but it would be extremely easy to start contributing to the game.

![Translations approved by community reviewers are added to the game](/images/community-management/translation-approved.png)


## Why so Open Source?
The game is created as a hobby project in order to learn Python and to create a game **I would really like to play**. A good game means not only the good code, but also good treatment and cooperation with players.

My intentions are just and giving away the code to everyone is the best way to prove that.
This way if most of you, players, will think the game turns into the wrong direction, nothing will stop you from setting up an another game server. I'm not afraid of competition, as it makes things better. ;)

