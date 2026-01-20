# Hexa Stack Sort 🧩

> A satisfying, infinite puzzle game built with Vanilla JavaScript and HTML5 Canvas.

**Hexa Stack Sort** is a browser-based puzzle game where players drag and drop stacks of hexagonal tiles to merge colors, clear the board, and progress through procedurally generated levels. It features a "2.5D" isometric rendering engine, synthesized audio, and complex recursive merge logic—all contained within lightweight HTML files.

## ✨ Features

### 🎮 Gameplay
-   **Infinite Levels:** Difficulty scales procedurally, increasing board density, color variety, and stack complexity as you progress.
-   **Satisfying Physics:** Tiles snap, merge, and pop with custom animations.
-   **Recursive Merging:** Placing a stack triggers a chain reaction—tiles fly across the board to match neighbors, revealing new colors that trigger *further* merges.
-   **Progression System:** Clear tiles to fill the meter and advance. Early levels are designed for fast, satisfying progression.

### 🛠 Technical
-   **Zero Dependencies:** Built entirely with native HTML, CSS, and JavaScript. No external libraries or frameworks.
-   **HTML5 Canvas Rendering:**
    -   Custom hexagonal grid mathematics (Axial coordinate system).
    -   "Painter's Algorithm" implementation for correct Z-index sorting (rendering 3D stacks in 2D space).
    -   60 FPS animation loop with lerp-based transitions.
-   **Synthesized Audio:** Sound effects (pops, swooshes, chords) are generated in real-time using the **Web Audio API**. No external \`.mp3\` or \`.wav\` files required.
-   **Responsive Design:** Fully playable on desktop (mouse) and mobile (touch/drag).

## 🚀 How to Play

1.  **Drag** a stack of tiles from your inventory (bottom of screen).
2.  **Drop** it onto an open hexagon on the grid.
3.  **Watch** as matching colored tiles from neighboring stacks fly over to merge with your placed stack.
4.  **Clear** stacks by building them up to **10 tiles high**.
5.  **Fill** the progress meter at the top to unlock the next level!

## 📦 Installation & Usage

Since this project uses no build tools or bundlers, it is incredibly easy to run.

1.  Clone the repository:
    \`\`\`bash
    git clone https://github.com/yourusername/hexa-stack-sort.git
    \`\`\`
2.  Navigate to the project folder.
3.  Open \`index.html\` in your web browser to view the Landing Page.
4.  Click **Play Now** to launch the game (\`app.html\`).

## 📂 Project Structure

* \`index.html\` - The marketing/landing page. Features CSS animations and a "Play" CTA.
* \`app.html\` - The core game logic. Contains the Canvas engine, game state management, and Web Audio implementation.
* \`README.md\` - Documentation.

## 🎨 Color Palette

The game uses a specific "Satisfying Vibe" palette:

| Color | Hex | Usage |
| :--- | :--- | :--- |
| **Background** | \`#452b3f\` | Dark Purple |
| **Grid Base** | \`#2b1b28\` | Deep Shadow |
| **Tiles** | \`#fabf61\`, \`#e08d51\`, \`#609c4f\` | Various gameplay elements |
| **UI Text** | \`#f5eeb0\` | Cream |

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the merge algorithm, add new particle effects, or optimize the canvas rendering:

1.  Fork the Project
2.  Create your Feature Branch (\`git checkout -b feature/AmazingFeature\`)
3.  Commit your Changes (\`git commit -m 'Add some AmazingFeature'\`)
4.  Push to the Branch (\`git push origin feature/AmazingFeature\`)
5.  Open a Pull Request

## 📄 License

Distributed under the MIT License. See \`LICENSE\` for more information.


