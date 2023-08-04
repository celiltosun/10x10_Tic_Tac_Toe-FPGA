This project is our endterm project for EE314 at Middle East Technical University in the spring of 2023. 
This project is a Tic Tac Toe game for two players that can be played by using Altera FPGA board and a VGA monitor.
The game is played by using 3 buttons: Logic-0 button, logic-1 button and activity button. Each player inserts 8 bit number by using logic-0 and logic-1 buttons and presses to activity button to place a symbol on given coordinate. First 4 bit corresponds to row data and second 4 bit corresponds to column data. For instance; 01010001 corresponds to fifth row, first column.  
First player that places 4 symbols side by side horizontally, vertically or diagonally wins the game. 
Challenge in this game is that at every 6th move of a player, the first move that played by same player gets cancelled and corresponded square turns to red. 
At 25th move, the game results in draw. 