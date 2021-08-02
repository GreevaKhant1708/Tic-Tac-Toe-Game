# Tic-Tac-Toe-Logisim-
Tic tac toe implementation using logisim

There are 4 parts leading to the complete implementation. 

Part 1 is the mover circuit, which detects if a move attempting to be made is allowed or not. It uses D flip flop along with AND and NOT gates.

Part 2 is the win detect circuit. There are 8 ways in which a player can win Tic Tac Toe, these 8 ways are checked in the win detect circuit.

Part 3 is the controller, which has mover circuits for every box in the grid(i.e., 9 boxes). It also has the windetect circuit to finally select the winner.

Part 4 is the main circuit, at which the two players can play the game. It has 9 input buttons for each color(blue and green), for two players. These buttons are connected to the controller circuit which is further connected to the output LEDs to show the move that was made. And it is also connected to two other LEDs to show when the winner is found.

The game can be played with either blue or green as the first player. This circuit does not check if the same player makes the move continously. To reset the game press ctrl + r.

Logisim is a free and open source software compatible with multiple platforms like Windows, MacOS and Linux. The ease of Logisim comes from its interactive graphical user interface developed with Java Swing GUI library. Users can create circuits with simple drag actions of the mouse.

Logisim can be downloaded from : https://sourceforge.net/projects/circuit/

*It requires java 1.5.0, which if not available in system, will be prompted by logisim installer.
