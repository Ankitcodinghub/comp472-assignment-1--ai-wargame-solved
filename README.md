# comp472-assignment-1--ai-wargame-solved
**TO GET THIS SOLUTION VISIT:** [COMP472 Assignment 1- AI Wargame Solved](https://www.ankitcodinghub.com/product/comp472-ai-wargame-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112280&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP472 Assignment 1- AI Wargame Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<h1>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; AI Wargame</h1>
AI Wargame<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> is a 2-player game played by an <em><sub>attacker </sub></em>(<sub>a</sub>) and a <em><sub>defender </sub></em>(<sub>d</sub>) on a 5 <em>× </em>5 board. A demo of the game is available at <a href="https://users.encs.concordia.ca/~kosseim/COMP472Fall2023/">https://users.encs.concordia.ca/</a><a href="https://users.encs.concordia.ca/~kosseim/COMP472Fall2023/"><em>∼</em></a><a href="https://users.encs.concordia.ca/~kosseim/COMP472Fall2023/">kosseim/COMP472Fall2023/</a>

Each player has 6 units on the board. These units can be of different types:

<strong>AI (</strong><strong><sub>A) </sub></strong>each player has only 1 AI unit. The goal of the game is to destroy the opponent’s AI.

<strong>Viruses (</strong><strong><sub>V) </sub></strong>are very offensive units; they can destroy the AI in 1 attack.

<strong>Techs (</strong><strong><sub>T) </sub></strong>are very defensive units, Tech and Virus are equal in combat against each other.

<strong>Programs (</strong><strong><sub>P</sub>) </strong>are generic soldiers.

<strong>Firewalls (</strong><strong><sub>F) </sub></strong>are strong at absorbing attacks, but weak at damaging other units.

Each unit has an associated health level, represented by an integer between [0…9]. Initially, all units have full health (9). When the health level of a Virus, a Tech, a Program or a Firewall reaches 0 or below 0, the unit is destroyed and removed from the board. If the health level of an AI reaches 0, then the player loses the game.

<h2>1.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Initial Configuration</h2>
At the beginning of a game, the attacker has 1<em><sub>×</sub></em>AI, 2<em><sub>×</sub></em>Viruses, 2<em><sub>× </sub></em>Programs and 1<em><sub>×</sub></em>Firewall; while the defender has 1<em><sub>×</sub></em>AI, 2<em><sub>×</sub></em>Techs, 2<em><sub>×</sub></em>Firewalls and 1<em><sub>×</sub></em>Program. The game starts with the following initial configuration:

<table width="688">
<tbody>
<tr>
<td width="209">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 4

A: dA9 dT9 dF9 .&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .
</td>
<td width="480"></td>
</tr>
<tr>
<td width="209">B: dT9 dP9 .&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .

C: dF9 .&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; . aP9

D:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; . aF9 aV9

E:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; . aP9 aV9 aA9
</td>
<td width="480">dA9, at <sub>A0</sub>, represents the defender (<sub>d</sub>)’s AI (<sub>A</sub>) and has a health of 9. aP9, at <sub>C4</sub>, represents the attacker (<sub>a</sub>)’s Program (<sub>P</sub>) and has a health of 9.

…
</td>
</tr>
</tbody>
</table>
The attacker starts the game.

<h2>1.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Actions</h2>
Each player take turn to play any of the following actions.

<strong>Movement </strong>A single unit can move to an adjacent position on the board. Rules to move a unit are the following: 1. The destination must be free (no other unit is on it).

<ol start="2">
<li>Units are said to be <em><sub>engaged in combat </sub></em>if an adversarial unit is adjacent (in any of the 4 directions).</li>
</ol>
If an AI, a Firewall or a Program is engaged in combat, they cannot move. The Virus and the Tech can move even if engaged in combat.

<ol start="3">
<li>The attacker’s AI, Firewall and Program can only move up or left. The Tech and Virus can move left, top, right, bottom.</li>
<li>The defender’s AI, Firewall and Program can only move down or right. The Tech and Virus can move left, top, right, bottom.</li>
</ol>
<strong>Attack </strong>A unit <em><sub>S </sub></em>can attack another unit <em><sub>T</sub></em>. Rules to attack a unit are the following:

<ol>
<li><em><sub>T </sub></em>must be adjacent to <em><sub>S </sub></em>in any of the 4 directions (up, down, left or right).</li>
<li><em><sub>T </sub></em>and <em><sub>S </sub></em>must be adversarial units (i.e. belong to different players).</li>
</ol>
A combat is bi-directional. This means that if <em><sub>S </sub></em>attacks <em><sub>T</sub></em>, <em><sub>S </sub></em>damages <em><sub>T </sub></em>but <em><sub>T </sub></em>also damages <em><sub>S</sub></em>.

Table 1 shows the damages inflicted to an adversary’s health during a combat.

Health values cannot go above 9 or below 0. If a unit’s health reaches 0, it is destroyed and eliminated from the board.

<strong>Repair </strong>A unit <em><sub>S </sub></em>can repair another unit <em><sub>T</sub></em>. Rules to repair a unit are the following:

<ol>
<li><em><sub>T </sub></em>must be adjacent to <em><sub>S </sub></em>in any of the 4 directions (up, down, left or right).</li>
<li><em><sub>T </sub></em>and <em><sub>S </sub></em>must be friendly units (i.e. belong to the same player).</li>
<li>The repair must lead to a change of health on <em><sub>T</sub></em>. Table 2 shows the change in health resulting from repairs. So for example,
<ul>
<li>a Tech cannot repair a Virus (see value 0 in Table 2). This is would be an invalid action.</li>
<li><em><sub>S </sub></em>cannot repair <em><sub>T </sub></em>if <em><sub>T</sub></em>’s health is already at 9. This is would be an invalid action.</li>
</ul>
</li>
</ol>
<strong>Self-Destruct </strong>Any unit can kill itself (and be removed from the board) and damage surrounding units.

Self-destruction removes the unit and inflicts 2 points of damage to all 8 surrounding units (if present). This includes diagonals and friendly units. Remember that health values cannot go above 9 or below 0. If the health of a unit reaches 0 or below 0, it is removed from the board.

<h2>1.3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; End of the Game</h2>
The game ends when a player loses their AI, or a pre-determined number of moves has been reached (e.g. 100). A player wins if their AI is alive while the other AI is destroyed; otherwise the defender wins (because the attacker started playing first).

Given that any unit can self-destruct, no player should be left in a position where no action is available to them.

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Your Task</h1>
In this project, you will implement an adversarial search to play the game of AI Wargame automatically. You will implement a minimax algorithm + alpha-beta pruning and at least 2 heuristics.

<h2>2.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Play Modes</h2>
Your program should be able to run in manual mode and in automatic mode. This means that you should be able to run your program with:

<ol>
<li>manual entry for both players (i.e. human vs human: H-H)</li>
<li>manual entry for one player, and automatic moves for the other (i.e. human vs AI: H-AI, AI-H)</li>
<li>automatic moves for both players (i.e. AI vs AI: AI-AI)</li>
</ol>
After each move, your program must display the new configuration of the board, and some statistics (see Section 2.5).

<h2>2.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Programming Environment</h2>
<ol>
<li>You must use GitHub to develop your project so we can monitor the contribution of each team member (make sure your project is private while developing).</li>
<li>To program the project, you can use any of the following languages: Python, Java, C, C++. If you wish to use another language, please check with me first (just send me an email). However, note that a significant skeleton of code written in Python 3.11 is available on Moodle. You can use this code as a starting point. If you wish to use another language, you will have to write on your own all the functionality provided in the Python skeleton.</li>
<li>If you do choose Python, if you wish, you can use the <sub>PyPy</sub><a href="#_ftn2" name="_ftnref2"><sup>[2]</sup></a> runtime instead of the regular <sub>CPython </sub>to make your code run faster, but be careful as <sub>Pypy </sub>is not compatible with all <sub>Python </sub></li>
</ol>
<h2>2.3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The Heuristics</h2>
Develop 2 different heuristics, <em><sub>e</sub></em><sub>1 </sub>and <em><sub>e</sub></em><sub>2</sub>, to play this game automatically. For deliverable D2 (see Section 3), you will need to implement and demo your code with the following heuristic:

<em>e</em><sub>0 </sub>= (3<em>V<sub>P</sub></em><sub>1 </sub>+ 3<em>T<sub>P</sub></em><sub>1 </sub>+ 3<em>F<sub>P</sub></em><sub>1 </sub>+ 3<em>P<sub>P</sub></em><sub>1 </sub>+ 9999<em>AI<sub>P</sub></em><sub>1</sub>) <em>− </em>(3<em>V<sub>P</sub></em><sub>2 </sub>+ 3<em>T<sub>P</sub></em><sub>2 </sub>+ 3<em>F<sub>P</sub></em><sub>2 </sub>+ 3<em>P<sub>P</sub></em><sub>2 </sub>+ 9999<em>AI<sub>P</sub></em><sub>2</sub>) where:

<em>V<sub>Pi </sub></em>= nb of Virus of Player <em><sub>i&nbsp;&nbsp; TPi </sub></em>= nb of Tech of Player <em><sub>i&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; FPi </sub></em>= nb of Firewall of Player <em><sub>i </sub>P<sub>Pi </sub></em>= nb of Program of Player <em><sub>i AIPi </sub></em>= nb of AI of Player <em><sub>i</sub></em>

<h2>2.4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The Input</h2>
It is not necessary to have a fancy user-interface. A simple command-line interface with a text-based I/O is sufficient. As long as your program supports the following input:

<h3>2.4.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Game Parameters</h3>
Your program must accept the following game parameters<a href="#_ftn3" name="_ftnref3"><sup>[3]</sup></a>.

<ol>
<li>The maximum allowed time (in seconds) for your program to return a move</li>
</ol>
Your AI should not take more than <sub>t </sub>seconds to return its move. If it does, your AI will automatically lose the game. This entails that even if your adversarial search is allowed to go to a depth of <sub>d </sub>in the game tree, it may not have time to do so every time. Your program must monitor the time, and if not enough time is left to explore all the states at depth <sub>d</sub>, it must interrupt its search at depth <sub>d </sub>and return values for the remaining states quickly before time is up.

<ol start="2">
<li>The maximum number of turns to declare the end of the game (see Section 3)</li>
<li>A Boolean to force the use of either minimax (<sub>FALSE</sub>) or alpha-beta (<sub>TRUE</sub>)</li>
<li>The play modes</li>
</ol>
Your program should be able to make either player be a human or the AI. This means that you should be able to run your program in all 4 combinations of players: H-H, H-AI, AI-H and AI-AI.

<h3>2.4.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Coordinates of Actions</h3>
Moves will be specified by the coordinates of the source <em><sub>S</sub></em>, then the coordinates of the target <em><sub>T </sub></em>(e.g. <sub>B2 B3</sub>).

<ul>
<li>If the target <em><sub>T </sub></em>is an empty cell, the action will be interpreted as a movement.</li>
<li>If the target <em><sub>T </sub></em>is an adversarial unit, the action will be interpreted as an attack.</li>
<li>If the target <em><sub>T </sub></em>is a friendly unit (=<em><sub≯ S</sub></em>), the action will be interpreted as a repair.</li>
<li>If <em><sub>T </sub></em>= <em><sub>S</sub></em>, the action will be interpreted as a self-destruction.</li>
</ul>
Coordinates will be specified by the row number (a letter <em><sub>∈ </sub></em>[<em><sub>A…E</sub></em>]), then the column number (an integer <em>∈ </em>[0<em><sub>…</sub></em>4]); for example, <sub>B3</sub>.

<strong>If a human player enters an illegal action </strong>(e.g. <sub>W3</sub>, the coordinates of a position that is not empty, a move of a unit engaged in combat …), then the human will only be warned and be given a chance to enter another move with no penalty<a href="#_ftn4" name="_ftnref4"><sup>[4]</sup></a>.

<strong>If your AI generates an illegal action </strong>it will automatically lose the game.

<h2>2.5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The Output</h2>
Your program should generate an output file with the trace of a single game. The name of these output files should follow the format: gameTrace-&lt;b&gt;-&lt;t&gt;-&lt;m&gt;.txt, where b is either false if alpha-beta is off or true if alpha-beta is active; <sub>t </sub>is the value of the timeout in seconds; and <sub>m </sub>is the max number of turns.

For example <sub>gameTrace-true-5-100.txt</sub>, is a game trace where alpha-beta is active, the timeout is 5 seconds for each turn, and the game ends after at most 100 turns. The trace should contain:

<ol>
<li>The game parameters (see Section 4.1):
<ol>
<li>the value of the timeout in seconds <sub>t</sub></li>
<li>the max number of turns</li>
<li>if a player is an AI, whether alpha-beta is <sub>on </sub>or <sub>off</sub></li>
<li>the play modes (eg. player 1 = AI &amp; player 2 = H)</li>
<li>in addition, if a player is an AI, indicate the name of your heuristic: <sub>e0</sub>, <sub>e1 </sub>or <sub>e2</sub></li>
</ol>
</li>
<li>The initial configuration of the board.</li>
<li>Then, for each action, display:
<ul>
<li>information about the action:
<ol>
<li>the turn number (eg. <sub>turn #1</sub>)</li>
<li>the name of the player (eg. <sub>Attacker</sub>)</li>
<li>the action taken (eg. <sub>move from C4 to C3</sub>)</li>
<li>if a player is an AI, the time for the action in seconds (eg. <sub>time for this action: 0.4 sec</sub>)</li>
<li>if a player is an AI, the heuristic score of the resulting board: (eg. <sub>heuristic score: -881</sub>) f) the new configuration of the board</li>
</ol>
</li>
<li>if a player is an AI, cumulative information about the game so far:
<ol>
<li>the number of states evaluated by the heuristic function since the beginning of the game (e.g.</li>
</ol>
</li>
</ul>
</li>
</ol>
Cumulative evals: 18.0M)

<ol>
<li>the same number as above but split over each depth (consider the starting node to be at depth 0)</li>
</ol>
(e.g. Cumulative evals by depth: 1=39 2=277 3=2.3k 4=17.9k 5=95.4k 6=6.5M 7=11.4M)

<ol>
<li>c) the same number as above but expressed as percentages</li>
</ol>
(e.g. Cumulative % evals by depth: 5=0.5% 6=36% 7=63%)

<ol start="4">
<li>d) the average branching factor: (e.g. <sub>Average branching factor: 4.8</sub>)</li>
</ol>
<ol start="4">
<li>The winner of the game (e.g. <sub>Defender wins in 37 turns</sub>)</li>
</ol>
<h1>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Evaluation Scheme</h1>
Students in teams can be assigned different grades based on their individual contribution to project. The team grade will count for 90% and the individual grade will count for 10%.

<table width="730">
<tbody>
<tr>
<td width="82"><strong>Deliverable</strong></td>
<td width="65"><strong>Deadline</strong></td>
<td width="151"><strong>Functionality</strong></td>
<td width="35"><strong>%</strong></td>
<td width="397"><strong>Evaluation Criteria</strong></td>
</tr>
<tr>
<td width="82">D1 + Demo 1</td>
<td width="65">see page 1</td>
<td width="151">manual&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; game:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; H-H

(no minimax, no heuristic)
</td>
<td width="35">30%</td>
<td width="397">Code (25%): functional criteria (I/O, functionality of the rules of the game, detection of illegal actions, output files …), programming quality.

Demo (5%): quality of the presentation, knowledge of the code and clarity of explanations, time management, team QA
</td>
</tr>
<tr>
<td width="82">D2 + Demo 2</td>
<td width="65">see page 1</td>
<td width="151">same as above + AI moves (minimax, alpha-beta, <em><sub>e</sub></em><sub>0</sub>, <em>e</em><sub>1 </sub>and <em>e</em><sub>2</sub>)</td>
<td width="35">45%</td>
<td width="397">Code (40%): functionality of minimax &amp; alpha-beta (generation and heuristic evaluation of states, return of the best action, …), quality of the heuristics, programming quality.

Demo (5%): quality of the presentation, time management, team QA
</td>
</tr>
<tr>
<td width="82">Tournament</td>
<td width="65">tbd</td>
<td width="151">same as above</td>
<td width="35">5%</td>
<td width="397">Participation at the tournament with a functional code (i.e. no crashing or other functional error). Your ranking at the tournament will not be evaluated, only your participation.</td>
</tr>
<tr>
<td width="82">D3</td>
<td width="65">see page 1</td>
<td width="151">same as above + Report</td>
<td width="35">10%</td>
<td width="397">Clarity of the report, justification of the heuristic, depth of the analysis, presentation, grammar, …</td>
</tr>
<tr>
<td width="82">Individual</td>
<td width="65"></td>
<td width="151"></td>
<td width="35">10%</td>
<td width="397">Peer-evaluation done after D1 and D3</td>
</tr>
<tr>
<td width="82">grade</td>
<td width="65"></td>
<td width="151"></td>
<td width="35"></td>
<td width="397">Contribution of each student as indicated on GitHub

Individual Q/A at demo 1 and demo 2 (correct and clear answers to questions, knowledge of the program, …).
</td>
</tr>
<tr>
<td colspan="2" width="147"></td>
<td width="151"><strong>Total</strong></td>
<td colspan="2" width="432">100%</td>
</tr>
</tbody>
</table>
<h2>3.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Demos</h2>
You will have to demo your project after each deliverable. Regardless of the demo time, you will demo the program that was uploaded by the submission deadline. The schedule of the demos will be posted on Moodle. The demos will consist of 2 parts: a presentation and a Q/A part.

<h3>Demo 1</h3>
□ Prepare a <em><sub>≈ </sub></em>5 minute presentation to explain your code and show its functionality.

□ After your presentation, your TA will proceed with a <em><sub>≈ </sub></em>10 minute question period. Each student will be asked questions on the code/project, and they will be expected to understand and explain any part of the code. Hence every member of team is expected to attend the demo.

□ At the end of the demo, your TA may ask you to generate output files (see Section 2.5) for specific game parameters (see Section 2.4.1). You will need to generate these files, and submit them on EAS.

<h3>Demo 2</h3>
□ Prepare a <em><sub>≈ </sub></em>5 minute presentation to explain your code and your heuristics <em><sub>e</sub></em><sub>1 </sub>and <em><sub>e</sub></em><sub>2</sub>. Discuss the effect of alpha-beta pruning and the quality of the heuristics. Show actual data to back up your claims.

□ After your presentation, your TA will proceed with a <em><sub>≈ </sub></em>10 minute question period. Each student will be asked questions on the code/project, and they will be expected to understand and explain any part of the code and any part of the analysis. Hence every member of team is expected to attend the demo.

□ At the end of the demo, your TA may ask you to generate output files (see Section 2.5) for specific game parameters (see Section 2.4.1). You will need to generate these files, and submit them on EAS.

<h2>3.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Tournament</h2>
We will organize an AI versus AI tournament. If you participate and your program does not crash or produces a functional error, then you get 5%. Your ranking at the tournament will not be evaluated, only your participation. More details on the tournament will be posted on Moodle.

<h2>3.3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Report</h2>
The last deliverable will be a 4-5 page report that describes your heuristics, analyses them with respect to one another and within the scope of the tournament, the effect of alpha-beta pruning on the efficiency and quality of the search etc Show actual data to back up your claims. Also provide an analysis of what you have learned, and a description of what you did right/wrong and what you would change if you were to redo the project today.

<h1>4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Submission</h1>
<h2>4.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Team Leader</h2>
If you work in a team, identify one member as the team leader and make sure this information is indicated in the Groups on the Moodle page. The only additional responsibility of the team leader is to upload all required files (including the files at the demo) from their account and book the demo on the Moodle scheduler.

<h2>4.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Submission Checklist</h2>
<strong>D1: </strong>□ Create one zip file containing your code, and a <sub>README </sub>file.

□ Name your zip file: 472 Project ID1 ID2 ID3.zip where ID1 is the ID of the team leader.

□ Have the team leader upload the zip file on <a href="https://fis.encs.concordia.ca/eas/">EAS</a> as Programming Project Group <strong><sub>1 </sub></strong>/ Submission Number <strong><sub>1</sub></strong>. During your actual demo with the TA: □ Generate the output files for the data that the TA will give you.

□ Create a zip file called: <sub>472 Demo1 ID1 </sub><sub>ID2 ID3 </sub>where <sub>ID1 </sub>is the ID of the team leader.

□ Have the team leader upload the zip file on <a href="https://fis.encs.concordia.ca/eas/">EAS</a> as Programming Project Group <strong><sub>1 </sub></strong>/ Submission Number <strong><sub>2</sub></strong>.

<strong>D2:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>same as D1, but have the team leader upload:

□ Upload the zip file on <a href="https://fis.encs.concordia.ca/eas/">EAS</a> as Programming Assignment Group <strong><sub>2 </sub></strong>/ Submission Number <strong><sub>1</sub></strong>.

□ Upload the demo output zip file on <a href="https://fis.encs.concordia.ca/eas/">EAS</a> as Programming Project Group <strong><sub>2 </sub></strong>/ Submission Number <strong><sub>2</sub></strong>.

<strong>D3:</strong>

□ Save your report in PDF format.

□ Name your report: 472 Report ID1 ID2 ID3.pdf where ID1 is the ID of the team leader.

□ Have the team leader upload the zip file on <a href="https://fis.encs.concordia.ca/eas/">EAS</a> as Programming Project Group <strong><sub>3 </sub></strong>/ Submission Number <strong><sub>1</sub></strong>.

Have fun!

<a href="#_ftnref1" name="_ftn1">[1]</a> Do not bother googling this game, I invented it.

<a href="#_ftnref2" name="_ftn2">[2]</a> <a href="https://www.pypy.org/">https://www.pypy.org/</a>

<a href="#_ftnref3" name="_ftn3">[3]</a> You do not need to check the validity of these input values; you can assume that they will be valid.

<a href="#_ftnref4" name="_ftn4">[4]</a> The point of this rule is to avoid losing a game in the tournament (see Section 3.2) because a human did not transcribe your AI’s action correctly.
