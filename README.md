# GPQ Stage 3 Solver

A web-based solver for the **Great Pyramid Quest (GPQ) Stage 3** puzzle from MapleStory. This interactive tool helps players find the correct item combination by analyzing feedback from NPCs.

## Overview

GPQ Stage 3 presents a challenging puzzle where you must determine the correct order of 4 items (Medal, Scroll, Food, Drink) based on feedback from NPCs. This solver uses constraint elimination to narrow down possibilities with each guess.

## How It Works

1. **Initial Setup**: The solver suggests an item combination based on all 256 possible permutations
2. **Input Feedback**: After submitting your guess to an NPC, input the feedback:
   - **Correct**: Items in the right position
   - **Incorrect**: Items not used in the solution
   - **Unknown**: Items in the solution but wrong position
3. **Filter & Solve**: The solver eliminates impossible combinations and suggests the next guess
4. **Repeat**: Continue until you find the solution

## Features

- 🎯 **Smart Suggestions**: Recommends guesses to narrow down possibilities efficiently
- 📊 **Real-time Filtering**: Instantly eliminates invalid combinations
- 🔄 **Undo Support**: Go back to previous turns if needed
- 🌙 **Dark Theme**: Easy on the eyes during long gaming sessions
- 📱 **Simple UI**: Quick-click buttons for fast input

## Installation

Simply open `test.html` in any modern web browser:
- Double-click the file in File Explorer, or
- Right-click → "Open with" → Select your browser

No installation or dependencies required!

## Usage

1. Open the solver
2. See the suggested combination for your first guess
3. Try the suggested combination in-game
4. Input the NPC's feedback using the buttons
5. Click **FILTER** to eliminate possibilities
6. The solver will suggest your next guess
7. Repeat until you find the correct combination

## Project Files

- `test.html` - Main solver application
- `medal.png` - Medal item icon
- `scroll.png` - Scroll item icon
- `food.png` - Food item icon
- `drink.gif` - Drink item icon

## How Feedback Works

| Feedback | Meaning |
|----------|---------|
| **Correct** | Item is in the correct position |
| **Unknown** | Item is in the solution but in the wrong position |
| **Incorrect** | Item is not used in the solution |

Example: If your guess is `[Medal, Scroll, Food, Drink]` and feedback is:
- Correct: 1, Incorrect: 1, Unknown: 2
- This means: 1 item is correct, 1 item isn't used, 2 items are correct but in wrong positions

## Tips for Efficiency

- Start with the suggested combination
- Be precise with feedback to eliminate more possibilities each turn
- Use BACK if you need to correct previous feedback
- The solver will tell you how many possibilities remain

## Browser Compatibility

Works on:
- Chrome/Chromium (Recommended)
- Firefox
- Safari
- Edge

## License

This is a fan-made tool for MapleStory players.

## Contributing

Found a bug? Have suggestions? Feel free to improve this tool!
