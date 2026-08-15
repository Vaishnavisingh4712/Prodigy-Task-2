# Python Guessing game

A simple Number Guessing Game built using Python. The program generates a random number between 1 and 100, and the user has to guess the number. After each guess, the program provides feedback such as Too High or Too Low until the correct number is guessed.

📌 Features

- 🎲 Generates a random number between 1 and 100
- ⌨️ Accepts guesses from the user
- 📈 Provides Too High / Too Low feedback
- 🔢 Counts the total number of attempts
- ⚠️ Handles invalid input using "try-except"
- 🏆 Displays a success message when the correct number is guessed
- 🔄 Continues until the correct number is found

🛠️ Technologies Used

- Python 3
- "random" module
- Functions
- "while" loop
- "if-elif-else"
- "try-except"
- User input handling

🧠 How It Works

1. The program generates a random number between 1 and 100.
2. The user is asked to enter a guess.
3. The guess is compared with the generated number.
4. If the guess is smaller, the program displays "Too Low".
5. If the guess is larger, it displays "Too High".
6. The number of attempts is increased after every valid guess.
7. The game continues until the user guesses the correct number.
8. Finally, the total number of attempts is displayed.



▶️ How to Run

1. Clone the Repository

git clone <YOUR-GITHUB-REPOSITORY-URL>

2. Open the Project

cd guessing-game

3. Run the Program

python guessing_game.py

📸 Sample Output

Guess the Number!
I have selected a number between 1 and 100.

Enter your guess: 29
Too low! Try again.

Enter your guess: 40
Too high! Try again.

Enter your guess: 50
Too high! Try again.

Enter your guess: 35
Too high! Try again.

Enter your guess: 32
Too low! Try again.

Enter your guess: 34
Too high! Try again.

Enter your guess: 33
🎉 Correct! You guessed it in 7 attempts.

📚 Concepts Learned

- Python Functions
- Random Number Generation
- Loops
- Conditional Statements
- Exception Handling
- User Input
- Basic Problem Solving and Logic Building

🎯 Project Objective

The objective of this project is to practice Python programming fundamentals, logical thinking, loops, conditional statements, and exception handling by building an interactive command-line game.

👨‍💻 Author

Akarshit Srivastava

Built as part of the Prodigy Infotech Software Development Internship.

⭐ Acknowledgement

This project was developed as part of the Prodigy Infotech Software Development Internship.
