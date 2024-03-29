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
While autonomous vehicles have the potential to greatly improve our daily lives, there are also challenges and potential downsides to these systems. In this workshop, we intend to foster discussions about the potential negative aspects of autonomous cars in hopes of surfacing challenges that should be considered during the design process rather than after deployment. To enrich these discussions, we have added new features like the Contribution Tracking System to highlight active participant engagement, Dynamic Challenge Cards to tackle current AI ethical issues, and Scenario Expansion Packs to explore diverse AI applications. To enrich discussions, we have also introduced a Communication Feature that facilitates real-time discussion and feedback among players. We will spur these conversations through a review of participant position statements and through group discussion facilitated by a card game called “What Could Go Wrong?” Our goal is to consider the autonomous vehicle’s benefits—improving safety, increasing mobility, reducing emissions—against potential drawbacks and the broader implications for AI applications in various domains. By identifying potential harms and downsides, the workshop attendees, and the AutoUI community more broadly can design well-considered solutions.

## Game Setup Instructions
1. Download this repository
2. Go to https://playingcards.io/game/standard-deck to start a custom deck
3. Enter the virtual card table
4. Click the `Edit Table` icon in the green toolbard
5. Select `Room Options`
6. Select  `Import From File`
7. Upload `what-could-go-worng-av.pcio`
8. Click `Edit Table` to exit editing mode and go into gameplay mode
   
After entering the gameplay mode, participants can engage with the new role-assignment feature to undertake specific organizational tasks and access the collaborative card crafting module to co-create new content with peers. Ensure to download any relevant Scenario Expansion Packs to keep the discussions up-to-date with the latest AI applications.

## Gameplay Instructions
1. All players draw 5 white cards from their stack 
2. Click the spinner to choose the first player who will be the Card Czar.
3. The Card Czar then pull a black prompt card and reads it to the group 
4. All other players then put 1 white response card face down in their slot.
5. The Card Czar then flips and reads each white card out loud.
6. The Card Czar then picks one of the white cards to further discuss. +1 point goes to the player whose card was chosen.
7. The group then discusses further what else could go wrong based on the chosen card. People can award +1 point anyone who makes a good point in discussion.
8. After the discussion dissipates after a few minutes, the next player becomes the Card Czar and clicks the “Deal” button. Each player then draws a new white card, so that they again have 5 cards in their hand.
9. Each round, players will be assigned roles like "Ethics Overseer" or "Sustainability Steward," with specific tasks to contribute to the organization of the gameplay. (addition of Role Assignment Feature and Collaborative Card Crafting)
10. Integrate a Communication canal, where players can chat, discuss strategies, and provide instant feedback on gameplay moves 
    
### During the game
1. Take notes on ideas that you have not thought about before
2. Some of the cards are causes, others are effects. Don’t worry about what the game designers intended with each card, go where the discussion is best.
3. Some of the cards may be upsetting. (Such as, a person is abused.)
4. It’s fine to take time to have discussion.
5. Try not to get side tracked, though!
6. participants should engage with the Contribution Tracking System to ensure their engagement is accurately captured. This system will enhance the credit statement aspect of the game.
7. Moreover, players are encouraged to utilize the online community contribution platform to submit their own expansions or modifications to the game, fostering an environment of online community Peer Production (OCPP).
8.  Utilize the Communication canal to share thoughts and strategies, making the gameplay more interactive and engaging

### Video Demonstration
[![What could go wrong card game demonstration](https://img.youtube.com/vi/DlqgWnhEqoc/0.jpg)](https://youtu.be/DlqgWnhEqoc)

## Adding new cards
Edit the `prompts.csv` and `responses.csv` to add new cards to the decks. Follow instrcutions for adding new cards here: https://playingcards.io/docs/custom-decks. 
Players can also use the Collaborative Card Crafting feature during the gameplay to create new cards which may then be added to the game upon community review and approval.

### Community Contributions
A new online communities contribution platform is now available, where players can submit their game expansions or modifications, which will be reviewed by the community and possibly included in the official game, enhancing the OCPP relevance of "What Could Go Wrong."
To further bolster community engagement, the new Communication Feature provides a forum for discussion and brainstorming, allowing for richer collaboration on submitted expansions or modifications

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


