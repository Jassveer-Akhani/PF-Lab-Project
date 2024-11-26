![WhatsApp Image 2024-11-21 at 20 07 06_91a9033e](https://github.com/user-attachments/assets/7bc10d28-e9bd-40e8-bde9-065bba05c4bc)
## Dungeon & Dragons.

## Overview

**Dungeon & Dragons** is an engaging text-based role-playing game (RPG) where you embark on an adventure as a heroic elf, battling against dark forces, solving riddles, and exploring dangerous quests. With a simple dice roll mechanic, every action you take is determined by the roll of the dice, adding an element of chance to every decision.


## Features

- **Hero Creation**: Choose your hero's name and start your journey as the last hope of the Elven race.
- **Multiple Quests**: Battle dark minions, solve riddles, and face the ultimate boss, the Underworld King.
- **Dice Rolling Mechanics**: Every action is decided by a dice roll, creating an element of randomness and excitement.
- **Save/Load Functionality**: Save your progress at any point and pick up where you left off later.
- **Boss Fights**: Engage in epic battles with powerful bosses, including the fearsome Underworld King.
- **Health Management**: Your health is constantly at risk—defeat enemies and complete quests to stay alive.
- **Mysterious Encounters**: Find chests, gain health potions, or face deadly mimics.

## How to Play

1. **Start a New Game**:
   - Launch the game and choose your hero's name.
   - Immerse yourself in the rich storyline as you begin your adventure in Eldermoon.

2. **Roll the Dice**:
   - When engaging in battle or facing challenges, you will roll dice to determine the outcome.
   - Higher rolls mean you succeed, but low rolls can cost you health.

3. **Complete Quests**:
   - Progress through quests by defeating enemies, solving riddles, and making the right choices.
   - Your decisions will determine your fate and the survival of the Elven race.

4. **Save and Load**:
   - You can save your game at any point outside of combat. Simply open the **Game Menu** and select **Save Game**.
   - Your save will store all your hero’s stats, inventory, quests, and map progress, ensuring you don’t lose any valuable progress during your adventures.

## Installation

To play the game, you will need a C compiler. Follow these steps:

1. **Clone the Repository**:
   - Clone this repository to your local machine using the command:
     ```bash
     git clone https://github.com/your-username/dungeon-and-dragons.git
     ```

2. **Compile the Code**:
   - Navigate to the game directory and compile the game using a C compiler like GCC:
     ```bash
     gcc -o dungeon_and_dragons main.c
     ```

3. **Run the Game**:
   - After compiling, run the game with:
     ```bash
     ./dungeon_and_dragons
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
