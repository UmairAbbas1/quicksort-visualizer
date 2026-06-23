# 🔢 Quick Sort Visualizer

An interactive, visually polished **Quick Sort algorithm visualizer** built with
**vanilla HTML, CSS, and JavaScript** — no frameworks, no build step, no dependencies
(except an optional Google Fonts link).

Watch the Quick Sort algorithm (Lomuto partition scheme) sort an array step by step:
pivots, comparisons, swaps, and recursion — all animated in real time.

![Status](https://img.shields.io/badge/status-stable-brightgreen)
![Made with](https://img.shields.io/badge/made%20with-HTML%2FCSS%2FJS-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## ✨ Features

- 🎯 **Real Quick Sort** — Lomuto partition scheme, fully instrumented. Every
  comparison/swap/access shown reflects the actual algorithm, not a fake animation.
- 🎨 **Clean white theme** with smooth `cubic-bezier` transitions for every bar
  movement, height, and color change.
- 🌈 **Color-coded states:**
  - Gray = Unsorted
  - Red = Pivot
  - Yellow = Comparing
  - Orange (with pulse) = Swapping
  - Green = Sorted
- ⏯️ **True Pause / Resume / Step Forward** using `async/await` + pausable promise
  gates (not `setInterval` hacks).
- 📊 **Live stats:** comparisons, swaps, array accesses, elapsed time, recursion depth.
- 🏷️ **Live status banner** (e.g. `Partitioning [2..7], pivot = 14`) plus animated
  `low` / `high` / `i` pointers and a subarray range marker.
- 📜 **Pseudocode panel** that highlights the currently executing line.
- 🎉 **Celebration wave animation** when sorting completes.
- ⌨️ **Keyboard shortcuts** for clean screen recording.

---

## 🚀 Getting Started

No installation, no dependencies, no build tools required.

### Run it
1. Download or clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/quicksort-visualizer.git
   cd quicksort-visualizer
