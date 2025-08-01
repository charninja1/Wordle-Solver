# Wordle-Solver
Solves wordle using DLV, a form of answer set programming. Averages around 4 guesses


# How it works
The wordle solver ranks all valid words with a score based on the freqeuncy each letter in the word appears in valid answers. The user then enters the word it returns into wordle, updates the clues file with the results, and runs the code again. The user keeps repeating this until the worlde is solved.

# To Use
The clues file is currently filled out as an example of how to fill it out. To use, the user must empty the clues file to start. Install DLV, run all five files together, and enter the result into wordle. Then update the clues file with the wordle clues, and run again. Enter the new word into wordle, update the clues file, and repeat until the wordle is solved. The wordle solver averages around 4 guesses per puzzle, sometimes finishing in much less, and sometimes not finishing in time
