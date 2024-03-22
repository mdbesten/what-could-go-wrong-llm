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
1. Download this repository
2. Go to https://playingcards.io/game/standard-deck to start a custom deck
3. Enter the virtual card table
4. Click the `Edit Table` icon in the green toolbard
5. Select `Room Options`
6. Select  `Import From File`
7. Upload `what-could-go-worng-av.pcio`
8. Click `Edit Table` to exit editing mode and go into gameplay mode

## Gameplay Instructions with New Rules
All players start with 5 white cards from their stack.
A spinner determines the first Card Czar, who draws a black prompt card to share with the group.
Players submit one white response card face down.
The Card Czar reads each submitted card aloud.
After selecting the best response, the Card Czar initiates a mini-debate on the selection. Players can defend their cards with humorous or persuasive arguments. Successful arguments earn extra points.
Following a brief discussion, a new Card Czar is chosen, and the game continues with players refreshing their hands to five cards.
Players are encouraged to explore new ideas and discuss the implications of various scenarios.

## During the Game
Engage in thoughtful discussion and take notes on new perspectives.
Explore the connections between cause and effect cards, allowing the conversation to guide the gameplay.
Be mindful of sensitive topics and maintain a respectful atmosphere for discussion.
Stay focused on the game's objectives while enjoying the exploration of ethical considerations in AI and technology.

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


