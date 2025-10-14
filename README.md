# Guess_the_number_game(Single & Multiplayer)

Guess game for solo and  multiplayer, written in Python
Try your gut and see who can make the greatest guesses by playing alone or with friends.
---

## 🕹️ Game mode

### 🧍 Single Player Mode
In this mode, you play against the computer.

- The computer randomly picks a number between a chosen range.
- You have a limited number of attempts to guess it.
- After each guess, you’ll get hints:
  - `"Too high!"` if your guess is greater than the number.
  - `"Too low!"` if your guess is smaller.
- The game ends when you guess correctly or run out of attempts.

**Function:** `guess_the_number(low=1, high=10, attempts=3)`

---

### 👥 Multiplayer Mode
Challenge your friends and see who guesses best!

- Supports **2 to 8 players**.
- Each player takes turns guessing the secret number.
- The game is played over multiple rounds.
- Players earn **1 point per correct guess**.
- A **leaderboard** is displayed after each round.
- Smart default attempts per player are calculated using the number range.

**Function:** `multiplayer_guess_the_number()`

---


## ⚙️ Features

✅ Input validation — prevents crashes from invalid inputs  
✅ Customizable range, attempts, and rounds  
✅ Automatic leaderboard and score tracking  
✅ “Hot/Cold” hints when guesses are close  
✅ Tie detection at the end of the game  
✅ Beginner-friendly and easy to extend

---


