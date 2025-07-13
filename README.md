Number Guessing Game (1–1000)
📌 Project Description:
This is a simple console-based number guessing game built using Python. The program generates a random number between 1 and 1000, and the user is prompted to guess it. 
After each guess, the program gives feedback — whether the guess is too high or too low 
until the correct number is guessed. It also tracks the number of attempts taken to find the correct answer and displays it when the user wins.

🛠️ Technologies Used:
The project is developed using Python. It utilizes the built-in random module to generate random numbers and handles user input through the console using input(). 
Error handling is implemented using try-except to manage invalid (non-integer) inputs.

📁 How It Works:
The program generates a random integer between 1 and 1000.

The user is asked to guess the number.

After each guess, the program gives a hint:

“Too low!” if the guess is less than the number.

“Too high!” if the guess is more than the number.

If the guess is correct, it congratulates the user and displays the number of attempts taken.

If the input is not a number, it shows an error message and prompts again.

