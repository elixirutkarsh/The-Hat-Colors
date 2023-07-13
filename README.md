# The-Hat-Colors
Problem Statement:
There are three people standing in a line, each wearing a hat. The hats can be either red or blue. Each person can see the hats of the people in front of them but not their own or the hats behind them. Starting from the person at the back, they are asked to guess the color of their own hat. The guesses proceed as follows:

The person at the back says, "I don't know."
The person in the middle says, "I don't know."
The person in front says, "I know."
How did the person in front know the color of their own hat?

Solution:
The solution lies in observing the responses of the two people ahead. Let's analyze the possibilities:

If the person at the back sees two hats of the same color in front of them, they would know that their own hat is of the opposite color. In this case, they would confidently announce the color of their hat.
If the person at the back sees two hats of different colors in front of them, they cannot determine their own hat's color. Hence, they say, "I don't know."
The person in the middle listens to the response of the person at the back. If the person at the back confidently announces the color, it means their own hat is of the opposite color. However, since they said, "I don't know," it indicates that the person in the middle also cannot determine their own hat's color. Hence, they say, "I don't know."
The person in front analyzes the responses of the two people behind them. If both of them said, "I don't know," it means that they cannot determine their own hat's color based on the information received. However, when the person in front hears this, they can confidently conclude that their own hat is the opposite color. Therefore, they say, "I know."
