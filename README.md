# Minesweeper Game

## Overview

This Java application is a recreation of the classic Minesweeper game, featuring adjustable difficulty levels and a graphical user interface built using Java Swing. Players can uncover squares on the grid, avoid mines, and use flags to mark potential mine locations. The game includes a timer and supports different grid sizes based on the selected difficulty level.

## Features

- **Adjustable Difficulty Levels:** Three difficulty settings (Beginner, Intermediate, Expert) alter the grid size and number of mines.
- **Interactive UI:** A user-friendly interface with buttons and icons for gameplay interactions.
- **Timer:** Tracks the duration of the current game session.
- **Custom Icons:** Utilizes custom icons for mines, flags, and various number clues.
- **Game Status Indicators:** Icons change based on the game's state (playing, win, or loss).

## How to Play

- **Left Click:** Reveals what is under a tile.
- **Right Click:** Places a flag on a tile to indicate a suspected mine.
- **Reset Button:** Starts a new game and resets the timer and game grid based on the current difficulty level.
- **Difficulty Selection:** Choose your difficulty level from the menu to adjust the challenge.

## Setup and Running the Application

### Prerequisites

- Java Development Kit (JDK) installed on your machine.
- Basic knowledge of running Java applications.

### Running the Game

1. **Compile the Java File:**
   - Navigate to the directory containing `Minesweeper.java`.
   - Compile the file using the command:
     ```bash
     javac Minesweeper.java
     ```
2. **Run the Compiled Class:**
   - Start the game using the command:
     ```bash
     java Minesweeper
     ```
   - The game window will open, and you can select your difficulty and start playing.

### Controls

- **Beginner:** 9x9 grid with 10 mines.
- **Intermediate:** 16x16 grid with 40 mines.
- **Expert:** 16x40 grid with 99 mines.

## Screenshots

*Include screenshots of your application here.*

## Customization

- **Icon Customization:** You can replace the icons used for mines, flags, and the face button by replacing the corresponding `.png` files in the project directory.
- **Font Customization:** You can replace the digital clock font by modifying the font file path in the `try-catch` block where the font is loaded.

## Conclusion

Enjoy this Java-based Minesweeper game, perfect for both beginners and experienced players looking to challenge their problem-solving and strategic thinking skills. Whether you're killing time or looking for a nostalgic trip, this Minesweeper game is sure to provide hours of fun.
