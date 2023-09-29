This is a game of rock, paper, scissors.

You might find it fairly impressive that--as a beginner--I made this game off of one commit; however, I've made a project like this before while using Python. Of course, the syntax was quite different, but I'd like to thank my prior experience with python to push through this one.

The code makes a blank html page and takes user input with a prompt and the game does this for 5 rounds. Each time, the computer picks a random integer from 0-2 (to which, translates to: rock, paper, or scissors) and the game makes a comparison and decides who's the eventual victor. There's comments in the code to explain the functions and code by declaration and coding block, respectively. However, I'd also like to share in this README how I came up with the logic to break the project down! I must admit though, I may have deviated from the pseudocode, but I hope this could help anyone out that may be struggling with this! Here it is:

create a function called getComputerChoice that randomly returns rock paper or scissors

write another function that plays a single round of rock paper scirrors with two parameters playerSelection and computerSelection that also returns a string of the winner (be sure to make playersection case insensitive)

write a new function called game() and use the previous function inside this one to play five rounds that keeps score and reports a winner or lose at the end

create getComputerChoice
create variable that picks a number between 1 and 3
if the number is 1
return rock.
if the number is 2
return paper
if the number is 3
return scissors.

create playRound(playerSelection, computerSelection)
run the getComputerChoice function
if playerselection is equal to the losing position and the playerselection is equal to the winning position
return the string
else if vice versa
return the string
else
return try again
