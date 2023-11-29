# Guesser-Game
Sure, here is a description of your guesser game formatted for a README.md file on GitHub:

**Guesser Game**

**Overview**

This Java program simulates a guessing game where a guesser tries to guess a number thought of by three players. The program is organized into three classes: Guesser, Player, and Umpire.

**Classes**

* **Guesser:** Represents the person who guesses the number. It has a method `guessNumber()` that prompts the user to enter a guess and returns the entered number.

* **Player:** Represents each of the three players who try to guess the number. It also has a method `guessNumber()` that prompts the user to enter a guess and returns the entered number.

* **Umpire:** Orchestrates the game. It has methods:
    * `collectNumFromGuesser()`: Calls the `guessNumber()` method of the `Guesser` class to collect the guesser's guess.
    * `collectNumFromPlayer()`: Calls the `guessNumber()` method of each `Player` class to collect the guesses of the three players.
    * `compare()`: Compares the guesser's guess to the players' guesses and displays the results.

**Execution**

The main method of the `Launchgame` class creates an instance of the `Umpire` class and calls its methods to run the game.

**Experience**

* Object-oriented programming concepts
* Data structures
* Algorithms
* Exception handling

**Technologies**

* Java programming language
* Scanner class
* System.in input stream
