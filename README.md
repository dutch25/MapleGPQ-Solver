# Guild Quest Solver - Free GPQ Stage 3 Solver for MapleStory

A web-based solver for the **Guild Quest (GQ) Stage 3** puzzle from MapleStory. This interactive tool helps players find the correct item combination by analyzing feedback from NPCs. No installation required - works directly in your browser!

## Overview

GPQ Stage 3 presents a challenging puzzle where you must determine the correct order of 4 items (Medal, Scroll, Food, Drink) based on feedback from NPCs. This solver uses constraint elimination to narrow down possibilities with each guess.

## How It Works

1. **Initial Setup**: The solver suggests an item combination based on all 256 possible permutations
2. **Filter & Solve**: Click FILTER to eliminate impossible combinations
3. **Next Guess**: The solver suggests the next best guess
4. **Repeat**: Continue until you find the solution

## Features

- 🎯 **Smart Suggestions**: Recommends guesses to narrow down possibilities efficiently
- 📊 **Real-time Filtering**: Instantly eliminates invalid combinations
- 🔄 **Undo Support**: Go back to previous turns with BACK button
- 🎨 **Background Selector**: Choose between 2 beautiful fantasy backgrounds
- 💾 **Persistent Settings**: Your background choice is remembered across reloads
- 🌙 **Dark Theme**: Easy on the eyes during long gaming sessions
- 📱 **Show Possibilities**: Displays all remaining possible solutions (up to 50)
- ⏱️ **History Tracking**: See all your previous guesses and feedback

## Installation

Simply open `index.html` in any modern web browser:
- Double-click the file in File Explorer, or
- Right-click → "Open with" → Select your browser

**No installation or dependencies required!**

## Usage

1. Open the solver in your browser
2. See the suggested combination for your first guess
3. Try the suggested combination in-game
4. Input the NPC's feedback using the buttons:
   - Click **Correct**, **Incorrect**, or **Unknown** 
5. Click **FILTER** to eliminate possibilities
6. The solver suggests your next guess
7. Repeat until you find the correct combination
8. Use **BACK** to undo if you made a mistake
9. Click **Full Reset** to start over
10. Switch backgrounds using the dropdown selector

## Project Files

- `index.html` - Main solver application
- `medal.png` - Medal item icon
- `scroll.png` - Scroll item icon
- `food.png` - Food item icon
- `drink.gif` - Drink item icon
- `background.png` - Fantasy background image 1
- `background2.png` - Fantasy background image 2
- `README.md` - This file

## How Feedback Works

| Feedback | Meaning |
|----------|---------|
| **Correct** | Item is in the correct position |
| **Unknown** | Item is in the solution but in the wrong position |
| **Incorrect** | Item is not used in the solution |

**Example:** If your guess is `[Medal, Scroll, Food, Drink]` and NPC feedback shows:
- Correct: 1, Incorrect: 1, Unknown: 2
- This means: 1 item is correct in position, 1 item isn't used, 2 items are correct but in wrong positions

## Features in Detail

### Background Selector
- Dropdown at the top to switch between 2 beautiful backgrounds
- Your choice is saved automatically
- Persistent across page reloads

### Possibilities Display
- Shows all remaining possible solutions when there are 50 or fewer
- Hides when too many possibilities remain
- Helps you verify the solver's logic

### History Tracking
- See all previous guesses and their feedback
- Displayed in reverse chronological order (newest first)
- Helps you understand the solving process

### Undo/Reset
- **BACK button**: Undo the last guess
- **Full Reset button**: Start completely fresh with all 256 combinations

## Tips for Efficiency

- Start with the suggested combination for Turn 1 and 2 (they're forced)
- Be precise with feedback to eliminate more possibilities each turn
- Use BACK if you need to correct previous feedback
- Watch the "Remaining Possibilities" count to track progress
- Switch backgrounds to keep things fresh during long solving sessions!

## Browser Compatibility

Works on:
- Chrome/Chromium (Recommended)
- Firefox
- Safari
- Edge

## License

This is a fan-made tool for MapleStory players.

## Credits

Created by Dutch25

## Contributing

Found a bug? Have suggestions? Feel free to improve this tool!
