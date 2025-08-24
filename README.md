# Guess-game
Guess the Number Game 🎮 A simple web game made with HTML, CSS, and JavaScript, connected to Django as a template. The computer picks a number (1–100) and the player tries to guess it. The game gives feedback (Too high / Too low / Correct) and counts the attempts.
# 🎮 Guess the Number Game

A simple browser game built with **HTML, CSS, and JavaScript** and integrated into a **Django project** using templates.

## 📌 How to Play
- The computer randomly chooses a number between **1 and 100**.
- Enter your guess and click **Try**.
- The game will tell you if your guess is:
  - Too high 👆
  - Too low 👇
  - Correct 🎉 (and a new number will be generated).
- A counter shows how many attempts you made.
- Click **Reset** anytime to start a new round.

## 🚀 Run the Game
1. Make sure Django is installed.
2. Run the server:
   ```bash
   python manage.py runserver
