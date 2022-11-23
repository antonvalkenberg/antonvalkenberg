<img align="left" height="200" width="200" src="/Media/Profile.png"></img>
<img align="right" height="200" width="150" src="/Media/Profile_1.png"></img>
### Hi there 👋, I'm Anton Valkenberg :)
This page is my Portfolio, where I'd like to share some awesome projects that I've had the pleasure to work on, focused on Games & A.I.

#### Current version: 0.1.0 (rough draft of the projects/games I want to highlight)
</br>
</br>

#### <u>HunterKiller (Java version)</u>
During my Master in Artificial Intelligence, I was able to run an internship at Codepoke working under G.J. Roelofs. Together we created HunterKiller as a game in which we could research various search techniques.</br>
Below you can see HunterKiller running on a test-map, which was specifically designed to enable us to efficiently and rigorously test new techniques and adjustments:</br>
![HunterKiller running on a test-map](/Media/HK_run_testmap.gif)
</br>
Here is an example of one of the fully sized maps that were created to test the performance of the different techniques:
![An example of a full Map in HunterKiller](/Media/HK_Map_Example.png)

##### Implemented techniques
- Various heuristic-based bots using value-maps, some examples:
	- Squad bot, which preferred to keep it's units together in small squads while moving
	- Scout bot, which preferred to scout out the enemy's position and highly valued field-of-view coverage
	- Rules bot, which acted based on preconstructed behaviour-rules
- Hierarchical Monte Carlo Tree Search (HMCTS)
- Naïve Monte Carlo Search (NMC)
- Linear Side Information (LSI)

For pathfinding, all of the bots used a combination of A* and value-maps.
Note that the engine included a full field-of-view/line-of-sight implementation.

##### Report on research results
Check [this link](/Documents/Internship_report.pdf) for the report on the research I did during my internship.
It also outlines my proposed enhancement to the HMCTS technique; using side-information for move ordering during the expansion phase of the search.

##### Code
The code for HunterKiller's engine can be found in [the HunterKiller repository](https://github.com/antonvalkenberg/HunterKiller).
</br>
The code for the bots created for HunterKiller can be found in [the HunterKillerBots repository](https://github.com/antonvalkenberg/HunterKillerBots).
</br>

#### <u>HunterKiller (C++ version)</u>
In the last couple months, as an exercise and some self-education, I decided to port HunterKiller's engine to C++.
Here you can see it running in a console window, with two purely random bots playing against eachother:
</br>
![C++ version of HunterKiller running in console window](/Media/HKCPP_run_randombots.gif)
</br>
Currently I'm developing a visualization for this engine in Unreal Engine 5.0, here's a sneak peak: (Note: work in progress)
</br>
<insert link to UE5 screenshot>
	
#### <u>AI/Bot(s) for Hearthstone (C#)</u>
For my Master's Thesis, I wanted to approach the hugely popular digital card game Hearthstone as a Combinatorial Multi-Armed Bandit problem. To tackle this, I used a Hearthstone simulator, Sabberstone, which was written in C#. To employ all the various techniques I had learned about during my internship (and Master as well, I guess :P ), I ported the entire A.I. framework (used by Codepoke) from Java to C#.

##### Thesis and code
The written thesis can be found [through this link](/Documents/Thesis.pdf).
</br>
All of the code, including the A.I. framework and bots written for this project, can be found in [the Master Thesis repository](https://github.com/antonvalkenberg/ThesisCodeHSCMAB).

#### AI for Battlecode 2014 competition, won our University Class' tournament
	- Pathfinding with A*
	- Novel herding strategy, specific to this year's environment
	- Blackboard system for multi-agent communication
#### AI for Knightthrough, variation of chess played with only Knights
	- ...
#### AI for Mastermind, performed best in Class
