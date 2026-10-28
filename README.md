# CodeViz — Interactive Algorithm, Memory & Git Visualizer

CodeViz is a browser-based educational application for learning algorithms, memory concepts, and Git workflows through interactive simulations.

## Features
- **Algorithm Visualizer:** Bubble, Selection, Insertion, Merge, Quick, and Heap Sort; Linear and Binary Search.
- **Memory Tracker:** simulated variable creation, updates, release, and stack/heap concepts.
- **Git Learning:** guided lessons from repository basics through branching and remote workflow.
- **Git Workflow Lab:** simulated file changes, staging, commits, branches, merge, and push/pull concepts.
- **Practice Challenges and DSA Quiz:** feedback, hints, scoring, and locally saved best score.
- **Code & Pseudocode Explorer:** step through algorithm logic.
- **Complexity Compare and Big-O Playground:** compare theoretical complexity and illustrative growth rates.
- **Progress & Badges:** selected activity stored in browser localStorage.
- **Light/Dark Theme.**

## Important scope note
This version is frontend-only. Git operations are simulations; the app does not execute Git commands or connect to GitHub. The memory tracker is conceptual and does not inspect real process memory. Progress is stored in the current browser's localStorage; there is no backend or shared database.

## Requirements
- Node.js (current LTS recommended)
- npm

## Run locally
1. Extract the ZIP.
2. Open the `CodeViz-main` folder in VS Code (the folder containing `package.json`).
3. Open Terminal → New Terminal and run:

   ```powershell
   npm install
   npm run dev
   ```

4. Open the local URL printed by Vite, usually `http://localhost:5173`.
5. Stop the server with `Ctrl + C` in the terminal.

## Production build
```powershell
npm run build
```

Vite outputs the production bundle to `dist/`. Run `npm run preview` to preview it locally.

## Documentation
- `docs/PROJECT_REPORT.md` — project report
- `docs/VIVA_QUESTIONS.md` — viva questions and suggested answers
- `docs/TESTING_CHECKLIST.md` — manual test checklist

## Suggested demo order
Dashboard → Algorithm Visualizer → Memory Tracker → Git Learning → Git Lab → Practice → DSA Quiz → Complexity Compare → Big-O Playground → Progress & Badges.
