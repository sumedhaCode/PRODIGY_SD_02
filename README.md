# PRODIGY_SD_02
# 🎯 Guessing Game – Full Stack Project

This is a full-stack **Guessing Game** built as part of Task-02 at **Prodigy Infotech**. The app challenges users to guess a randomly generated number with real-time feedback until they win. And when they do… 🎉 there's confetti to celebrate!

## 📌 Problem Statement
> Create a program that generates a random number and challenges the user to guess it. After each guess, the program should tell the user if the guess was too high or too low, and continue until the correct number is guessed. Finally, display the total number of attempts it took to win the game.

---

## 🛠️ Tech Stack-----

### 🔹 Backend
- **Java**: Core game logic using `Random`, `Scanner`, and loops
- **Node.js**: REST API to relay user guesses and send back real-time responses

### 🔹 Frontend
- **React.js**: Interactive UI for user inputs and feedback
- `react-confetti`: Confetti animation on winning
- `@react-hook/window-size`: Responsive confetti display

## ✨ Features

- ✅ Real-time feedback: too high / too low
- 🔁 Reset button for replaying the game anytime
- 🎉 Confetti on correct guess
- 🌈 Gradient background theme for a warm and playful experience
- 🧠 Attempts counter to track user performance

---

## 🚀 How to Run

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/guessing-game
cd guessing-game

2. Start the Backend Server
bash
cd guessing-game-server
npm install
npm start

3. Start the Frontend
bash
cd guessing-game-ui
npm install
npm start
Make sure your backend runs on http://localhost:5000 and React app on http://localhost:3000.


🤓 What I Learned
Full-stack app structure and communication flow

State management and dynamic feedback in React

API setup and request handling using Express

UI enhancements with animations and responsive design...
