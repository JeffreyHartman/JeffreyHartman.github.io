---
layout: post
title: From Humble Beginnings
---

For as long as I can remember, I've wanted to get into video game development. After many false starts and barely begun side projects cluttering my Github account, I've finally decided to take this a little more seriously. So, I've started this blog to keep me honest and motivated. I don't have a lot of free time outside of work and family time, so I will probably be posting rather sparingly. 

Most of my false starts I can partly blame on being much too complicated and un-defined for a beginner's first project. So my first game has to be something simple, with clearly defined mechanics. So what's simpler than an Atari game?

![A scan of Atari's Combat box cover]({{ site.baseurl }}/images/2016-07-19/combat-atari-2600-front-cover.jpg "Atari's Combat")

Combat, released in 1977 for the Atari 2600, is one of my earliest gaming memories. There were actually a couple different game modes included in there, but I'm only going to concentrate on the tank modes. I am especially fond of the 'Tank Pong' mode, where the bullets will bounce off the barriers, making for some tense competitive gameplay. There were also bi-plane and jet modes, but the tanks were always my favorite, so that's the experience I want to re-create. The game was 2 player only, but I may attempt a rudimentary AI once I have this feature complete.

![A screenshot of Combat, depicting two tanks in a top down environment ]({{ site.baseurl }}/images/2016-07-19/combat-atari-2600-screenshot.gif "Tank Combat")

I guess the first big decision of developing a game is whether to use a development engine or to create something from scratch. I do code in my day job, so I'm not afraid of creating something from scratch, but my goal here is to actually get a complete game out as quick as possible, so I've chosen to use Game Maker Studio as my development engine. I've dabbled with it before, following some short tutorials, and I've found it incredibly easy to pick up and learn, and it seems especially well suited for 2d top down games like Combat.

After a few days of messing around in Game Maker, I've gotten a small start.

![A screenshot of my Combat clone, depicting two tanks in an empty field]({{ site.baseurl }}/images/2016-07-19/tanks.png "Tank Combat")

I wanted to get the bare basics of what you could call a game up for this post. The only thing you can currently do is drive around and shoot, one bullet at a time. There is a scoreboard, but there is currently no ending situation. There's not even any walls or player destruction at the moment, you just shoot your opponent and get a point. The movement and firing doesn't even feel like the old Atari Combat yet, I just sort of threw the mechanics in there. Still, it's a start. The left player is controlled with W S A and D, with the space bar firing, and the right player is controlled with the arrow keys, with the Enter button firing. 

The source can be viewed and downloaded on [Github](https://github.com/JeffreyHartman/CombatClone). Keep in mind I have no idea what the hell I'm doing yet. I'm pretty much guessing or googling things as I go along. A lot of things are stored in global variables because I don't know what else to do with them, and most of it feels kind of hacked together.

Hopefully I'll have the workings of something more than just barely playable by next post! Next up, I plan on implementing player death (although it wasn't really death in the original Combat, you just kind of got knocked backwards and spun around for a bit), and a winnin condition.
