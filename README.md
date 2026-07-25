# Connect-four-Game
A browser-based Connect Four game built using HTML, CSS, and JavaScript featuring two-player gameplay, automatic piece placement, horizontal, vertical, and diagonal win detection, and an interactive responsive game board.

# Description
This project is a browser-based implementation of the classic Connect Four game developed using HTML, CSS, and JavaScript. It provides a two-player gaming experience where players take turns dropping colored pieces into a 7-column, 6-row game board. The game automatically detects horizontal, vertical, and diagonal winning combinations, announces the winner, and prevents further gameplay after a player wins. The project demonstrates fundamental game development concepts including dynamic board generation, event handling, game state management, and win-condition algorithms.

# Features
Classic two-player Connect Four gameplay
Interactive 6×7 game board
Automatic turn switching between Red and Yellow players
Dynamic piece placement with gravity simulation
Horizontal, vertical, and diagonal win detection
Real-time winner announcement
Prevents additional moves after the game ends
Clean and responsive user interface
Fully browser-based with no external libraries required
# Technologies Used
HTML5
CSS3
JavaScript (ES6)
# Project Structure
📁 Connect-Four
│
├── index.html        # Main game interface
├── c_style.css       # Game board styling and UI
├── c_script.js       # Game logic and winner detection
└── README.md
# Project Overview

The Connect Four game recreates the classic strategy board game in a web browser. Players alternate turns by selecting a column where their colored piece is automatically placed in the lowest available position. JavaScript manages the game board as a two-dimensional array, tracks player turns, updates the interface dynamically, and continuously checks for winning combinations after every move. Once four consecutive pieces of the same color are connected horizontally, vertically, or diagonally, the game announces the winner and ends the match.

# Key Functionalities
Dynamically generates a 6-row by 7-column game board.
Simulates gravity by placing pieces in the lowest available position.
Alternates turns between Red and Yellow players.
Detects horizontal winning sequences.
Detects vertical winning sequences.
Detects both diagonal and anti-diagonal winning combinations.
Displays the winning player instantly.
Disables further gameplay once a winner is declared.
# Learning Outcomes

This project demonstrates practical knowledge of:
HTML structure and dynamic element creation
CSS layout and game board styling
JavaScript DOM manipulation
Event handling
Two-dimensional arrays
Game state management
Win-condition algorithms
Interactive browser game development
# Future Enhancements
Restart/New Game button
Draw (tie) detection
Scoreboard for multiple rounds
Single-player mode with AI opponent
Animated piece drop effect
Sound effects and background music
Difficulty levels for AI gameplay
Responsive design for mobile devices
Highlight the winning four connected pieces
