# AB-Testing-for-Mobile-Games

## Project description
The dataset is from https://www.datacamp.com/projects?page=1. 

Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three" style puzzle game where the player must connect tiles of the same color in order to clear the board and win the level. 

As players progress through the game they will encounter gates that force them to wait some time before they can progress or make an in-app purchase. In this project, we will analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. In particular, we will analyze the impact on player retention.

## Data description
* userid = A unique number that identifies each player.

* version = Whether the player was put in the control group (gate_30 - a gate at level 30) or the group with the moved gate (gate_40 - a gate at level 40).

* sum_gamerounds = The number of game rounds played by the player during the first 14 days after install.

* retention_1 (次日留存率) = Did the player come back and play 1 day after installing?

* retention_7 (七日留存率)= Did the player come back and play 7 day after installing?

## Project Aims
We will use A/B tests to determine whether the difference in retention between the two groups is statistically significant. 