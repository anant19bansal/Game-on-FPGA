# Game-on-FPGA
### Description:
This is a 2 player game. Both the players increment a common count from 0 by either 3, 2 or 1 turn by turn. The player who gets to 21 first wins the game. 
#### For example: 
P1: 1 2 <br>
P2: 3 <br>
P1: 4 5 6 <br>
P2: 7 8 <br>
P1: 9 10 <br>
P2: 11 12 13 <br>
P1: 14 15 <br>
P2: 16 17 <br>
P1: 18 <br>
P2: 19 20 21!!! <br>

Player 2 wins the game

### Hardware used:
- FPGA (Zynq-7000 SoC - Zedboard)
- 7 segment LED displays <br>
<img src = " https://github.com/anant19bansal/Game-on-FPGA/blob/master/FPGA%20image.jpg" width = " "> <br>
<img src = " " width = " "> <br>

### Input/Output Specifications:
- 3 switch buttons for incrementing count by 1, 2 or 3
- 1 switch button for reset
- 2 LEDs to indicate the turn of the player
- 2 seven segment displays to show the count <br><br>

<img src = " https://github.com/anant19bansal/Game-on-FPGA/blob/master/FPGA%20Game.png" width = " ">
