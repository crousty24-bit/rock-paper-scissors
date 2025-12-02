# rock-paper-scissors



* First JS Odin Project : *"Write a rock-paper-scissors game played against the computer."*



We need code to return the computer choice between "rock", "paper", "scissors", randomly.

We need code to return player's choice.

The game is played round by round, keeps players score : 5 rounds played to declared a winner.

This game as no GUI, it's only played via the console.

Need input for the player's choice (prompt).

Need conditions to compare rock < paper ; scissors > paper, etc.







# **PLAN**



* I'll go step-by-step :



1. **Setup project structure ✅**
2. **Read assignment carefuly, write your plan ✅**
3. **Write the solution and the pseudocode ✅**
4. **Go code each function, one a the time, test it, then go to the next one.✅**
5. **If something isnt working : problem solving process (debugging) until it's fixed.**
6. **Make sure everything is in place, playtest it.**



##### 

##### Pseudocode :



1. ###### GET the computer's choice randomly between 3 values (rock, paper, scissors)
2. ###### GET the player's choice with user's input (prompt)
3. ###### WHILE both choices are set, plays one round to determine which one is greater than the other :
4. ###### IF choices are the same, its a tie and sequence repeat
5. ###### ELSE IF one choice is greater than the other one

######  	- the greater one wins and score 1 point (Computer VS Player score)

######  	- next sequence

###### 6\. REPEAT for 5 rounds then determine the winner (higher score)

###### 7\. THEN END SEQUENCE and start a new game reset







# **DIVIDE \& CONQUER**



* Step 1 is done : get the computer's choice is working **✅**
* Step 2 is done : get the player's choice is working **✅** (for now..) : 2 func variants
* Step 3 is done : func playRound is working **✅** func human choice is case sensible **✅** also returns null if answer not whats expected
* Step 4 is done : get the player and computer's scores, incr by 1 each time a round is played **✅**
* Step 5 working on : func game loop => its looping currently but still need to set it for 5 rounds ! 
* Step 6 









