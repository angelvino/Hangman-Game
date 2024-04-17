**Project Overview:
Game Objective:**
The player must guess a randomly selected country name by suggesting letters within a limited number of attempts.

**Gameplay Mechanics:**

The game begins by randomly selecting a word (country name) from a predefined list.
The word to guess is represented by a series of asterisks that correspond to each letter of the word.
The player is allowed up to 5 incorrect guesses, which are counted when a suggested letter does not appear in the word.
If a player's guess is correct, the corresponding asterisk(s) is replaced with the correctly guessed letter.
The game continues until the player either guesses the country name correctly or exhausts the allowed number of incorrect guesses.

**Key Features:**

**Random Word Selection:**
The game includes a list of 10 country names. Each game session begins with the program randomly selecting one of these countries as the target word to guess.

**User Interaction:**
Players interact with the game through the console, entering guesses and receiving feedback on their progress.
Feedback includes notifications of correct or incorrect guesses, the current state of the word (revealed letters and remaining asterisks), and the number of guesses remaining.

**End of Game:**
The game ends either when the player correctly guesses the country name or fails to guess correctly after 5 incorrect attempts.
Upon game completion, the player is shown a message indicating whether they won or lost, and the correct word is displayed.

**Implementation Details:
Technologies Used:**

The game is entirely written in C++ and uses standard libraries such as iostream for input/output operations and cstdlib/cctime for random number generation.
Functions:
letterFill(char, string, string&): Checks if a guessed letter is in the secret word, updates the word display with correct guesses, and ensures the same letter isn’t guessed multiple times.

**Execution Flow:**

Initialization of variables and selection of a random word.
Execution of a loop that continues until the player has either guessed the word or exceeded the maximum number of wrong guesses.
Collection of user input and updating of game state based on the correctness of the player's guesses.

**Developer Notes:**

The program is a straightforward example of basic C++ capabilities, including loops, conditionals, function usage, and basic data handling.
Potential enhancements could include more sophisticated data structures for handling words, additional features like hint giving, or graphical user interface implementation.
This Hangman game is an ideal project for beginners looking to practice fundamental programming concepts in C++, especially related to strings, loops, conditionals, and user input handling.

**OUTPUT**

![image](https://github.com/angelvino/Hangman-Game/assets/109471128/cedc3df4-aac4-4596-aafe-b129742ab794)
