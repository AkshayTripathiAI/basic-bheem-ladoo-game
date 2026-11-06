# Basic Bheem Ladoo Game

A minimal HTML5 canvas game: hold the mouse button to move Bheem across the screen, dodge the bouncing enemies and reach the ladoo.

This is a non-commercial, fan-made practice game. Characters and names belong to their respective owners; this is a non-commercial fan project. Images are used for learning purposes.

**Live demo:** https://akshaytripathiai.github.io/basic-bheem-ladoo-game/

## How to play

- Press and hold the mouse button on the canvas to move Bheem to the right; release to stop.
- Three enemies bounce up and down. Touching one costs 50 points; if the score drops below zero the game ends.
- Reach the ladoo on the right side to win.

## Tech stack

- HTML5 Canvas
- Vanilla JavaScript (no libraries, no build step)

## Run locally

```bash
git clone https://github.com/AkshayTripathiAI/basic-bheem-ladoo-game.git
cd basic-bheem-ladoo-game
npx serve .
```

Or simply open `index.html` in a browser.

## Project structure

```
index.html   # page and canvas
game.js      # game loop, collision detection, input
images/      # sprites and background
```

## Related projects

- [Bheem-Ladoo-2](https://github.com/AkshayTripathiAI/Bheem-Ladoo-2) - expanded version with keyboard controls, levels, music and a saved high score
- [Chota-Bheem-Adventure-game](https://github.com/AkshayTripathiAI/Chota-Bheem-Adventure-game) - a jump-and-dodge runner
- [Adventure-Game](https://github.com/AkshayTripathiAI/Adventure-Game) - bundles this game (as Game 1) with the others in one page
