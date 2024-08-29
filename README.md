# Towers of Hanoi

## Overview

**Towers of Hanoi** is an interactive web-based puzzle game that challenges players to move disks between three towers following specific rules. The game is designed to develop the player's problem-solving and logical thinking skills. This version of the game features two levels, where the number of disks increases as the player progresses.

## Features

- **Level 1:** Players start with 3 disks. The objective is to move all the disks from the first tower to any other tower, following the rules of the game.
- **Level 2:** Players are challenged with 4 disks, increasing the complexity of the puzzle.
- **Drag and Drop:** The game uses drag-and-drop functionality to move disks between towers.
- **Progression and Feedback:** After completing Level 1, players receive feedback and can proceed to Level 2. Upon completing Level 2, the player receives a congratulatory message and advances to the next skill challenge.
- **Steps Counter:** The game tracks the number of moves (steps) taken by the player.

## How to Play

1. **Start the Game:** When the page loads, Level 1 with 3 disks is automatically started.
2. **Move Disks:** Click and drag a disk from one tower to another. The disks must be moved according to the rules:
   - Only one disk can be moved at a time.
   - A disk can only be placed on top of a larger disk or an empty tower.
3. **Complete the Level:** 
   - For Level 1, move all 3 disks to one of the other towers to complete the level.
   - For Level 2, move all 4 disks to one of the other towers to complete the game.
4. **Progression:**
   - After completing Level 1, you'll see a message and the option to proceed to Level 2 by clicking the "Next Level" button.
   - After completing Level 2, you'll receive a congratulatory message, and after a short delay, you'll be directed to the next challenge.

## File Structure

- **index.html:** The main HTML file containing the structure and logic for the Towers of Hanoi game.
- **towers.css:** The CSS file for styling the game elements.
- **jquery.min.js:** A link to the jQuery library used for handling drag-and-drop functionality.

## Usage

To run the Towers of Hanoi game, simply open the `index.html` file in a web browser. Make sure the `towers.css` file is in the same directory as `index.html`.

## Customization

- **Number of Disks:** You can customize the number of disks for each level by modifying the `loadLevel` function in the script.
- **Disk Appearance:** Change the appearance of the disks by modifying the CSS in `towers.css`.

## Future Enhancements

- Add more levels with an increasing number of disks.
- Implement a scoring system based on the minimum number of moves required.
- Provide a timer to track how long it takes to complete each level.
- Create a leaderboard to compare scores and times with other players.
