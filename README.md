Tetris Game Project

Bahria University Islamabad - Department of Computer Science  
Project Date: December 28, 2023  
Developed by:  
- Syeda Ammal Asim 
- Haseeb Ullah Khan 

Project Overview

This project is a C++ implementation of the classic Tetris game, developed as part of our coursework in the Department of Computer Science at Bahria University Islamabad. It showcases our understanding of object-oriented programming (OOP), data structures, and algorithms through the creation of an interactive, graphical Tetris game.

Features

- User Authentication: Includes basic user registration and login for game access.
- Interactive Game Board: Displays the current game state, score, and active tetromino pieces.
- Tetromino Functionality: Random generation of tetromino shapes with movement (left, right, rotate) and locking mechanics.
- Line Clearing & Scoring: Completed lines are detected, cleared, and points are awarded.
- Graphical Interface: Utilizes the Simple and Fast Multimedia Library (SFML) for an engaging, graphical user experience.

System Design

The project applies key programming concepts, including:
- OOP Principles: Encapsulation, inheritance, polymorphism, and abstraction are integrated into the game’s design.
- Data Structures: 
  - Stack for tracking tetromino placement history.
  - Queue for managing upcoming tetromino pieces.

Installation

Prerequisites
- C++ compiler (Visual Studio Community 2022)
- SFML Library (available at https://www.sfml-dev.org/) for graphical rendering

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd tetris-game
   ```
3. Build and run the project:
   ```bash
   g++ -std=c++17 -o Tetris main.cpp -lsfml-graphics -lsfml-window -lsfml-system
   ./Tetris
   ```

How to Play

- Controls:
  - Use arrow keys to move the tetromino (left, right, rotate, and drop).
- Objective:
  - Stack the falling tetromino shapes to create complete lines, which will clear and earn points.
  - Avoid letting the pieces stack to the top of the board.

Project Structure

- Documentation: Project requirements, design, and timeline documentation.
- Source Code: Includes files for game logic, board display, and SFML setup.
- UML Diagrams: Class and system interaction diagrams for an overview of the OOP design.

Contributors

- Syeda Ammal Asim: Documentation, code for tetromino shapes and board display, file handling, and SFML integration.
- Haseeb Ullah Khan: Project conceptualization, movement logic, level and scoring system, and UML diagrams.

License

This project is for educational purposes as part of Bahria University coursework and is not intended for commercial use.
