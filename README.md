A number guessing game is being developed based of main, and there are multiple branches that add functionality, but never merge to the master/main.

Main branch: initializes a number guessing game, then branches out to feature1, feature2, feature3, and dev.

feature1 branch: adds the following functionalities to the game in its own branch. 
	- adds the ability to quit the game with negative input.
	- adds play-again loop functionality
	- improves user feedback messages for guesses
	- adds version comment documenting quit feature
dev branch separates from main and Adds encouraging message for players

feature2 branches from dev branch and adds the following in order:
	- Adds max Attempts constant and game over state
	- Implement max attempts logic and game over condition

feature3 branches from main branch. The commit messegas are terrible and don't convey detailed information. 
After researching feature3 I discovered that they added a hit system for the game. To provide the player hints throughout their journey.

Lastly. There was a hotfix branch based on the main branch to include the max value in the range of a randomInt.

When these branches decide to merge into the main, numerous conflicts will need to be resolved.