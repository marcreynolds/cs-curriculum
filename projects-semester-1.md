# 💻 Semester 1 Project Specifications: Programming Fundamentals

These are beginner-friendly Python project descriptions, each with clearly defined requirements, suggested features, and stretch goals. Designed to accompany the material from _Python Programming_ by John Zelle.

---

## 📊 Project 1: Grade Calculator (CLI)

### 📋 Objective

Create a command-line application that calculates a student’s final grade based on scores from multiple categories (e.g., assignments, quizzes, exams).

### ✅ Requirements

- Prompt user for grades in each category
- Apply configurable weightings (e.g., assignments = 30%, exams = 50%)
- Display a final numeric and letter grade (A–F)

### 🧰 Suggested Features

- Input validation (reject negative grades)
- Store multiple students' grades
- Read/write from a CSV file

### 🚀 Stretch Goals

- Create a menu system
- Use object-oriented design (`Student`, `Gradebook` classes)
- Support GPA calculation

---

## ✍️ Project 2: Mad Lib Generator

### 📋 Objective

Build a program that takes a Mad Lib-style template and asks the user to fill in words (e.g., noun, adjective) and then outputs the completed story.

### ✅ Requirements

- Display prompts for parts of speech
- Insert user responses into a story template
- Print the resulting story

### 🧰 Suggested Features

- Multiple story templates
- Randomly select a template
- Replay option

### 🚀 Stretch Goals

- Save completed stories to a text file
- Replace placeholders in external .txt files
- Use regular expressions to parse templates

---

## 🏦 Project 3: Bank Account Simulation

### 📋 Objective

Simulate basic banking operations using object-oriented design.

### ✅ Requirements

- Define a `BankAccount` class with methods: `deposit`, `withdraw`, `check_balance`
- Allow user to interact with the account via CLI
- Prevent overdrafts and invalid operations

### 🧰 Suggested Features

- Add an `InterestAccount` subclass
- Add transaction logging
- Display a statement summary

### 🚀 Stretch Goals

- Simulate multiple accounts with unique IDs
- Support saving/loading accounts to a file
- Add PIN/password protection

---

## 🎮 Project 4: Event-Driven Graphics Game

### 📋 Objective

Use Zelle’s graphics module to build a simple interactive graphical game.

### ✅ Requirements

- Use `graphics.py` for window and shape rendering
- Track mouse or keyboard events
- Update game state based on input (e.g., click a target)

### 🧰 Suggested Games

- Click-the-Target reflex game
- Pong (with simplified physics)
- Simple platformer with jumping

### 🚀 Stretch Goals

- Add sound effects (via external library)
- Display score and timer
- Modularize with classes (`GameObject`, `Player`, etc.)

---

## 📝 General Submission Guidelines

- Include a `README.md` for each project
- Use consistent naming and comments
- Store screenshots (if applicable)
- Push to GitHub with meaningful commit messages

---

Happy coding! 🧠💡
