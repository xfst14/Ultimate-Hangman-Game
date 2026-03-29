**>>Welcome to the Ultimate Hangman Game!<<**

In this game, you are required to guess a word that directly relates to the current technological landscape, for as many consecutive rounds as possible. The game may look simple, but watch out - there may be dangerous traps you need to avoid when guessing a word - one wrong move, and the hangman is stuck at stake! 

**Prerequisites**

To play the game, you should have gcc installed on your computer (available on both MacOS, Linux and Windows), since an official .exe/.dmg/.deb/.rpm file is not yet published (although future GUI versions with executable files will be released)

**Installation**
1. To install the game, you should download the hangmangame.c file on your computer, then use your OS' terminal to head towards the folder/directory.

For Windows (depending on your hard drive name, whether it's C:, D:, ...): 
```
cd C:\path\to\your\folder
```
For MacOS/Linux/ChromeOS:
```
cd /path/to/your/folder
```

2. Compile the .c file via gcc:
```
gcc hangmangame.c -o your_file_name
```
3. Launch the game:
```
./your_file_name
```
**Game instructions**

There is a certain number of rounds in this game that you are required to overcome. 
For each round, you are required to guess a technology-based word, and you need to that across multiple rounds. 
You have a limited number of lives left (the lives will be reset in the next round). Guessing one wrong letter or an already guessed one can cost you a life.

**DISCLAIMER: if you lose all lives, you ALREADY LOSE the game (which means you are not allowed to advance into the next round)!**

*Tip: to save as many lives as possible during word-guessing sessions, you should guess the vowels first, then consonants later.*
