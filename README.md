<img align="left" height="200" width="200" src="/Media/Profile.png"></img>
<img align="right" height="200" width="150" src="/Media/Profile_1.png"></img>
### Hi there 👋, I'm Anton Valkenberg :)
This page is my Portfolio, where I'd like to share some awesome projects that I've had the pleasure to work on, focused on Games & A.I.

</br>
</br>
</br>

### HunterKiller (Java version)
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

### HunterKiller (C++ version)
In the last couple months, as an exercise and some self-education, I decided to port HunterKiller's engine to C++ (cpp20).
Here you can see it running in a console window, with two purely random bots playing against each other:
</br>

https://user-images.githubusercontent.com/15450200/203626881-a1d5988a-431e-45bc-b3a1-ad3a27b6b8c9.mp4

</br>
Currently, I'm developing a visualization for this engine in Unreal Engine 5.0, here's a sneak peak: (Note: work in progress)
</br>
<insert link to UE5 screenshot>
	
### AI/Bot(s) for Hearthstone (C#)
For my Master's Thesis, I wanted to approach the hugely popular digital card game Hearthstone as a Combinatorial Multi-Armed Bandit problem. To tackle this, I used a Hearthstone simulator, Sabberstone, which was written in C#. To employ all the various techniques I had learned about during my internship (and Master as well, I guess :P ), I ported the entire A.I. framework (used by Codepoke) from Java to C#.

Due to this being a research Thesis, no visualization was required or requested, so I did not spend any time developing that.

##### Thesis and code
The written thesis can be found [through this link](/Documents/Thesis.pdf).
</br>
All of the code, including the A.I. framework and bots written for this project, can be found in [the Master Thesis repository](https://github.com/antonvalkenberg/ThesisCodeHSCMAB).

### AI for Battlecode 2014 competition (Java)
As one of the projects during the A.I. Master, we were tasked with writing an AI/entry for MIT's yearly competition called Battlecode. We eventually ran our own tournament between all the groups in our Class of that year. Our group won this tournament by beating the most amount of other teams on all the maps provided by the University. As an additional note for clarity: the objective of the 2014 edition of Battlecode was to herd cows into pastures and optimize resource-generation.
</br>
Our approach included, among others, the following techniques:
- Pathfinding using A*
- Novel cow-herding strategy, specific to this year's environment
- Blackboard system for multi-agent communication
- Fully automated testing code to facilitate more efficient testing of enhancements (and other teams' bots as well)

### AI for Mastermind (Java)
In our first year at Maastricht University, our very first group-project was to create a UI for the well known board game Mastermind, as well as an automatic solver that could guess a user's code in as few guesses as possible. The results for our group were quite good: we beat the other 5 groups in our Class (even though one group reported an average of <3, which is not possible). For the default game setup of 4 positions and 6 total colors, our solver reached an average of 4.41 moves.
The following two pictures show the UI we created back then (note that this was in 2003), as well as our results:
</br>
<img height="300" width="250" src="/Media/Mastermind_UI.png"></img>
<img height="230" width="400" src="/Media/Mastermind_Results.png"></img>
</br>

</br>
</br>

### :v: Thank you for checking out my Portfolio! :heart:
If you have any questions, you can find my email address here in [my profile](https://github.com/antonvalkenberg).

</br>
</br>
:copyright: A. Valkenberg 2022, current version: 1.0.0, last modified: 23-11-2022
