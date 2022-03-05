# Hangman-Game
This is a excitement game made in python

 HANGMAN WIKI:
The origins of Hangman are obscure meaning not discovered, but it seems to have arisen in Victorian times, ” says Tony Augarde, author of The Oxford Guide to Word Games. The game is mentioned in Alice Bertha Gomme’s “Traditional Games” in 1894 under the name “Birds, Beasts and Fishes.” The rules are simple; a player writes down the first and last letters of a word and another player guesses the letters in between. In other sources, [where?] the game is called “Gallows”, “The Game of Hangin”, or “Hanger”.

IMPLEMENTATION

This is a simple Hangman game using Python programming language. Beginners can use this as a small project to boost their programming skills and understanding logic.

The Hangman program randomly selects a secret word from a list of secret words. The random module will provide this ability, so line 1 in program imports it.
The Game: Here, a random word (a fruit name) is picked up from our collection and the player gets limited chances to win the game.
When a letter in that word is guessed correctly, that letter position in the word is made visible. In this way, all letters of the word are to be guessed before all the chances are over.
For convenience, we have given length of word + 2 chances. For example, word to be guessed is mango, then user gets 5 + 2 = 7 chances, as mango is a five letter word.

EXPECTED OUTPUT

Guess the word! HINT: word is a name of a fruit
_ _ _ _ _ 

Enter a letter to guess: m
_ _ m _ _ 
Enter a letter to guess: o
_ _ m o _ 
Enter a letter to guess: l
l _ m o _ 
Enter a letter to guess: e
l e m o _ 
Enter a letter to guess: n
l e m o n 
Congratulations, You won!
