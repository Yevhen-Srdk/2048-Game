# 2048 Game

A responsive, browser-based implementation of the classic **2048** puzzle game built with modern JavaScript (ES6+), HTML5, and SCSS.

- **[Live Demo](https://yevhen-srdk.github.io/2048-Game/)**

---

## 🎮 How to Play

1. Click **Start** to begin a new game. Two initial tiles (value 2 or 4) will spawn on the 4x4 grid.
2. Use the **Arrow keys** (`Up`, `Down`, `Left`, `Right`) on your keyboard to slide tiles across the board:
   - When two tiles with the same number collide during a move, they **merge into one** tile with their combined sum!
   - Every valid move generates a new random tile in an empty cell.
3. **Win Condition:** Create a tile with the number **2048**.
4. **Game Over:** When the board is completely full and no adjacent tiles can merge in any direction.
5. Click **Restart** at any time to reset the board and start fresh.

---

## ✨ Features

- **OOP Architecture:** Clean separation of concerns with an isolated, testable `Game` class (`Game.class.js`).
- **Interactive UI:** Smooth transitions, responsive feedback, and dynamic status messages (Start, Win, Game Over).
- **Mobile Responsive:** Fluid layout that adapts smoothly across screen sizes (desktop, tablet, and mobile down to 320px).
- **Favicon & Branding:** Custom 2048 SVG favicon and typography consistent with the classic design.
- **Code Quality:** Enforced with ESLint, Stylelint, and Linthtml following strict industry standards.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic markup, accessibility considerations, and Linthtml validation.
- **SCSS / CSS3:** Modular stylesheets, CSS variables, flexbox, and responsive media queries.
- **JavaScript (ES6+):** Object-Oriented Programming (Classes), event-driven DOM manipulation.
- **Bundler & Tooling:** Parcel, NPM, Git, GitHub Pages.

---

## 🚀 Getting Started Locally

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) (v18 or higher recommended) and [npm](https://www.npmjs.com/) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Yevhen-Srdk/2048-Game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd 2048-Game
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Available Scripts

- **Start development server:**
  ```bash
  npm start
  ```
  Runs the local dev server (usually at `http://localhost:1234`).
- **Run linters (HTML, SCSS, JS):**
  ```bash
  npm run lint
  ```
- **Build for production:**
  ```bash
  npm run build
  ```
  Generates production-ready, minified assets in the `dist` directory.
- **Deploy to GitHub Pages:**
  ```bash
  npm run deploy
  ```
