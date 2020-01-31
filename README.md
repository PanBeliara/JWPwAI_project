# JWPwAI_project

Used frameworks:
- anime.js

So basically it's a maze game where you need to direct your yellow ball onto the green box. You can change the board's dimensions (up to 80x40) and it will randomly generate proportional amount of obstacles (fields you cannot cross nor even stand on). You can bump into them if you aren't currently moving.

The buttons above your maze are your controls. They and the board disappear when you finish a game. Then also the animated "Congratulations!" appears.

You can generate a new map at any given moment. The obstacles can prevent you from reaching your goal though and it is a bug that requires some path finding algorithm like A*, but i couldn't find time to write it since I was fighting the actual framework. It was a poor choice for an interactive game and also object oriented code and it's better fitting more of static website content. Well, the more you know.
