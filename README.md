- 👋 Hi, I’m @Sakhilendlovu, Bachelor of Science in Informatics .
- 👀 I’m interested in Systems development and Data science projects.
- 🌱 I’m currently learning C++ application development using Qt Creator, and User interface design using Figma.
- 💞️ I’m looking to collaborate on Machine Learning projects as well Data Visualisation. 
- 📫 You can reach me on E-Mail: Sakhilendlovu698@gmail.com

Dice Game
The Dice Game is a C++ console application that allows multiple players to compete in a dice-rolling game. Each player takes turns rolling dice and 
accumulating points based on the outcome. The objective of the game is to reach a specified winning score before the other players.

Game Rules
1.The game is played with a set of standard six-sided dice.
2.Each player takes turns rolling the dice.
3.The sum of the dice values rolled by a player in each turn contributes to their score.
4.If a player rolls a 1, their turn ends, and they lose all the points accumulated in that turn.
5.A player can choose to roll the dice multiple times in a single turn until they decide to stop or until they roll a 1.
6.The first player to reach or exceed a specified winning score wins the game.
7.In case of a tie, the player who reached the winning score first is declared the winner.

Getting Started
Follow the instructions below to compile and run the Dice Game on your machine.

Prerequisites

* C++ compiler (e.g., GCC, Clang)

Compilation

1.Clone the repository or download the source code files.

2.Open a terminal or command prompt and navigate to the directory where the source code is located.

3.Compile the code using the following command:

shell                  Copy code

g++ -o dice_game dice_game.cpp


Running the Game
After successfully compiling the code, run the game using the following command:

shell                   Copy code
./dice_game

Game Interaction
Once the game starts, you will be prompted to enter the number of players, the number of dice per roll, and the winning score. 
Follow the on-screen instructions and provide the requested information.

During a player's turn, they will be prompted to roll the dice or stop. If they choose to roll, the dice will be rolled, and the outcome will be displayed. 
The player can continue rolling or stop and accumulate the points. If a player rolls a 1, their turn ends, and they lose all the points accumulated in that 
turn.

The game continues until a player reaches or exceeds the winning score. The winner is then announced, and the game terminates.

Example Gameplay

Here's an example of a game session:

yaml                   Copy code

Welcome to the Dice Game!

Number of players: 2
Number of dice per roll: 2
Winning score: 50

Player 1, it's your turn.
Rolling 2 dice...
You rolled: 3 4
Points accumulated: 7
Roll again? (Y/N) Y
Rolling 2 dice...
You rolled: 2 5
Points accumulated: 14
Roll again? (Y/N) N
Turn ended. Total score: 14

Player 2, it's your turn.
Rolling 2 dice...
You rolled: 6 6
Points accumulated: 12
Roll again? (Y/N) Y
Rolling 2 dice...
You rolled: 1
Turn ended. Total score: 0

...

Player 1, it's your turn.
Rolling 2 dice...
You rolled: 1
Turn ended. Total score: 14

Player 2, it's your turn.
Rolling 2 dice...
You rolled: 2 2
Points accumulated: 4
Roll again? (Y/N) N
Turn ended. Total score: 4

Player 1 has reached the winning score of 50! Player 1 wins!
Conclusion

The Dice Game provides an entertaining way to compete with friends by rolling dice and accumulating points. Compile and run the game code to start playing. 
Enjoy the game and have fun!

License
This project is licensed under the MIT License. See the LICENSE file for details.


<!---
Sakhilendlovu/Sakhilendlovu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
