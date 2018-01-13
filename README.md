# Bingo-Game---Skillrack

<div class="ui raised segment big">

                                                <div class="ui label big circular grey">Program ID- 3622</div>
                                                <div class="ui label big circular pink"> Solved By 66 Users</div> 



                                                <div class="ui label big circular black">Author: SkillRack</div>                                                
                                                <img class="ui avatar image mini circular" src="http://cdn.skillrack.com/profilepic/1/1508170751418skillrack.png">
                                                <br>
                                                <h3 style="color:#003333">BINGO Game</h3>
                                                <br> <p>A Bingo game is played with a 5x5 matrix board. When a person correctly guesses a number in the board it is slashed. When 5 rows or columns are entirely slashed it is BINGO (As BINGO contains 5 letters).</p>

<p>Given the values for the 5*5 matrix board, followed by N numbers which are guesses by a person, find the number of guesses needed for a BINGO.</p>

<p><strong>Input format:</strong><br>
First 5 lines each contain 5 numbers with the values for bingo game.<br>
6th line contains N<br>
7th line contains N numbers as guesses by the person separated by space.</p>

<p><strong>Boundary Condition:</strong><br>
1 &lt;= Number in a Bingo board &lt;=50<br>
1 &lt;= Number Guessed &lt;=50</p>

<p><strong>Example Input/Output 1:</strong><br>
<strong>Input:</strong><br>
1 2 3 4 5<br>
6 7 8 9 10<br>
11 12 13 14 15<br>
16 17 18 19 20<br>
21 22 23 24 25<br>
33<br>
1 29 2 49 28 3 4 5 47 6 7 8 26 9 11 50 12 27 45 13 16 17 18 21 22 23 24 41 25 36 19 39 42</p>

<p><strong>Output:</strong><br>
29</p>

<p><strong>Explanation:</strong><br>
The guesses required to solve the bingo are<br>
1 29 2 49 28 3 4 5 47 6 7 8 26 9 11 50 12 27 45 13 16 17 18 21 22 23 24 41 25<br>
Last 4 guesses are not required as after <strong>29</strong> guesses the bingo is,<br>
- - - -&nbsp; -<br>
- - - -&nbsp; 10<br>
- - - 14 15<br>
- - - 19 20<br>
- - - -&nbsp; -<br>
Here 2 rows and 3 columns are slashed (that is a total of 5 rows or columns are completely slashed)</p>

                                            </div>
