After downloading the code, you can run HangmanGame from the command line.  The command used is ./HangmanGame.  When the game starts, one player should input a word for the second player to guess.  After all the letters are entered, press the enter key.  Then, the second player can start guessing letters.  Seven incorrect guesses are allowed before the player loses the game.  Guesses of the same letter do not penalize the player, but have no positive effect either.  The game resets after a word is guessed or the game is lost, and it can continuously be played in this manner. 

* If the executable is not able to run as soon as the code is downloaded, try to compile like this: g++ Hangmain.cpp Hangman.cpp Hangman.h -o HangmanGame
Now you should be able to simply run ./HangmanGame
