# 🧮 Math Game (C# Console App)

A beginner-friendly **C# console application** that challenges users with the four basic math operations: addition, subtraction, multiplication, and integer-only division.  
Built as part of **The C# Academy** foundation series to reinforce C# fundamentals through hands-on coding.

---

## 📌 Features

- **Four basic operations**:
  - ➕ Addition
  - ➖ Subtraction
  - ✖️ Multiplication
  - ➗ Division *(integer results only)*
- **Integer-only division logic** — no fractional results (e.g., no `7 ÷ 2`)
- **Menu-driven interface** to:
  - Start a new game with a chosen operation
  - View game history from the current session
  - Exit the application
- **In-memory game history** — all results are stored in a `List` for the current run  
  *(Data is cleared once the program closes)*

---

## 🛠️ Tech Stack

- **Language:** C#
- **Framework:** .NET 6 / .NET 7 (Console App)
- **IDE:** Visual Studio / Visual Studio Code

---

## 📂 Project Structure

```
MathGame/
│
├── Program.cs          # Entry point and main game loop
├── Game.cs             # Game model to store results
├── GameService.cs      # Handles game logic and operations
├── MenuService.cs      # Displays and handles menu options
├── Utils.cs            # Helper methods for random number generation & validation
└── README.md           # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- [.NET SDK](https://dotnet.microsoft.com/download) (6.0 or later)
- A C# IDE (Visual Studio, Rider, or VS Code with C# extension)

### Installation & Running
```bash
# Clone the repository
git clone https://github.com/yourusername/MathGame.git
cd MathGame

# Build the project
dotnet build

# Run the game
dotnet run
```

---

## 🎮 How to Play

1. Run the application.
2. Choose a math operation from the menu:
   - **1**: Addition
   - **2**: Subtraction
   - **3**: Multiplication
   - **4**: Division (integer only)
   - **5**: View previous games
   - **0**: Exit
3. Solve the math problems presented.
4. Your results will be stored in a session history until you exit.

---

## 🏆 Example Gameplay

```
======================
  WELCOME TO MATH GAME
======================
1 - Addition
2 - Subtraction
3 - Multiplication
4 - Division
5 - View History
0 - Exit
======================
Choose an option: 4

What is 84 ÷ 7 ?
Your answer: 12
✅ Correct!

Play again? (y/n): y
...
```

---

## 🎯 Challenges (Optional)

These challenges help you push your skills further:

- ⏱ **Timed Mode**: Add a countdown timer for each question.
- 🎯 **Difficulty Levels**: Let users choose Easy, Medium, or Hard (affects number ranges).
- 📊 **Scoreboard**: Track total correct/incorrect answers per game.
- 💾 **Persistent History**: Save results to a file and load them on the next run.

---

## 📖 Learning Outcomes

By completing this project, you will:
- Understand **C# basic syntax** and control structures.
- Work with **Lists**, classes, and methods.
- Implement **menu-driven console applications**.
- Apply **input validation** and user interaction best practices.

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
