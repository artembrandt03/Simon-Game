# Simon Game — Mini Web Project

A small **HTML/CSS/JavaScript** recreation of the classic **Simon memory game**. The game generates a growing color sequence; you repeat it by clicking the colored buttons. One mistake ends the run and shows your score!
<img width="2544" height="1304" alt="image" src="https://github.com/user-attachments/assets/48e6165c-bd6b-4827-9e45-9a1a2a21e1ae" />


## Live Demo (GitHub Pages)
Play it here: https://artembrandt03.github.io/Simon-Game/

## Features
- Random sequence generation (4 colors)
- Sequence playback with timed flashes + matching sound effects
- Input locking during playback (prevents accidental clicks)
- Round counter + score on game over
- Start game with **Space** or by clicking **HERE**

## Concepts Demonstrated
- DOM manipulation with **jQuery**
- Event handling (keyboard + button clicks)
- Arrays for state (`gamePattern`, `userClickedPattern`)
- Timing control with `setTimeout` for sequence playback
- Audio playback using the `Audio()` API
- Basic game state management (start, round progression, game-over)

## Tech Stack
- **HTML** (`index.html`)
- **CSS** (`styles.css`)
- **JavaScript** (`game.js`)
- **jQuery** (CDN)

## Project Structure
```
.
├── index.html
├── styles.css
├── game.js
└── sounds/
```

## How to Run Locally
Clone the project:
```Bash
git clone https://github.com/artembrandt03/Simon-Game.git
```
### Option 1: Just open the file
1. Open `index.html` in your browser.

### Option 2: Use a local server (recommended)
Some browsers apply stricter rules for local files. Running a small server avoids issues.

**VS Code (Live Server extension):**
- Right-click `index.html` → **Open with Live Server**

## Credits
Developed by **Artem Brandt**.
