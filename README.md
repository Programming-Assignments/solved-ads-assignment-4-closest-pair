Download Link: https://assignmentchef.com/product/solved-ads-assignment-4-closest-pair
<br>
It is now spring and what would be a better activity than to have a water gun fight? Thinks everyone else. Who would even like to be hit by water though?, you think. Instead you, godlike as you are, take a step up above the petty human beings and observe this crazy game (from a cloud high above, also known as a balcony with a great view). Shortly you get bored out of you mind and decide to create a betting game with your friend.

After having observed the game for a while you think you have figured out the rules. Each minute all players have to stop somewhere in the field where they play and shoot exactly one shot at someone else. As the guns are not made for shooting long distance everyone tries to hit the very closest person. Before everyone shoot you and your friend will play a game. You win if you can name two people who both will shoot at each other, and otherwise you friend wins.

You soon realize that this is an easy task, since of course the two people with the shortest distance (among all distances between pairs of players) between them obviously will shoot at each other. But as you also like to win you do not tell your friend, of course. So, what is the closest distance between any two players? If you can only answer this question, then the victory will be yours!

<h1>Aims</h1>

The goals of the lab are:

<ul>

 <li>Implementing a divide and conquer algorithm solving the Closest Pair problem.</li>

 <li>Debugging your code.</li>

 <li>Structuring your code in a logical fashion.</li>

 <li>Reason about correctness of your algorithm.</li>

 <li>Reason about upper bounds for time complexity.</li>

</ul>

<h1>Problem formulation</h1>

You are given the coordinates of the <em>N </em>people participating in the silly water pistol battle. You should calculate the minimal distance between two people on the battle ground.

<h1>Input</h1>

The first line of input consists of a single integer, 2≤ <em>N </em>≤10<sup>6</sup>, the number of players. Then follow <em>N </em>lines, the <em>i</em>-th line containing two integers, the <em>x</em>– and <em>y</em>-coordinates of the <em>i</em>-th player. All coordinates have absolute value less than 10<sup>9</sup>.

<h1>Output</h1>

The output should contain a single floating point number containing the shortest distance between two players on the battle field. The output should be a floating point number rounded to exactly 6 decimal digits.

<h1>Examination and Points of Discussion</h1>

To pass the lab make sure you have:

<ul>

 <li>Have successfully implemented the algorithm with the correct time complexity.</li>

 <li>Have neat and understandable code.</li>

 <li>Have descriptive variable names.</li>

 <li>Have filled in the blanks in the report.</li>

 <li>Have run the check_solution script to validate your solution.</li>

</ul>

During the oral presentation you will discuss the follwoing questions with the lab assistant:

<ul>

 <li>What is the time complexity, and more importantly why?</li>

 <li>Why is it sufficient to check a few points along the mid line?</li>

 <li>Draw a picture and show/describe when each distance is checked in your solution!</li>

 <li>When do you break the recursion and use brute force?</li>

</ul>

<strong>Sample Input 1                                                                                 Sample Output 1</strong>

<table width="622">

 <tbody>

  <tr>

   <td width="311">40 10     01     01 1</td>

   <td width="311">1.000000</td>

  </tr>

 </tbody>

</table>

<strong>Sample Input 2                                                                                 Sample Output 2</strong>

<table width="622">

 <tbody>

  <tr>

   <td width="311">40 -1-1 00     11     0</td>

   <td width="311">1.414214</td>

  </tr>

 </tbody>

</table>


