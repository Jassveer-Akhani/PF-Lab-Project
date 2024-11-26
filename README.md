<img align="left" src="logo/WhatsApp Image 2024-11-21 at 20.07.06_91a9033e.jpg" width=256>.
## raudio is simple and easy-to-use audio library based on miniaudio.

## Overview

**Eldermoon: The Last Stand** is a text-based role-playing game (RPG) set in a fantastical world where you, as the last hope of the Elven kin, battle against dark forces threatening Middle Earth. Embark on an adventure filled with quests, battles, riddles, and a quest to defeat the Underworld King.

## Features

- **Randomized Combat**: Engage in dice-based battles with enemies using the `rollDice` function.
- **Multiple Quests**: Experience a variety of quests, including battling dark minions, solving riddles, and confronting the Underworld King.
- **Game Saving**: Save and load your progress, allowing you to pick up where you left off.
- **Storyline**: Immerse yourself in a rich narrative as you guide the Elven hero through their journey to save their people.

## Installation

1. **Clone this repository**:

    ```bash
    git clone https://github.com/yourusername/eldemoon-the-last-stand.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd eldemoon-the-last-stand
    ```

3. **Compile the game**:

    Use any C compiler to compile the `game.c` file. For example, with GCC:

    ```bash
    gcc game.c -o eldemoon
    ```

4. **Run the game**:

    After compiling, you can run the game with the following command:

    ```bash
    ./eldemoon
    ```

## Gameplay

Upon starting the game, you will be prompted to enter your hero's name and then face various quests. Here is a breakdown of the gameplay:

### Quests

- **Quest 1: Battle with the Dark Minion**
  - A dice-based battle where you roll against an enemy.
  
- **Quest 2: Encounter the Mysterious Chest**
  - You come across a chest with multiple outcomes: finding a health potion, triggering a trap, or battling a Mimic.
  
- **Quest 3: Solve a Riddle**
  - You must solve a riddle posed by a wise old Elf to continue your journey.
  
- **Final Quest: Battle the Underworld King**
  - The ultimate battle where you face the Underworld King in a dice roll duel.

### Game Saving and Loading

You can save and load your progress at any point in the game. Your health, current quest, and hero name will be saved and can be resumed in future sessions.

- **Saving**: Save your game to a file with the `saveGame` function.
- **Loading**: Load your previous save to continue where you left off.

## Commands

- **Press Enter**: Prepare for a dice roll during battles.
- **Enter your choice**: Answer questions or make decisions that will affect the outcome of the game.

## Example Output

```text
You, Legolas, were born in Eldermoon, the last refuge of the Elven kin in Middle Earth.
Nestled amidst towering mountains, gushing rivers, and the stately trees of the Elven Forest, Eldermoon has been your home for your entire life - a tranquil sanctuary far removed from the opulence of grand cities and the intrigues of royal courts.

The cries of your kin echo in your heart, urging you to rise against the encroaching darkness. Will you take up the mantle of leadership and lead the Elves into one final battle for the survival of Elvenkind and the fate of all Middle Earth?

Do you want to continue to the battlefield? (y/n): y

Your Inventory:
- Sword of Legend
Your Health: 100

--- Quest 1: The Fields of Eldermoon are under attack by a Dark Minion. ---

Press Enter to prepare for the dice roll...
Press Enter again to roll the dice...
You rolled: 4, Dark Minion rolled: 2
You defeated the Dark Minion!
