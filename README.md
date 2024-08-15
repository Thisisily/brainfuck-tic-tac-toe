# Tic-Tac-Toe in Brainfuck

## Introduction

This project implements an advanced version of the classic Tic-Tac-Toe game using the esoteric programming language Brainfuck. The game features move validation, win detection, draw detection, and a simple AI opponent.

## The Brainfuck Language

Brainfuck is an esoteric programming language created in 1993 by Urban Müller. It was designed to challenge programmers and to create a language with the smallest possible compiler.

### History

Müller's goal was to create a language with a compiler smaller than 1024 bytes. He succeeded, with the second version of the compiler being only 240 bytes in size. The name "Brainfuck" is a reference to the difficulty of programming in this language, as it's intentionally designed to be challenging and minimalistic.

### Language Basics

Brainfuck uses only eight commands, each represented by a single character:

- `>`: Move the pointer to the right
- `<`: Move the pointer to the left
- `+`: Increment the memory cell under the pointer
- `-`: Decrement the memory cell under the pointer
- `.`: Output the character signified by the cell at the pointer
- `,`: Input a character and store it in the cell at the pointer
- `[`: Jump past the matching `]` if the cell under the pointer is 0
- `]`: Jump back to the matching `[` if the cell under the pointer is nonzero

The language operates on an array of memory cells, each initially set to zero. Despite its simplicity, Brainfuck is Turing complete, meaning it can compute any computable function or simulate any other computational model, given enough time and memory.

## Game Features

Our Tic-Tac-Toe implementation includes:

1. Interactive gameplay
2. Move validation
3. Win detection
4. Draw detection
5. Simple AI opponent

## How to Play

1. Compile and run the Brainfuck code using a Brainfuck interpreter.
2. The game will display the initial empty board and instructions.
3. Enter numbers 1-9 to place your X in the corresponding cell.
4. The AI will automatically make its move after yours.
5. The game will announce the winner or a draw when the game ends.

## Code Structure

The Brainfuck code is structured as follows:

1. Initialization and board display
2. Main game loop
3. Move input and validation
4. Board update
5. Win and draw detection
6. AI opponent logic

## Conclusion

This project demonstrates the power and flexibility of Brainfuck, showing that even complex games can be implemented in this minimalistic language. It serves as both a programming challenge and an educational tool for understanding the fundamentals of computation.
