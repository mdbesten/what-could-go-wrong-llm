# What Could Go Wrong - Online Communities Edition

This repository is the home for the resources needed for the « What « Could Go Wrong - Online Community version » online game. Originally crafted by Nikolas Martelaro and Wendy Ju, the game debuted at the AutoUI 2020 Workshop. It underwent transformations under Nik and his collective at CMU, evolving to encompass AI-centric scenarios. The current iteration diverges significantly, shedding light on the dynamics of online communities.

In this version, the game delves into the vast universe of online social structures, leveraging prompts that explore the intricacies of virtual interactions and community governance. Inspiration for scenarios comes from a blend of theoretical research and real-world examples, including findings from Smith et al. (2024) and insights from VirtualSocietyHub.com. The framework for discussing potential social and ethical implications is informed by the Digital Society Ethics Code (Diaz & Patel, 2023) and principles of online community management (Jensen & Harper, 2022).

This iteration is enriched with a versatile LaTeX template, enabling enthusiasts to bring the game into the physical realm from its digital origins. Players can immerse themselves in "Community Constellations" through PlayingCards.io, where the game thrives with options for customizing decks through provided csv files for prompts and responses, allowing for a tailored exploration of online communities' complexities.

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

## Gameplay Instructions with Wildcard Round Integration

1. All players draw 5 white cards from their stack.
2. Click the spinner to determine the first player to become the Card Czar.
3. If a player either do not know the definition of the word mentionned on the prompt card or thinks there can be a confusion on the meaning of this word, this player tell others and : 
  a. If every other players have the same definition in mind : explain it to the player who did not know and continue the game (go to fifth point of instructions).
	b. If the other players disagree on the right definition : the whole team debate on the right definition to adopt.
	c. If people disagree, the Card Czar decide it.
4. All other players then put 1 white response card face down in their slot.
5. **Introducing the Wildcard Round**: At a predetermined point in the game, players are allowed to play two white cards instead of one, introducing a dynamic element of strategy. This round allows for the potential to earn double points if both cards are selected by the Card Czar, encouraging deeper thought in card selection and synergy.

- **Activation**: The Wildcard Round is introduced at a specific, pre-announced point in the game, such as after every third round, to inject a refreshing twist.
- **Dual Play**: During this round, players are permitted to select two white cards from their hand instead of the standard single card. This challenges players to think strategically about card combinations that will resonate with the prompt and with each other.
- **Double Points Opportunity**: If the Card Czar selects a player’s combination as the most compelling, that player earns double points for the round. This raises the stakes and encourages players to engage more deeply with both the prompt and their cards.

6. The Card Czar reveals all submitted white cards, reading each aloud. They then select the card(s) that they find most fitting or humorous in relation to the black prompt card. +1 point (+2 in case of both the two submitted cards are chosen in wildcard round) goes to the player whose card was chosen.
7. The chosen white card sparks a group discussion, allowing players to explore further implications or humorous takes on the scenario.
8. The group engages in an extended discussion on what else could go wrong based on the chosen card. Participants can award +1 point to anyone who contributes a compelling point during the discussion.
9. After the discussion concludes, a new Card Czar is chosen via the spinner, and the "Deal" button is pressed. This ensures each player draws up to 5 cards again, preparing for the next round.

### During the game
1. Take notes on ideas that you have not thought about before
2. Some of the cards are causes, others are effects. Don’t worry about what the game designers intended with each card, go where the discussion is best.
3. Some of the cards may be upsetting. (Such as, a person is abused.)
4. It’s fine to take time to have discussion.
5. Try not to get side tracked, though!

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


