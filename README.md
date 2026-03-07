# AlgoSight — Interactive Algorithm Education

> Transform abstract algorithms into visual understanding.

**AlgoSight** is a browser-based DSA visualizer that brings **34 algorithms** to life through real-time, step-by-step animations. Built for students, interview preppers, and anyone who learns better by *seeing* how code works under the hood.

---

## ✨ Features

**34 Algorithms across 4 categories**

- **Sorting** — Bubble, Selection, Insertion, Merge, Quick, Heap, Radix, Shell, Counting, Tim, Cocktail Shaker, Comb, Gnome, Bucket, Pigeonhole
- **Searching** — Linear, Binary, Jump, Interpolation, Exponential, Ternary
- **Pathfinding** — BFS, DFS, Dijkstra's, A\*
- **Techniques** — Two Pointers, Sliding Window, Kadane's, Prefix Sum, Frequency Counter, Dutch National Flag, Boyer-Moore Majority Vote, Merge Intervals, Reservoir Sampling

**Visualizer**
- Step-by-step execution with forward/backward controls
- Adjustable speed (5 levels) and array size
- Timeline scrubber to jump to any point in the animation
- Live stats: comparisons, swaps, and total steps

**Learn Mode**
- Narration bar with plain-English explanations at every step
- Highlighted pseudocode, Python, C++, Java, and JavaScript snippets synced to execution
- Recursion tree panel for Merge Sort and Quick Sort
- Complexity reference (best/average/worst time + space) in the sidebar

**Race Mode**
- Run two algorithms head-to-head on the same data
- Works across Sorting, Searching, and Pathfinding categories
- Live progress bars, step counters, and a winner declaration

**Pathfinding Grid**
- Draw walls and weighted cells with click-and-drag
- Generate random mazes
- Drag start/end nodes anywhere on the grid
- Animated visited cells and shortest-path highlight

**Quality of Life**
- Dark / Light theme toggle
- Custom array input
- Best / Average / Worst / Equal preset arrays
- GIF export of any visualization
- Shareable URL per algorithm
- Keyboard shortcuts (`Space`, `←→`, `R`, `S`, `F`, `1–5`)
- Guided interactive tutorial for new users
- Fully responsive layout

---

## 🖥️ Demo

**Live site:** *(https://algo-sight.netlify.app/#app)*

---

## 🗂️ Project Structure

```
algosight/
├── index.html      # App shell and layout
├── style.css       # Design tokens, components, responsive styles
├── script.js       # All algorithm logic, rendering, and UI
└── favicon.svg     # Site icon
```

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Run / Pause |
| `←` | Step backward |
| `→` | Step forward |
| `R` | Reset |
| `S` | Shuffle array |
| `F` | Fullscreen |
| `L` | Toggle Learn / Narration mode |
| `1–5` | Set speed (Very Slow → Max) |
| `W` | Pathfinding: Wall tool |
| `E` | Pathfinding: Erase tool |

---

## 🛠️ Tech Stack

- Vanilla HTML, CSS, JavaScript — zero dependencies, zero frameworks
- [Inter](https://fonts.google.com/specimen/Inter) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) + [Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif) via Google Fonts
- CSS custom properties for full dark/light theming
- Canvas API for the welcome screen particle graph and GIF export

---

## 👤 Author

Made by [Jeet Makhija](https://www.linkedin.com/in/jeet-makhija)
Vibe Coded 🎧

If you found this useful, consider giving the repo a ⭐ — it helps a lot!
