Number Guessing Game
This is a simple Number Guessing Game built in Python. The game generates a random number between 1 and 100, and the player tries to guess the number. The game provides feedback if the guess is too high or too low and counts the number of attempts the player took to guess the number.

Features
The computer randomly selects a number between 1 and 100.
The player has to guess the number.
The game gives hints like "Too high" or "Too low" after each guess.
The game ends when the player guesses the correct number, and it shows the total number of attempts.
Easy to play with basic terminal input and output.
How to Play
Run the program.
Enter your guess (a number between 1 and 100).
The program will provide feedback:
If the guess is too high, the program will display "Too high!".
If the guess is too low, the program will display "Too low!".
If the guess is correct, the program will congratulate you and display the total number of attempts you took.
After the correct guess, the game ends.
Sample Interaction
mathematica
Copy code
Guess the number between 1 and 100!
Enter your guess: 50
Too low!
Enter your guess: 75
Too high!
Enter your guess: 60
Too low!
Enter your guess: 65
Congratulations! You guessed the number in 4 attempts.
Project Structure
number_guessing_game.py: The main Python script for the game.
Prerequisites
Python 3: Make sure Python 3 is installed on your system.
How to Run
Clone or Download the Project:

bash
Copy code
git clone https://github.com/your-username/number-guessing-game.git
Navigate to the Project Directory:

bash
Copy code
cd number-guessing-game
Run the Game:

bash
Copy code
python number_guessing_game.py
Follow the on-screen instructions to play the game!

Code Explanation
random.randint(1, 100): Generates a random number between 1 and 100.
input(): Takes the player's guess as input.
if statements: Used to compare the guess with the randomly generated number and provide feedback ("Too high", "Too low", or "Congratulations!").
attempts: A variable that tracks how many guesses the player has made.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Author
Your Dhivashini R
Feel free to use and modify this project as you like. If you have any suggestions or improvements, feel free to create a pull request or open an issue.

Final Notes
This Number Guessing Game is a fun way to practice basic Python concepts such as loops, conditionals, and user input. It's perfect for beginners looking to enhance their Python skills with a simple project.

This README provides a comprehensive overview of the project, including how to play the game, how to run it, and an explanation of the code. You can modify the instructions according to your setup or hosting environment.











