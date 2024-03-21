**CodTech IT Solutions Internship- Number Guessing Game Documentation**

**Internship Project Overview:**
- **Company Name:** CodTech IT Solutions
- **Intern's Name:** P. Sri Vaishnavi
- **Project Title:** Number Guessing Game

**Introduction:**
CodTech IT Solutions presents an exciting internship opportunity focusing on Java programming skills through the development of a Number Guessing Game. This project aims to provide interns with hands-on experience in Java programming, enhancing their problem-solving abilities, and familiarizing them with software development practices.

**Objective:**
The primary objective of this internship project is to develop a Java-based Number Guessing Game. Through this project, interns will:
1. Gain proficiency in Java programming.
2. Understand fundamental programming concepts such as loops, conditionals, and user input.
3. Enhance problem-solving skills through practical implementation.
4. Learn software development practices including code documentation and version control.

**Project Overview:**
The Number Guessing Game is a simple interactive game where the computer generates a random number and the player has to guess it within a certain number of attempts. The game provides feedback to the player on whether their guess is higher or lower than the target number until they either guess correctly or exhaust their attempts.

**Features:**
1. **Random Number Generation:** The computer generates a random number within a specified range.
2. **User Input:** Players can input their guesses.
3. **Feedback Mechanism:** The game provides feedback on whether the guess is too high, too low, or correct.
4. **Number of Attempts:** Players have a limited number of attempts to guess the correct number.
5. **Validation:** Input validation ensures that only valid inputs are accepted.
6. **End of Game:** The game ends when the player correctly guesses the number or exhausts all attempts.

**Implementation Details:**

1.**generateRandomNum() Method:**
This method generates a random number between 1 and 100 using the Math.random() function and converts it into an integer.
The generated random number represents the computer's choice for the player to guess.

2.**enterNumber() Method:**
This method prompts the player to enter their guess within the range of 1 to 100.
It utilizes the Scanner class to capture user input from the console.

4.**Main Method:**
The main method orchestrates the flow of the game.
It initializes variables such as the number of attempts and the computer's randomly chosen number.
Within a do-while loop, it continuously prompts the player to guess the number and provides feedback until the correct number is guessed or the maximum number of attempts is reached.

**User Interaction:**
Upon running the program, the user is greeted with a welcoming message and informed about the number of attempts available.
The user is prompted to enter their guess through the console.
After each guess, the program informs whether the guess was too high, too low, or correct.
If the user guesses correctly within the given attempts, a winning message is displayed. Otherwise, a "Game Over" message is shown.

**Conclusion:**
The Number Guessing Game project demonstrates fundamental programming skills in Java, including user input handling, random number generation, and logical decision-making. It serves as a practical example of object-oriented programming principles and provides an interactive experience for the user. This project reflects the applicant's proficiency in Java development and problem-solving abilities, making it a suitable demonstration for the internship application at CodTech IT Solutions.
This documentation outlines the structure, features, and flow of the Number Guessing Game project, showcasing its functionality and purpose in the context of the internship application.
