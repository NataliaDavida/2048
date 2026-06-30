# 2048 Game — Sliding Tile

A modern version of the popular **2048** game. The goal of the game is to slide numbered tiles on a grid to combine them to create a tile with the number 2048.

[DEMO LINK](https://NataliaDavida.github.io/2048/)

---

## Features

* **Classic Gameplay** — Smooth tile sliding and combining mechanics.
* **Keyboard Controls** — Play comfortably using the arrow keys (`ArrowUp`, `ArrowDown`, `ArrowLeft`, `ArrowRight`).
* **Object-Oriented Architecture** — Game logic is cleanly structured using JavaScript classes (e.g., `Game` class).

---

## Technologies Used

### Core
* **HTML5** — Semantically structured game canvas and interface elements.
* **SCSS** — Advanced modular styling with precise grid layout for the game board.
* **JavaScript (ES6+)** — Object-Oriented Programming (OOP) for game state, tile generation, and movement logic.

### Development Tools
* **Parcel** — Modern frontend bundler and asset compiler.
* **ESLint** — Code quality checkers ensuring high-standard clean code.
* **Git & GitHub** — Version control and deployment workflow.

---

## Project Structure

The logical architecture of the game scripts and styles inside the `src/` directory:
* `src/index.html` — Main entry document with the game grid layout.
* `src/scripts/main.js` — Main script managing event listeners for keyboard inputs and buttons.
* `src/modules/Game.class.js` — Core game class housing the initialization, grid generation, and movement mechanics.
* `src/styles/main.scss` — Global styles compiling all individual layout modules.

---

## Installation & Setup

1. **Clone the repository:**
   
   ```bash
   git clone https://github.com/NataliaDavida/landin-page_Museum.git

2. **Navigate to the project directory:**
     ```bash
    cd landing-page_museum

3. **Install project dependencies:**
   
    ```bash
    npm install

4. **Start the local development server:**
   
    ```bash
    npm start
