# Guess the Number

This is a simple command-line game written in Rust. The goal is to guess a random number between 1 and 100. The game will give you feedback on whether your guess is too high, too low, or correct.

## How to play

To play the game, you need to have Rust installed on your system. You can download Rust from https://www.rust-lang.org/tools/install . Then, follow these steps:

- Clone this repository or download the source code as a zip file.
- Navigate to the directory where the code is located and run `cargo build` to compile the code.
- Run `cargo run` to start the game.
- Enter your guess and press enter. The game will tell you if your guess is too high, too low, or correct.
- Repeat until you guess the correct number .

## Resource 
- For refernce or detailed explanation you can visit the offical rust documentation https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html .

## Features

This game demonstrates some of the features of Rust, such as:

- Using external crates with `Cargo.toml` and `cargo build`.
- Generating random numbers with the `rand` crate.
- Handling user input and output with the `std::io` module.
- Using variables, data types, expressions, and statements.
- Using control flow structures such as `loop`, `match`, and `break`.
- Handling errors with the `Result` type and the `expect` and `parse` methods.
- Using references and borrowing with the `&` and `mut` keywords.

## License

This project is licensed under the MIT License.
