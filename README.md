# Basketball_Scoreboard_Quartus
Device that allows you to track the number of points scored by one team in a basketball game

The scorer (person who manages scoreboard) of a basketball game has three buttons at his disposal,
BTN0, BTN1 and BTN2 by which he adds the appropriate number of points to a given team for each basket scored. By pressing the BTN0 button the scorer adds
one point, by pressing the BTN1 button the scorer adds two points, by pressing the BTN2 button the scorer adds three points. 

Consider it impossible press more than one button at a time and it is not possible to score more than 99 points in one game. The number of points scored by a given 
team needs to be presented in decimal form, and the individual digits of the number of points scored should be shown on two seven-segment displays HEX1 and HEX0 
(HEX1 - display for displaying tens; HEX0 - display for displaying units).

Within the solution of the task, it is necessary to realize the increment as a separate module (in
the project setting only needs to implement the INC7.bdf scheme). The Binary2BCD combination module receives a binary number 7 bits wide as input, and as
the result gives the BCD representation of the binary number from the input. The 7segmentInterface combination module receives a 4-bit binary number as input
on a seven-segment display. The RisingEdge sequential module has one bit as an output that is activated for one clock period, each time the input
changes from inactive to active state.
