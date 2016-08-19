# Hangman
A Python script that simulates  the 'Hangman' game. 

# Overview -
1. Hangman game requires the user to guess a particular word/s by entering single letter every time the imput prompt appears.
2. The user has 8 lives to correctly guess the name. Each life is reduced if the currently guessed letter doesnt exist in the unknown string.
3. The unknown string used in this script are movie names , found in the 'movie.txt' file.
4. 'hangman.txt' contains the 8 different stages of the 'hangman' pattern used to depict the 8 different stages of available lives .
5. 'movie.txt' can be modified to contain as many movies as the user requires . The script chooses a random movie name from the file .
6. If there are multiple words in the movie name , ex - The Martian , then the displayed unknown string will be in the format of 
   ' - - - / - - - - - - - ' . The dashes represent the letters and slashes represent the whitespace between two words.
7. On entering a valid letter , the dashes are replaced by the letter , wherever they occur in the original movie name.

# Requirements -

1. Python 3.0 or higher.
2. Python modules - os , random . They can be installed using the ' pip install module-name' command .
3. Text editor - to store the movie names and the hangman patterns.

Note :- Run the script from the command line or the '.bat' file for better experience.
