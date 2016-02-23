# Fifteen-Puzzle

Loyd's Fifteen Puzzle - solver and visualizer<br>

-TG 13/08/2015(modifed oct/2015)<br>

-project for PoC course by Rice University<br>
https://www.coursera.org/course/principlescomputing2<br>
-Fifteen Puzzle template <br>
http://www.codeskulptor.org/#poc_fifteen_template.py<br>

 Graphical user interface "FifteenGUI class" and part of "Puzzle class" provided by instructors and modified by TG<br>
- random shuffle method added<br>
- print moves method removed<br>
- accept capitals letters on input<br>
- accept leading and/or trailing whitespace characters on input<br>
- short game instruction added<br>

<p>
!!!! NOTE !!!!<br>
This is PYTHON code written to work in codeskulptor, w'll work in PYTHON 2.X after some changes<br>
Code from text file must be copied and paste into codeskulptor editor: http://www.codeskulptor.org/<br>
popup windows must be enabled
</p>

<h4>Fifteen Puzzle - HOW TO PLAY?</h4>

<p>
Solved configuration has the blank (zero) tile 
in upper left. Use the arrows key to swap this tile with 
its neighbors or alternatively you can type in a string 
containing letters:
</p>
- u - for UP<br>
- d - for DOWN<br>
- l - for LEFT<br>
- r - for RIGHT<br>
<p>
and hit enter. "zero" tile moves only in-side puzzle grid, 
program simply ignores invalid moves and print message in 
the consol on the right for each invalid move:
invalid move: "direction of invalid move".
You can randomly shuffle puzzle and solve puzzle by 
clicking on the buttons in the control area. When you hit 
Solve, program starts simulation by "moving" "zero" puzzle
towards solved configuration by 4 tiles per second.
Note that some configurations (when use Shuffle Puzzle and
Solve) are not solvable by this program, if get message in
the consol - "2x2 puzzels can't be solved", 
some or all top-left 4 tiles will remain unsorted.
</p>

This puzzle implementation will work on different grid size:<br>
change value of GRID_SIZE variable in the code<br>
2 <= GRID_SIZE <= (not tested above 8)<br>

Enable pop-up windows!!

-Hit PLAY icon to Start
(left top corner)
