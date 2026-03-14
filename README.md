#The-Java-Guesser
#Main Program
##Start program.
##Display the menu:
##0) Exit
##1) Human Guesser
##2) Computer Guesser
##Ask the user to enter a number from 0–2.
##If the user enters 1, run the Human Guesser game.
##If the user enters 2, run the Computer Guesser game.
##If the user enters 0, exit the program.
##Repeat the menu until the user chooses 0.

#Human Guesser Algorithm
##Generate a random number between 1 and 100.
##Set a guess counter to 1.
##Ask the user to guess the number.
If the guess is lower than the number:
Print "too low..."
If the guess is higher than the number:
Print "too high..."
If the guess is correct:
Print "got it!"
Print "Very good!"
End the game.
Increase the guess counter.
Repeat until the correct number is guessed.

Computer Guesser Algorithm
Ask the user to think of a number between 1 and 100.
Set the lowest possible number to 1.
Set the highest possible number to 100.
Set the guess counter to 1.
Computer guesses the middle number of the range.
Ask the user if the guess is:
H → too high
L → too low
C → correct
If the guess is too high, adjust the highest number.
If the guess is too low, adjust the lowest number.
If the guess is correct, end the game.
Increase the guess counter.
Repeat until the correct number is found.
