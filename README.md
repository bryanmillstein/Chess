# Chess
* This is a classic Chess game written in Ruby for terminal play between two human players.

# Setup
* After downloading and opening the repository, run "ruby game.rb" in your console program of choice.

# Controls
* Input a move as a number-number coordinate pair separated by a comma. The input order is row, column. For  example, 6,3 selects the white player's pawn above the queen. A subsequent input of 4,3 will advance the pawn two spaces. Please follow the instructions in the terminal throughout game play.

# Features
* Graphical interface with unicode representations of chess pieces.
* All pieces inherit from sliding or stepping piece superclasses in order to keep code DRY and modular.
* Deeply duplicates board to check for valid moves.
* Error handling and rejection of invalid/illegal moves prompting a user to choose another move.
* You cannot move into check and are required to move a king out of check before moving an alternative piece.
