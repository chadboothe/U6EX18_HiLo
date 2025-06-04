# HiLo

In the Hi-Lo game, the player begins with a score of 1000 and ends when the player reaches zero or 4,000.

The player is prompted for the number of points to risk and a second prompt asks the player to choose either High or Low. The player’s choice of either High or Low is compared to random number between 1 and 13, inclusive.

If the number is between 1 and 6 inclusive, then it is considered “low”. 
A number between 8 and 13 inclusive is “high”.
The number 7 is neither high nor low, and the player loses the points at risk.
If the player had guessed correctly, the points at risk are doubled and added to the total points.

For a wrong choice, the player loses the points at risk.

Now for the methods (you MUST use METHODS!)

The main method should ONLY be used to explain the rules of the game. 
- All game play and logic need to be in the playGame() method.
- Ideas for methods: displaying points, random number generation, taking bets, determining winner, getting a users choice, asking to play again, etc?
- Methods will probably need parameters, some might need return statements, but all will be public and static. 
- Each Method must have ONE specific task!
- Create a HiLo application based on this specification. Application output should look similar to:

```
HiLo Game

RULES
Numbers 1 through 6 are low
Numbers 8 through 13 are high
Number 7 is neither high or low.

You have 1000 points.
Enter points to risk: 500

Predict (1-HIGH, 0-LOW): 0
Number is: 4
You Win.
Play again? y

You have 2000 points.
```
