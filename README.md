# CODTECH-Task1
Name: RIDDHI BANERJEE
Company: CODTECH IT SOLUTIONS
ID: CT08EYU
Domain: C PROGRAMMING LANGUAGE
Duration: December 20th,2024 to January 20th,2025
Project Overview: 
Simple Quiz Game in C
The goal of this project is to develop a simple quiz game using the C programming language. The game will present multiple-choice questions to the user, track their score, and provide feedback based on their answers. It will offer an interactive and engaging way for users to test their knowledge across different topics.

Key Features:
Multiple-Choice Questions: The game will present a set of predefined multiple-choice questions. Each question will have four answer options, with only one correct answer.
User Input: The player will choose an answer by entering a letter corresponding to the option (e.g., A, B, C, or D).
Score Tracking: The game will maintain a score that is incremented for each correct answer and will remain unchanged for incorrect answers.
Feedback: After each question, the game will provide immediate feedback, telling the player whether their answer was correct or incorrect. After the quiz is complete, a final score will be displayed.
Question Progression: The game will present one question at a time and move to the next question only after the player answers.
Game End and Results: Once all questions are answered, the game will display the total score and a message indicating the user’s performance, such as "Excellent," "Good," or "Try Again."

Structure and Flow:
Quiz Logic: After the user starts the quiz, the game presents each question one by one.
Answer Validation: The user selects an answer, and the game validates the response and increments the score if correct.
End of Quiz: After all questions are answered, the game displays the final score and a summary message.

Technologies used:
In this project, the primary technology used is the C programming language, which forms the foundation for developing the quiz game. Below is a breakdown of the specific technologies and concepts leveraged in the project:

1.C Programming Language
Overview: C is a widely-used, high-performance programming language that is known for its efficiency and control over system resources. It is commonly used for developing system software, applications, and games.
Role in the Project: The entire quiz game is written in C. The language provides a robust foundation for handling input/output, control flow, and managing variables, which are essential for developing the interactive nature of the quiz game.
Key Concepts Utilized:
Variables and Data Types: Variables store the user’s score, answers, and question data.
Control Structures: Conditionals (`if`, `else`) and loops (`for`, `while`) are used for branching logic and iterating through questions.
Functions: Modular programming with functions like `displayQuestion()`, `getAnswer()`, and `showResult()` to organize the game logic.
Structures (`struct`)**: A `struct` is used to hold and organize the data for each quiz question, including the question text, options, and correct answer.

 2. Standard Input/Output (I/O) in C
   Overview: The standard input and output mechanisms in C, such as `printf` for displaying messages and `scanf` for reading user input, are essential for interaction with the player.
   Role in the Project: 
     - `printf` is used to display the quiz questions, options, and feedback (correct/incorrect responses, score).
     - `scanf` is used to capture the user’s input (answer selection) and handle user interaction during the game.

3. Conditional Statements and Loops
   Overview: Conditional statements (`if`, `else`) allow the program to make decisions based on the user’s responses, while loops (`for`, `while`) allow repetitive tasks such as iterating over questions or 
   validating input.
   Role in the Project:
     Loops: The `for` loop is used to iterate through the list of questions, displaying each one to the user.
     Conditionals: They are used to check whether the user’s answer is correct, provide feedback, and keep track of the score. Additionally, they handle user input validation to ensure that the player selects a        valid option.

4. Input Validation
   Overview: Input validation is an important technique used to ensure that users enter only acceptable values.
   Role in the Project: The project handles invalid inputs (e.g., when the user enters something other than a number between 1 and 4) using a `while` loop and condition checks. This ensures the game runs smoothly 
   without crashing due to incorrect user inputs.

5. Data Structures
   Overview: In this project, we use structures (`struct`) to organize and store multiple related pieces of data.
   Role in the Project:
   Structs are used to define a Question, which holds:
       - The question text (`char[]` array).
       - The four options (`char[][]` array).
       - The correct answer (stored as an integer index of the correct option).
   - This enables easy management of quiz data and scalability (you can easily add more questions by expanding the array).
   - 
7. Compilers/IDEs
   Overview: C programs require a compiler to translate the source code into an executable file.
   Role in the Project:
   Compilers: Popular C compilers such as GCC (GNU Compiler Collection) or Clang are used to compile the C code into machine code that can be executed by the system.
     - Integrated Development Environments (IDEs): IDEs like Code::Blocks, Dev-C++, or Visual Studio Code can be used for writing, compiling, and debugging the C code. They provide features like syntax 
       highlighting, error detection, and easy project management.

Conclusion
The core technology used in this quiz game project is the C programming language, alongside essential programming concepts like functions, loops, conditionals, and structures. The project utilizes standard input/output mechanisms for user interaction and includes input validation to ensure smooth gameplay. Through these technologies, the project demonstrates the practical application of fundamental programming skills, providing an interactive and user-friendly quiz game experience.
