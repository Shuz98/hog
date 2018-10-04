# hog
This is the source file for a two player dice-rolling game
This is a two player dice-rolling game. Each player take turns to roll a dice a number of times. Whoever gets 100 points first wins with the following rules:

A) Pig Out. If any of the dice outcomes is a 1, the current player's score for the turn is 1.
Example 1: The current player rolls 7 dice, 5 of which are 1's. They score 1 point for the turn.
Example 2: The current player rolls 4 dice, all of which are 3's. Since Pig Out did not occur, they score 12 points for the turn.

B) Free Bacon. A player who chooses to roll zero dice scores 2 * tens - ones, or 1, whichever is higher; where tens, ones are the digits of the opponent's score 
Example 1: The opponent has 46 points, and the current player chooses to roll zero dice. 2 * 4 - 6 = 2; which is greater than 1, so the current player gains 2 points. 
Example 2: The opponent has 73 points, and the current player chooses to roll zero dice. 2 * 7 - 3 = 11; which is greater than 1, so the current player gains 11 points.

C) Swine Swap. After points for the turn are added to the current player's score, if the absolute difference between the last two digits of
the current score and the last two digits of the opponent's score are the same, the scores are swapped

How to play:
1. Download all the files in an empty folder
2. Git Bash in the folder
3. in the terminal enter "python3 hog_gui.py -f" (or "py hog_gui.py -f" if it doesn't work)
4. Enjoy!
