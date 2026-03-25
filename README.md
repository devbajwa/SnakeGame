# Snake (Nokia-style)

A classic, grid-based Snake game designed to feel like the old Nokia version: discrete movement, simple rules, and fast restarts.

## How to run (browser)

### Option A: quick open
- Double-click `index.html` to play.

### Option B (recommended): local server
Some browsers behave better with local storage when served over HTTP.

- Python:
	- `python -m http.server 5173`
	- Open: http://localhost:5173/

## Controls
- Arrow keys: move
- Space: pause / resume
- R: restart
- Restart button: restart

## Rules
- Eat the food to grow and increase score.
- If you collide with yourself: game over.
- Wall behavior depends on the **Edges** setting.
- If **Hurdles** are enabled, hitting an obstacle is always game over.

## Settings
The game includes simple settings (shown as small segmented buttons) to adjust difficulty without changing the UI layout.

### Edges
- **Walls**: hitting the edge ends the game.
- **Wrap**: going off one edge makes the snake appear on the opposite side.

### Hurdles
- **Off**: no obstacles.
- **Easy**: a few obstacles.
- **Hard**: more obstacles.

### Speed
- **Slow / Normal / Fast**: changes the base movement speed (speed still increases gradually as your score grows).

## Tips
- Press an arrow key to start moving.
- Use **Wrap + Hard** for a tougher challenge.
