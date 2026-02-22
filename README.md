🎯 Number Guessing Game

A simple command-line Number Guessing Game built using Python where the computer randomly selects a number within a user-defined range, and the player tries to guess it with hints provided after each attempt.

This project demonstrates the use of loops, conditionals, user input handling, counters, and the random module in Python.

🚀 Features
1) User selects the difficulty level by defining the upper range
2) Random number generation using Python’s random module
3) Interactive guessing system
4) Hint system:
- "Bigger number please" if guess is too low
- "Lesser number please" if guess is too high
5) Tracks total number of attempts
6) Runs continuously until the correct number is guessed

🛠 Technologies Used
- Python 3
- Built-in random module

📂 How to Run the Project
- Clone the repository:
git clone https://github.com/your-username/your-repo-name.git

- Navigate to the project directory:
cd your-repo-name

- Run the script:
python number_guessing_game.py

🎮 How the Game Works
- The user enters the maximum range (starting from 1).
- The computer randomly selects a number within that range.
- The user keeps guessing until the correct number is found.
- The program provides hints after each incorrect guess.
- The total number of attempts is displayed at the end.

📸 Example Gameplay
- Enter the ending range of the guess (range starts from 1): 50
- Computer selected a number from 1-50, now it's your turn.

Enter the guessed number = 20
    Bigger number please

Enter the guessed number = 35
    Lesser number please

Enter the guessed number = 30
You got it right!

Number of turns = 3

🧠 Concepts Practiced
- while loop
- if-elif-else conditions
- Random number generation (random.randint)
- User input handling
- Integer conversion
- Counter variable usage
- Basic game logic implementation

📌 Future Improvements
1) Add limited number of attempts
2) Add difficulty levels (Easy/Medium/Hard)
3) Add replay option
4) Handle invalid (non-integer) input using try-except
5) Track best score
6) Convert to GUI version using Tkinter or PyQt

🎓 Learning Outcome
- This project strengthens understanding of Python fundamentals and logical thinking while building an interactive console-based game.

👨‍💻 Author:
Vikram Singh Kushwaha
