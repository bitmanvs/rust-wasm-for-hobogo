# Hobogo
Unfinished experimentation with Rust+WASM for making an AI for the game Hobogo.

## The game
Hobogo is a a pencil-and-paper board game played on a 7x7 grid. Each player has a mark (e.g. X and O) and take turns making a move. You can only mark a cell if the eight neighboring cells do not have more enemies than friends. The game is over when all cells have been marked. The player with most marks win.

(don't try to google Hobogo, me and a friend invented it)

## The AI
The AI is doing blind Monte Carlo Tree Search for one second.

## TODO:
* Test on iPad
* Highlight last move by each player
* Detect player not being able to make a move (add PASS button, or auto-pass)
* ABC/123 on every side
* Better colors
* Non-square board
* Parametric AI (N number of cycles). Will make it speed up towards endgame?
