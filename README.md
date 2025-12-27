# guess-the-number-js
# 🎯 Guess the Number (JavaScript Logic Game)

This project was developed during a **JavaScript Logic course from Alura**.

The course focus was **JavaScript logic**, not HTML or CSS.  
The HTML and CSS were provided by the course, and the main goal was to understand how to build game logic using **pure JavaScript**.

The game challenges the player to guess a secret number, receiving feedback until the correct number is found.

---

## 🧠 What this project is about

This is a simple number guessing game where:

- The program generates a **random secret number**
- The player tries to guess the number
- The game gives hints whether the guess is **higher or lower**
- The game keeps running until the correct number is guessed
- At the end, the total number of attempts is shown

---

## 📚 What I learned in this project

This project helped me practice core **JavaScript logic concepts**, including:

- ✅ Variables (`let`)
- ✅ Comparison operators
- ✅ `while` loops
- ✅ Conditional statements (`if / else`)
- ✅ Ternary operator
- ✅ Random number generation with `Math.random()`
- ✅ User interaction using `alert()` and `prompt()`
- ✅ Counting attempts and controlling program flow

---

## 🧩 Code logic explained

Here is a high-level explanation of how the code works:

1. The game starts by welcoming the player with an alert message.
2. A maximum number is defined (`numeroMaximo = 100`).
3. A random secret number is generated using `Math.random()`.
4. A `while` loop keeps asking the player to guess a number until the correct one is found.
5. Inside the loop:
   - The player enters a number using `prompt()`
   - The program checks if the guess is correct
   - If not, it tells whether the secret number is higher or lower
   - The number of attempts is counted
6. When the correct number is guessed:
   - The loop ends
   - A final message shows the secret number and how many attempts were needed
   - A ternary operator is used to correctly display "tentativa" or "tentativas"

---

## 🛠️ Technologies used

- JavaScript (Vanilla JS)
- HTML (provided by the course)
- CSS (provided by the course)

---

## 🚀 How to run the project

1. Clone the repository:
   ```bash
   git clone https://github.com/LuaFurtado/guess-the-number-js.git
