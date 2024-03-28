# What Could Go Wrong - LLM Edition

This repository hosts the files used for the What Could Go Wrong? digital card game. Nikolas Martelaro and Wendy Ju developed and presented the game at a Workshop at AutoUI 2020. The game was then modified by Nik and his team at CMU to be more generalized for AI-based systems.

The version here presents a further iteration on the game. In this iteration, prompts focus on applications of large language models. Example applications are drawn from two sources: Kaddour et al.(2023) and FlowGPT.com. The list of potential ethical issues stems from the AI4People framework (Floridi et al., 2021) and a business ethics enumeration (Baker and Comer, 2012). Besides, this iteration of the game includes a LaTeX template, which can be used to convert the digital card game into a physical card game. 

The digital card game can be loaded into and played on PlayingCards.io. Custom cards can be added using the `csv` files for `prompts` and `responses`

### References
Baker, S.D. and Comer, D.R. (2012) ‘“Business Ethics Everywhere”: An Experiential Exercise to Develop Students’ Ability to Identify and Respond to Ethical Issues in Business’, Journal of Management Education, 36(1), pp. 95–125. Available at: https://doi.org/10.1177/1052562911408071.

Floridi, L. et al. (2021) ‘An Ethical Framework for a Good AI Society: Opportunities, Risks, Principles, and Recommendations’, in L. Floridi (ed.) Ethics, Governance, and Policies in Artificial Intelligence. Cham: Springer International Publishing (Philosophical Studies Series), pp. 19–39. Available at: https://doi.org/10.1007/978-3-030-81907-1_3.

Kaddour, J. et al. (2023) ‘Challenges and Applications of Large Language Models’. arXiv. Available at: https://doi.org/10.48550/arXiv.2307.10169.


## Abstract
While autonomous vehicles have the potential to greatly improve our daily lives, there are also challenges and potential downsides to these systems. In this workshop, we intend to foster discussions about the potential negative aspects of autonomous cars in hopes of surfacing challenges that should be considered during the design process rather than after deployment. We will spur these conversations through a review of participant position statements and through group discussion facilitated by a card game called “What Could Go Wrong?” Our goal is to consider the autonomous vehicle’s benefits—improving safety, increasing mobility, reducing emissions—against potential drawbacks. By identifying potential harms and downsides, the workshop attendees, and the AutoUI community more broadly can design well-considered solutions.

## Game Setup Instructions
1. Download the Repository:
Begin by downloading this repository to access the game files.
2. Create a Custom Deck:
Visit playingcards.io/game/standard-deck to create a custom deck for the game.
3. Enter the Virtual Card Table:
Access the virtual card table where the game will take place.
4. Access Editing Mode:
Click on the "Edit Table" icon located in the green toolbar to enter editing mode.
5. Adjust Room Options:
Select "Room Options" to customize the settings for your game.
6. Import Game File:
Choose "Import From File" and upload the file named "what-could-go-worng-av.pcio" that you previously downloaded.
7. Exit Editing Mode:
Click on "Edit Table" again to exit editing mode and transition into gameplay mode.


## Gameplay Instructions
1. Roles and Setup :
Designate one player as the "Problem Guide" for the game.
All players should ensure they have access to the virtual card table and have their white card stack ready.
2. Initiating the Round :
The Problem Guide selects a black prompt card from the deck and reads it aloud to all players.
3. Submission of Responses :
Other players submit their responses via the chat function. Each player should input one white response card corresponding to the prompt.
4. Reviewing Responses:
Once all responses are submitted, the Problem Guide reveals and reads each white response card aloud to the group.
5. Discussion and Selection:
The Problem Guide selects one response card for further discussion based on its relevance or creativity. The player whose card is chosen earns a point.
Players use emojis, GIFs, or text to express their opinions and reactions during the discussion.
6. Awarding Points:
After the discussion, players vote for the most creative or relevant response. The player with the most votes receives additional points.
Points can also be awarded to players who contribute valuable insights or ideas during the discussion.
7. Rotation and Continuation:
The player with the most points becomes the Problem Guide for the next round.
The game continues with new prompts and responses, and players take turns fulfilling the role of the Problem Guide.
8. Rule of the "Joker Card":
Add a Joker card to the game. When the Joker card is selected as the prompt, all players must provide a completely wacky or absurd response. The funniest or most off-the-wall response earns two points instead of one. This rule adds a touch of whimsy and surprise to the game, encouraging players to unleash their wildest imaginations.


## During the game
1. Foster creativity in responses and discussions.
2. Utilize interactive features such as polls to gather player opinions.
3. Be open to non-linear discussions and allow players to explore new topics.
4. Host themed game sessions where cards are centered around specific subjects.
5. Reward active participation and innovation with virtual prizes or special rewards.ugh!

### Video Demonstration
[![What could go wrong card game demonstration](https://img.youtube.com/vi/DlqgWnhEqoc/0.jpg)](https://youtu.be/DlqgWnhEqoc)

## Adding new cards
Edit the `prompts.csv` and `responses.csv` to add new cards to the decks. Follow instrcutions for adding new cards here: https://playingcards.io/docs/custom-decks

## Suggested Citation
Nikolas Martelaro and Wendy Ju. 2020. What Could Go Wrong? Exploring the Downsides of Autonomous Vehicles. In *12th International Conference on Automotive User Interfaces and Interactive Vehicular Applications* (*AutomotiveUI '20*). Association for Computing Machinery, New York, NY, USA, 99–101. DOI:https://doi.org/10.1145/3409251.3411734

### Bibtex
```@inproceedings{10.1145/3409251.3411734,  
author = {Martelaro, Nikolas and Ju, Wendy},  
title = {What Could Go Wrong? Exploring the Downsides of Autonomous Vehicles},  
year = {2020},  
isbn = {9781450380669},  
publisher = {Association for Computing Machinery},  
address = {New York, NY, USA},  
url = {https://doi.org/10.1145/3409251.3411734},  
doi = {10.1145/3409251.3411734},  
abstract = { While autonomous vehicles have the potential to greatly improve our daily lives, there are also challenges and potential downsides to these systems. In this workshop, we intend to foster discussions about the potential negative aspects of autonomous cars in hopes of surfacing challenges that should be considered during the design process rather than after deployment. We will spur these conversations through a review of participant position statements and through group discussion facilitated by a card game called “What Could Go Wrong?” Our goal is to consider the autonomous vehicle’s benefits—improving safety, increasing mobility, reducing emissions—against potential drawbacks. By identifying potential harms and downsides, the workshop attendees, and the AutoUI community more broadly can design well-considered solutions.},  
booktitle = {12th International Conference on Automotive User Interfaces and Interactive Vehicular Applications},  
pages = {99–101},  
numpages = {3},  
keywords = {game with a purpose, failure modes, autonomous vehicles},  
location = {Virtual Event, DC, USA},  
series = {AutomotiveUI '20}. 
}
```

For some motivation on why we want to develop new hazard analysis games.

```@article{martelaro2022exploring,
  title={Exploring Opportunities in Usable Hazard Analysis Processes for AI Engineering},
  author={Martelaro, Nikolas and Smith, Carol J and Zilovic, Tamara},
  journal={arXiv preprint arXiv:2203.15628},
  year={2022}
}
```


