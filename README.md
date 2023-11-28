# Board Game
Board Game Project

## Random number game

Implement a game in Code::Blocks c-code that has the following functionality:

This is a two-player game, involving 5 randomly generated numbers from 1 to 9.

The players take turns to play and the game takes nine turns per player.

Each turn consists of up to three separate attempts.

The active player attempts to match all 5 values over the three attempts in order to score the highest possible sum.

On the first attempt, all five values are randomly generated.

The player can select to keep a subset of the five values they want (including none or all the values).

The discarded values (if any) can be randomly re-generated on the second turn to obtain a better combination of five values.

The selection and re-generation process can be repeated one last time.

At the end of the third turn, the player must select a place on the scorecard (as shown below) to place the sum of matching values.

The score you get depends on the location that you choose and the combination that you have rolled.

After a location is used, you can't use it again. 

The scorecard:
There are nine locations, each corresponding to the numbers 1 to 9.
For these locations, the sum of the values with the corresponding number is entered (and all other values are ignored).
For example, if you have 5 3 3 5 3 at the end of your turn, you may select row 3 and this should give a score of 9 for that row, or else you could select row 5 and obtain a score of 10 in that row.
Bonus: At the end of the game, you get a bonus of 72 points if the total score is 135 or higher.

NOTE: Code that does not compile will adversely affect your grade.

## Simplified explanation
You have 5 numbers that are randomly generated at first.

Each attempt you select which numbers you want to keep, those stay in their positions and the rest are randomly rolled again.

This is an attempt.

Each turn is 3 attempts.

Then at the end of each turn you select which number you want this turn to count towards.

The score for the turn is N * amount of time N is among those 5 numbers, where N is the number you chose and each of those can be used once
