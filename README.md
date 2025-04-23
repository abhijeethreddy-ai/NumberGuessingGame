# Number Guessing Game - Java

This is a simple **Number Guessing Game** built using Java. It randomly selects a number between 1 and 100, and the user must guess it. After each guess, the program provides feedback on whether the guess was too high or too low.

---

## 📁 Package Structure

The program is part of the `day7` package:
day7/ └── NumberGuessingGame.java

yaml
Copy
Edit

---

## 🎮 How to Play

1. Run the program.
2. Try to guess the number between 1 and 100.
3. The program will guide you by saying:
   - "Too low. Try again." if your guess is less than the target.
   - "Too high. Try again." if your guess is more than the target.
   - "Congratulations!" if you guessed correctly.

---

## 🧑‍💻 How to Compile and Run

### Using Terminal / Command Prompt:

```bash
cd path/to/your/project
javac day7/NumberGuessingGame.java
java day7.NumberGuessingGame
Make sure you are in the root folder that contains the day7 directory.

✅ Requirements
Java JDK 8 or higher

Terminal or IDE (like IntelliJ, Eclipse, or VS Code with Java support)

📌 Features
Random number generation between 1 and 100

Feedback after each guess

Tracks the number of attempts

Simple console-based interaction

