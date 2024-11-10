# Rock Paper Scissors Game

This is a simple Rock Paper Scissors game created with HTML and JavaScript, played between a human player and the computer. The game runs in the browser console and consists of five rounds to determine the winner based on the player's choices.

## Features

- **Randomized Computer Choice**: The computer randomly selects rock, paper, or scissors.
- **User Input Prompt**: The player is prompted to input their choice each round.
- **Round-by-Round Score Tracking**: The game tracks and displays the score for both the player and the computer.
- **Winner Announcement**: After five rounds, the game announces the winner based on the scores.

## How to Play

1. Open the project in a web browser.
2. Open the browser's developer console (usually F12 or right-click -> Inspect -> Console).
3. The game will automatically start, and a prompt will ask you to enter your choice ("rock," "paper," or "scissors") for each round.
4. Enter your choice and check the console for the results after each round.
5. After five rounds, the console will display the final scores and announce the winner.

## Code Overview

- **`getComputerChoice` Function**: Randomly selects "rock," "paper," or "scissors" for the computer's choice.
- **`getHumanChoice` Function**: Prompts the user to input their choice and ensures it's a valid option.
- **`playRound` Function**: Compares the player's choice to the computer's choice, updating the score accordingly.
- **`playGame` Function**: Runs a loop for five rounds, tracking the scores and announcing the winner at the end.

## Example

```plaintext
Human chose: rock
Computer chose: scissors
Current Score -> Human: 1, Computer: 0

Human chose: paper
Computer chose: rock
Current Score -> Human: 2, Computer: 0

Final Result: The Winner is Human
