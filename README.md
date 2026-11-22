# The Ultimate Game Arcade

A mobile-friendly retro arcade in a single HTML file. Three games, no installs, no dependencies.

**Play online:** https://YOUR-USERNAME.github.io/ultimate-game-arcade/
**Original site:** https://sites.google.com/view/the-ultimate-pythonsnake/full-page-embed

<!-- Add a screenshot: put it in an assets/ folder and uncomment the next line -->
<!-- ![Screenshot](assets/screenshot.png) -->

## Games

### Snake Arcade
- **Modes:** Normal (walls kill you), Wrap (edges teleport you), Trap (2x score with traps on the board)
- **Snake styles:** Green, Cyan, Pink, Cute Eyes
- **Base speed** and **background theme** options
- **Power-ups:** gem, ghost, doubler, mega fruit
- **Local leaderboard** and **8 achievements** (First Bite, Snake Master, Centipede, Speed Demon, Power Hungry, Trap Survivor, Century Club, Warp Runner), saved in your browser

### Mine-Tac-Toe
A tic-tac-toe twist with hidden mines.

### Classic Tic-Tac-Toe
The familiar 3x3 game.

## Controls
| Input | Action |
|-------|--------|
| Arrow keys or W / A / S / D | Steer the snake |
| Swipe (touch screens) | Steer the snake |
| Tap / click | Play tic-tac-toe moves, press buttons |
| PAUSE button | Pause Snake |
| Home button | Back to the hub |

## Run locally
1. Download or clone this repository.
2. Open `index.html` in any modern browser.

```bash
git clone https://github.com/YOUR-USERNAME/ultimate-game-arcade.git
cd ultimate-game-arcade
# then double-click index.html
```

Fonts are loaded from Google Fonts, so a connection is needed for the pixel font. The game still works offline with fallback fonts.

## Tech
HTML5 Canvas, CSS and vanilla JavaScript. Scores and achievements use `localStorage`.

## Deploy your own copy
Fork this repo, then go to **Settings > Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.

## License
MIT. See [LICENSE](LICENSE).
