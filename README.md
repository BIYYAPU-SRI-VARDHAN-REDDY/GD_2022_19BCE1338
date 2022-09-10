# GD_2022_19BCE1338
Assignment :
As the player, you have to survive on the platform as long as possible.

Time : 10th Sept, 5:00pm and should be submitted before 11:00 am 11th September. 

Unity Version to use: 2021.3.9f1

* The solution should be in 3D.
* Any public assets/resources can be used



Backstory:
Our hero Doofus likes to roam around on green metallic platforms called, Pulpit. The only problem with this is Pulpit has a short life span. Within seconds of appearing in the environment, they are destroyed. One day, Doofus took it as a challenge to at least walk on 50 Pulpits. 

Characters/Props:
Doofus - The main character (A simple cube can be considered for the character as well)
Pulpit - A green metallic 9x9 unit platform on which Doofus walk/stand

Target:
Make Doofus walk on as many Pulpits as possible. Remember, Doofus can fall off the Pulpit if he walks away from the edge.

Obstacles:
Every Pulpit has a time span attached to it. Once the timer runs out, the Pulpit gets destroyed. Whatever is on top of that will fall down and the game is over.

Video Reference of GamePlay : 
[https://youtu.be/NOgrwo1dWxQ
](url)
How does Doofus move?
Doofus can move left, right, forward, and backward (Arrow keys or WASD can be used for the movement). If there is no Pulpit below Doofus, then Doofus falls and dies. The speed at which Doofus moves is also written in the Diary of Doofus. The speed is defined in the JSON file below. 

When do Pulpits appear?
There can ever be only 2 Pulpits in existence at the same time. A Pulpit appears when the timer on the previous Pulpit reaches x seconds. The lifespan of a Pulpit is given in the Diary of Doofus (timespan ranges from y seconds to z seconds). When the timer of the Pulpit reaches 0, it disappears.
The Pulpit will appear adjacent (right/left/front/back) to the previous Pulpit randomly. Pulpits cannot appear in the previous position they had already appeared in.

Note : x is a random number between y and z seconds obtained from the JSON file. 

Scoring:
Scoring is based on how many Pulpits was Doofus able to walk on.




Resources & Steps :

You can find and read Doofus’s diary here :
[ https://s3.ap-south-1.amazonaws.com/superstars.assetbundles.testbuild/doofus_game/doofus_diary.json](url)

Note (Important) : Your code should read the above JSON file and set the values accordingly. 

There are no requirements for UI / UX of the game. 

Dofus Game Using Unity
======================

Dofus pvp game like created with Unity. Code in C#

Todo list :  
_enhancement of the movement range display (improve the algorithm)

_add of fighting mecanism  

_add of vision areas (don't allow player to attack a target which is behind an obstacle, even if he is in range)
