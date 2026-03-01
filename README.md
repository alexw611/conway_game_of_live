<p align="center">
  <h1 align="center">🎮 Conway's Game of Life</h1>
  <p align="center">
    <strong>Interactive browser simulation of John Conway's cellular automaton with real-time controls</strong>
  </p>
  <p align="center">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
    <img src="https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white" alt="GitHub Pages">
  </p>
  <p align="center">
    <a href="https://alexw611.github.io/conway_game_of_live/"><strong>▶️ Live Demo</strong></a>
  </p>
</p>

---

## About

An interactive implementation of John Conway's legendary "Game of Life" — a cellular automaton that creates complex patterns and behaviors from just three simple rules. Over 50 years ago, mathematician John Conway designed a system of black and yellow squares that produces fascinating worlds with objects that move, interact, and evolve — none of which is explicitly programmed.

## The Three Rules

| Rule | Condition | Result |
|---|---|---|
| **Survival** | A living cell has 2 or 3 living neighbors | Cell survives |
| **Birth** | A dead cell has exactly 3 living neighbors | Cell becomes alive |
| **Death** | All other cases | Cell dies or stays dead |

## Features

- **Interactive Grid** — click to toggle cells alive or dead
- **Play / Pause** — start and stop the simulation at any time
- **Speed Control** — adjust simulation speed dynamically
- **Generation Counter** — tracks how many generations have passed
- **Population Counter** — live count of all active cells
- **Restart & Clear** — reset to random state or empty grid
- **Zero Dependencies** — pure HTML, CSS, and JavaScript in a single file

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript (Canvas API) |
| Hosting | [GitHub Pages](https://pages.github.com/) |

## Getting Started

### Play Online

Open the **[Live Demo](https://alexw611.github.io/conway_game_of_live/)** — no installation required.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/alexw611/conway_game_of_live.git
cd conway_game_of_live

# Open in browser
open index.html
```

## Controls

| Button | Action |
|---|---|
| ⏸️ **Pause** | Pause / resume the simulation |
| 🔄 **Restart** | Reset the grid with a new random state |
| 🗑️ **Clear** | Clear all cells |
| ⚡ **Speed** | Increase simulation speed |

## Project Structure

```
conway_game_of_live/
├── index.html          # Everything — markup, styles, and logic
└── README.md
```

## License

This project is licensed under the [MIT License](LICENSE).

---
