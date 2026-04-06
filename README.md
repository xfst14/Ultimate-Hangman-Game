**Welcome to the Ultimate Technology Hangman Game!**

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/a0d65820-d121-41b2-9f69-e904063265bd" />



In this game, you are required to guess a word that directly relates to the current technological landscape, for as many consecutive rounds as possible. The game may look simple, but watch out - there may be dangerous traps you need to avoid when guessing a word - one wrong move, and the hangman is stuck at stake! 

**Prerequisites**

No prerequisites required (except non-Debian distros, in which Flatpak is needed). If you want to download and play this game via Flatpak, please ensure to have Flatpak and the Flathub repo installed for maximmum compatibility.

For Fedora-based distros:
```
sudo yum install flatpak
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
```
For Arch-based distros:
```
sudo pacman -Syu
sudo pacman -S flatpak
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
```
For Gentoo-based distros:
```
emerge --ask --verbose sys-apps/flatpak
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
```


**Installation**

There are three methods to install the game: .exe file (on Windows), .deb file (Debian-based distros), .flatpak file (all Linux distros):

For the first two methods (.exe and .deb), all you need is to extract the file and seamlessly play the game.

In case for flatpak, you need to download the .flatpak file first, then extract the game using the following commands:

```
flatpak install --user hangmangame.flatpak
```
Then you can finally run the game:
```
flatpak run io.github.xfst14.Hangman
```


**Game instructions**

There is a certain number of rounds in this game that you are required to overcome. 
For each round, you are required to guess a technology-based word, and you need to that across multiple rounds. 
You have a limited number of lives left (the lives will be reset in the next round). Guessing one wrong letter or an already guessed one can cost you a life.

**DISCLAIMER: if you lose all lives, you ALREADY LOSE the game (which means you are not allowed to advance into the next round)!**

*Tip: to save as many lives as possible during word-guessing sessions, you should guess the vowels first, then consonants later.*
