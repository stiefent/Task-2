# Task 2 

## Branch Structure

feature1: Version comment quit feature
- improve feedback messages for guesses
- add play-again loop
- add quit game with negative number

feature2: Implement max attempts logic and game over condition
- add maxAttempts constant and game over state
- add encouraging messages

Feature3: Done

hotfix: Fix randomInt to include max value in range

## Learning Summary

Differences:
- Merge takes two branches and combines the commits from each branch and the the histories of both branches
- Rebase moves your local branch to the tip of another branch, reapplying the commits one at a time. It takes the target branch and rewrites your local branch's history to have one linear history
- Squash takes a given number of commits, and reduces them to a singular commit to reduce the number of commits in the history
- Cherry-pick allows to pick out a commit in the history that can be commit to the target branch without messing with the local branch

Observations: 
Between the three features, all of them represented a similar program. Feature1 implemented a play-gain loop, quit game, and improved user feedback. Feature2 implemented max attempts and game over. Feature3 was used to add the hint system after 3 attempts. The history of feature 3 shares the commit history of the other two features due to the merge with dev.

Real-World Application: 
Each strategy can be used in many ways. 
- Merge is used to combine the entire history of one branch to another when you are confident with your tested material. 
- Rebase is when you want to integrate changes such that there is not a large change such as keeping a feature branch up to date.
- Cherry-pick can be useful for applying hot-fixes to the main branch for urgent updates. It can also be used to fix bugs and fix accidents with commits.
- Squash can be used to clean up a branch to reduce the amount of clutter and make readability better