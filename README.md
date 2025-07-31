# Dice-Game
React based Dice Game
TechStack
1. React.js (Component-based architecture)
2. JavaScript utility functions to manage game logic

   
#Main Components
StartGame: Likely renders the entry screen (Start Button, Title)

GamePlay: Manages the main logic after starting the game (dice rolling, scores)

Button (custom component): Used across the app with props like variant (e.g., "outline")

RollDice: Functionality to randomly generate and show dice values

#Flow Structure
User sees a Start Game screen.

Clicks Start, which switches to the GamePlay component.

A dice roll function is triggered with a button (possibly <Button onClick={rollDice}>Roll</Button>).

Dice values are updated on the screen.

Game state updates, maybe includes a score or win/lose logic.
