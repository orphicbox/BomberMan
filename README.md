# BomberMan
This is a programming test

------------------------------------------------------
Hi IKA Engineer
My name is Mahmood and it proud to me I have a chance to give a test for IKA company.

I'm sorry to start the test too late.
Unfortunately, the glass injured my one-year-old boy's hands and I spent the few days at the hospital and my brain didn't work well.

fortunately, now everything is OK and of course, from the day I received the test, I think about implementation much enough :)

I know that 16 hours to complete all the features is very very short. But I'll try my best.
------------------------------------------------------

next step in creating procedural map generator:
It's ideal that can create map by enter world size and block size.  Obviously world boundary elements need too.
 
It's need to have 2 type of Walls: Indestructible and destructible.

------------------------------------------------------
Now by choosing MapGenerator_BP actor in the world and setting  these three parameter user can create procedural level:
1- world dimension (number of cell (in a row or column); level always will be square.
2- BlockSize: set each cell size
3- Destructible Wall Chance, for adjust chance of destructible walls. Obviously affect to game play time and difficulty

------------------------------------------------------
Next step: player navigation:
 
According to short time to implement list of feature and because of fast development I prefer to skip using two different clients (two pawn actor) in game and writing c++ code for making custom pawn movement. (and making custom player states) I can handle custom navigation bye passing input to simple Actor objects. Using Axis and action binding and move player physically can be acceptable.

 
