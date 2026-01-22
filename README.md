# GuessingGame
Turbine \ Rust Lang \ Guessing Game Project

Here’s a clean, professional **`README.md`** file tailored for your GitHub repository based on the official [Rust Book – Chapter 2: Programming a Guessing Game](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html):

---

```markdown
# 🎲 Rust Guessing Game

A simple number guessing game built in Rust as part of **Chapter 2** of [*The Rust Programming Language* book](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html).

The program generates a random number between 1 and 100 and prompts the user to guess it. After each guess, it tells the player whether their guess was too high, too low, or correct. The game continues until the player guesses the secret number.

This project demonstrates core Rust concepts including:
- Variable binding and mutability (`let`, `mut`)
- User input with `std::io`
- Error handling with `Result` and `match`
- External crate usage (`rand`)
- Control flow with loops and pattern matching

---

## 🚀 How to Run

### Prerequisites
- [Rust](https://www.rust-lang.org/tools/install) (v1.70+ recommended)
- Cargo (comes with Rust)

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/guessing_game.git
   cd guessing_game
   ```

2. Build and run the game:
   ```bash
   cargo run
   ```

3. Follow the on-screen prompts to play!

---

## 🧪 Example Gameplay

```text
Guess the number!
Please input your guess.
50
You guessed: 50
Too big!
Please input your guess.
25
You guessed: 25
Too small!
Please input your guess.
37
You guessed: 37
You win!
```

---

## 📦 Dependencies

- [`rand = "0.8.5"`](https://crates.io/crates/rand) — for generating random numbers  
  *(Defined in `Cargo.toml`)*

---

## 📚 Learning Resource

This project is a direct implementation from:
> **[The Rust Programming Language — Chapter 2: Programming a Guessing Game](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html)**

Great for beginners learning Rust fundamentals!

---

## 📝 License

This project is educational and follows the examples from *The Rust Programming Language*, which is dual-licensed under [MIT](https://opensource.org/licenses/MIT) and [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
```

---

### ✅ Notes for You (Orkhan):
- Replace `your-username` in the clone URL with your actual GitHub username.
- This `README.md` aligns with your preference for **structured, clear, and reusable educational content**.
- You can place this file in the root of your `guessing_game` repository alongside `Cargo.toml` and `src/`.

Would you like a version that includes badges (e.g., build status, license), or instructions for contributors/reviewers?
