## Purpose

A small number guessing game.
main - 
	The base game

hotfix -
	Fixed randomInt to include full range (max - min + 1) as opposed to (max - min)

	feature 1 - 
		Added ability to replay the game without rerunning the program.
	
		Added "quit" function

	feature 2 - 
		Added new variable "maxAttempts = 10", indicating maximum number of guesses the player can make before a game over.

		dev -
			Added new message "Good Luck!"

	feature 3 - 
		Added hints system

Learning Summary
	Merge combines multiple branches, while keeping their history. Rebase does something similar but essentially rewrites the history. Squash can combine multiple commits in the same branch into one. Cherry-pick will apply a single commit from one branch to the current branch.

Merge is good for converging two separate, new additions to the program after having confirmed that they both work in their current state.
Rebase is best for when you're more confident that the two branches will work with each other, and you won't need to go back to a previous version. Since rebase modifies the history, it makes the overall result a lot cleaner.
Squash is good for cleaning up the commits within the branch. This is, again, best for when you're sure that you will not need to access any one of those specific commits again.
Cherry picking works when you only want one commit from another branch. The commit that you cherry-pick might actually be necessary to have for what you want to do next on your current branch, but you're not quite confident enough to merge/rebase the entire other branch.