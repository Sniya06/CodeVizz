# CodeViz — Viva Preparation

## Short explanation
CodeViz is a browser-based interactive learning platform for algorithms, memory concepts, and Git workflows. It is built with React, TypeScript, HTML/CSS, and Vite. It includes eight algorithm visualizations, a simulated memory tracker, Git lessons and a workflow simulator, practice challenges, a DSA quiz, pseudocode exploration, complexity comparison, a Big-O playground, and browser-local progress tracking.

## Questions and answers

**1. What is CodeViz?**  
An interactive educational web application that explains algorithms, memory concepts, and Git workflows through visual simulations.

**2. Why did you develop it?**  
To make abstract computing concepts easier to understand by showing operations step by step and allowing students to practise.

**3. Which technologies are used?**  
React, TypeScript, HTML, CSS, Vite, and browser localStorage.

**4. Why React?**  
React supports reusable components and state-driven UI updates.

**5. What is TypeScript?**  
A typed superset of JavaScript that helps catch certain errors during development.

**6. What is Vite?**  
A development server and build tool for frontend applications.

**7. Which algorithms are supported?**  
Bubble, Selection, Insertion, Merge, Quick, and Heap Sort; Linear Search and Binary Search.

**8. How does the visualizer work?**  
It generates a sequence of states containing the current array, active indices, and an explanatory message. The UI displays each state step by step.

**9. Why does Binary Search require sorted data?**  
It discards half of the search range after checking the middle value. This decision is valid only when the values are sorted.

**10. What is Big-O notation?**  
A way to describe how an algorithm's resource requirements grow as input size increases.

**11. What is the Memory Tracker?**  
A conceptual simulation that demonstrates variable creation, updates, release, and stack/heap ideas. It does not inspect actual process memory.

**12. What is Git?**  
A distributed version-control system that tracks changes to files over time.

**13. What is the staging area?**  
The intermediate area where selected changes are prepared for the next commit.

**14. What is a commit?**  
A saved snapshot of staged changes in repository history.

**15. Does CodeViz connect to real GitHub?**  
No. The Git Lab simulates repository workflows for learning and does not run Git commands or push to GitHub.

**16. Does the project use a database?**  
No database is used in this version. Selected progress and theme settings are stored in browser localStorage.

**17. What is localStorage?**  
Browser key-value storage that persists across reloads in the same browser profile. It is not a shared server-side database.

**18. What is the purpose of the quiz?**  
It tests understanding through multiple-choice questions, provides feedback, calculates a score, and stores the best score locally.

**19. Are Big-O bars actual runtime measurements?**  
No. They illustrate theoretical growth and are not benchmark timings.

**20. What are the limitations?**  
No backend, shared database, real Git integration, or real memory inspection is included. Progress is browser-local.

**21. What are future enhancements?**  
Automated tests, better accessibility, more practice material, optional synchronized progress, and additional safe repository exercises.

**22. How do you run the project?**  
Open the folder containing `package.json`, run `npm install`, then `npm run dev`, and open the local URL printed by Vite. Run `npm run build` for a production build check.

## Demo order
1. Home and Dashboard.
2. Run a sorting algorithm using `8, 3, 6, 1, 5`.
3. Demonstrate Linear Search and Binary Search.
4. Create, update, and release a simulated memory entry.
5. Explain working directory → staging → commit in Git Learning.
6. Perform a workflow in the simulated Git Lab.
7. Answer a practice challenge and a DSA quiz question.
8. Show Complexity Compare and the Big-O slider.
9. Open Progress & Badges and switch themes.
