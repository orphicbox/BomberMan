# BomberMan
This is a programming test

------------------------------------------------------
## Hi IKA Engineer,
my name is Mahmood and it proud to me I have a chance to give a test for IKA company.
I'm sorry to start the test too late.
Unfortunately, the glass injured my one-year-old boy's hands and I spent the few days at the hospital and my brain didn't work well. fortunately, now everything is OK and of course, from the day I received the test, I think about implementation much enough :)
I know that 16 hours to complete all the features is very very short. But I'll try my best.

------------------------------------------------------
## Procedural map generator
next step in creating procedural map generator:
It's ideal that can create map by enter world size and block size.  Obviously world boundary elements need too.
It's need to have 2 type of Walls: Indestructible and destructible.

------------------------------------------------------
Now by choosing MapGenerator_BP actor in the world and setting  these three parameter user can create procedural level:
1- world dimension (number of cell (in a row or column); level always will be square.
2- BlockSize: set each cell size
3- Destructible Wall Chance, for adjust chance of destructible walls. Obviously affect to game play time and difficulty

------------------------------------------------------
## Player navigation:
according to short time to implement list of feature and because of fast development I prefer to skip using two different clients (two pawn actor) in game and writing c++ code for making custom pawn movement. (and making custom player states) I can handle custom navigation bye passing input to simple Actor objects. Using Axis and action binding and move player physically can be acceptable. There is much time until morning and I want to make a double Espresso.

------------------------------------------------------
## Bomb Explosion:
bomb should have two difference functionality: 1- calculate max length until first wall 2- create list of all destroyable items in their range. With "ExplosionLenght" variable, we can set fire length. Also in next steps we can change it by Superbomb item for longer explosions. Also "ExplosionDelay" is for make delay before explosion.

------------------------------------------------------
## After 13 hours development:
From last night 10PM until now (8:30 AM), I worked about 10:30 hours. Also few days ago, I think about implementation totally near 3 hours.
I know that by today my one-week time will be finish. I have just 2.5 hours and many features are remained. 
In fact, I think main features now work and **there is no problem to implement other features with their bonus**. 

Of course I know **"IKA-Designed to work perfectly"** and all of my current code need to well testing and clean-up.
------------------------------------------------------
## After 15 hours development:
I worked 2 hours and I add some small features:
1- bombing limitation added by Reloading parameter
2- add scorboard for each player
3- fix destory wall minor bug





