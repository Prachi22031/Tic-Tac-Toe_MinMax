# Tic-Tac-Toe_MinMax
ALGORITHM:
The code allows two players, X and O, to take turns entering their moves on a 3x3 game board. The game continues until one of the players wins, or the game ends in a draw.
1.	printboard(xstate, ystate) Function:
•	This function translates the numerical values within the xstate and ystate matrices into visually recognizable markers on the game board.
•	By depicting the game state as a grid with X, O, and empty spaces, it enhances user understanding of the current state of play.
2.	check_win(xstate, ystate) Function:
•	This function determines the game's outcome by inspecting the current state of the board.
•	It evaluates rows, columns, and diagonals to identify a potential winning combination.
•	Additionally, the function considers the total number of moves to determine if the game has ended in a draw.
•	Outputs include values of 1 for X's victory, 0 for O's victory, 2 for a draw, and None for an ongoing game.
3.	Initialization of Game States:
•	xstate and ystate are matrices representing the state of the game board, with initial values set to zero.
•	The turn variable keeps track of the current player's turn, with 1 for X and 0 for O.
4.	Game Loop:
•	The main game loop iterates indefinitely until a win or draw condition is met.
•	In each iteration, the loop displays the current state of the board using the printboard function.
•	Players are prompted to input their moves by specifying the row and column in which they wish to place their mark.
5.	Win and Draw Detection:
•	After each player's move, the check_win function is invoked to determine whether the game has been won or drawn.
•	Upon identification of a winning or drawn scenario, the loop concludes and displays the appropriate outcome.
6.	Turn Alternation:
•	The code alternates between X and O turns by toggling the turn variable.
•	This ensures that both players have equal opportunities to make their moves.
