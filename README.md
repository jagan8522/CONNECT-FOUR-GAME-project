# Connect Four Game

A web-based implementation of the classic Connect Four game built with HTML, CSS, and JavaScript. This repository contains the source code, demo pages, and assets for a playable Connect Four game that you can include in your portfolio.

---

## Demo

* Live demo: https://jagan8522.github.io/CONNECT-FOUR-GAME-project/

---

## About

Connect Four is a two-player connection board game in which the players take turns dropping colored discs into a seven-column, six-row vertically suspended grid. The objective is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs.

This project recreates that experience in the browser with a clean UI, animations, and simple AI (optional) for single-player mode.

---

## Features

* Two-player (local) mode
* Optional single-player mode vs simple AI (if implemented)
* Win detection (horizontal, vertical, diagonal)
* Reset / New game button
* Highlight winning four
* Responsive layout for desktop and mobile
* Clean, modular JavaScript code

## Tech Stack

* HTML5
* CSS3 (Flexbox / Grid)
* JavaScript (ES6)
* (Optional) LocalStorage for saving game stats

---

## Project Structure

```
CONNECT-FOUR-GAME-project/
├── assets/
│   ├── images/
│   │   ├── logo.png
│   │   └── gameplay-1.png
│   └── styles/
│       └── theme.css
├── css/
│   └── styles.css
├── js/
│   ├── main.js
│   ├── game.js
│   └── ai.js        # optional
├── index.html
├── README.md
└── LICENSE
```

**File hints**

* `index.html` – main HTML file for the game UI.
* `css/styles.css` – core styling.
* `js/game.js` – game logic (board model, move validation, win detection).
* `js/main.js` – UI bindings, event listeners.
* `js/ai.js` – optional AI opponent (simple minimax or heuristic-based).

---

## Installation & Run

1. Clone the repository:

   ```bash
   git clone https://github.com/jagan8522/CONNECT-FOUR-GAME-project.git
   cd CONNECT-FOUR-GAME-project
   ```
2. Open `index.html` in your browser (double-click or run a local server):

   ```bash
   # using Python 3 built-in server
   python -m http.server 8000
   # then open http://localhost:8000 in your browser
   ```

---

## How to Play

1. Player 1 (red) goes first. Click or tap a column to drop a disc into that column.
2. Players alternate turns until one player connects four discs in a row horizontally, vertically, or diagonally, or the board fills (draw).
3. When a player wins, the four winning discs are highlighted and a message displays the winner.
4. Click **New Game** to reset the board.

---

## Controls

* Click/tap a column to drop a disc.
* `New Game` button to reset.
* (Optional) Toggle to switch between 2-player and single-player vs AI.

---

## Customisation

* Change the board size by editing constants in `js/game.js` (rows/cols) — note: win logic assumes min size 4.
* Update colors in `css/styles.css`.
* Replace images or add animations in `assets/`.

---

## Deployment

* Publish to GitHub Pages:

  1. Push the repo to GitHub.
  2. In repository settings > Pages, choose the `main` branch and `/ (root)` folder.
  3. Save and visit the provided URL.

---

## Contributing

Contributions are welcome!

1. Fork the repo.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes and push: `git push origin feature-name`.
4. Open a Pull Request.

Please keep code modular and add comments for complex logic.

---

## License

This repository is open-source. Add a license file (e.g., MIT) or change as needed.

---

## Contact

**Jagan Kurra**

* Email: [jagankurra89@gmail.com](mailto:jagankurra89@gmail.com)
* GitHub: [https://github.com/jagan8522](https://github.com/jagan8522)

---

## Notes for your portfolio

* Add a short project summary (1–2 lines) and a link to the live demo.
* Include 1–2 GIFs showing gameplay and win highlight.
* Tag the project with skills: `JavaScript`, `HTML`, `CSS`, `Game Development`.
* Mention any added features like AI or LocalStorage high score.

 
