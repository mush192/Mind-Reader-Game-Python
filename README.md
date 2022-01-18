# Mind-Reader-Game-Python
"A Mind Reading Machine" based algorithm that predicts player input in the game.

In this game, player needs to input a value 0 or 1 and the computer predicts the player input. If computer predicts correctly, Computer wins. Else, Player wins. Since this code is based on Claude Shannon algorithm, it is very difficult to cheat the computer.

Working:
Here the computer looks for certain patterns in the player inputs (0 or 1) and tries to remember them. Furthermore, it assumes that the player will follow these patterns the next time if the same situation arises.
If an assumed pattern is not repeated at least twice by the player, the machine predicts 0 or 1 randomly.
