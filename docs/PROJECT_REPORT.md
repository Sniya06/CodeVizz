# CODEVIZ — Interactive Algorithm, Memory & Git Visualizer

## 1. Abstract
CodeViz is a browser-based educational application that helps students learn algorithms, memory concepts, and Git workflows through interactive demonstrations. It combines an algorithm visualizer, conceptual memory tracker, guided Git lessons, simulated Git workflow lab, practice challenges, DSA quiz, pseudocode explorer, complexity comparison, Big-O playground, and local progress tracking. Users can experiment with array values, inspect algorithm steps, practise version-control concepts, and review quiz feedback. The current version is a frontend-only educational application. It does not connect to a backend database, inspect real process memory, execute Git commands, or push to GitHub.

## 2. Problem Statement
Algorithm execution, memory organization, and version-control workflows can be difficult to understand from text-only notes. Students benefit from seeing comparisons, state changes, and workflow stages. CodeViz brings these topics together in one interactive learning environment.

## 3. Objectives
- Visualize six sorting algorithms and two searching algorithms.
- Let learners test small, user-provided arrays.
- Explain stack and heap concepts using simulated variables.
- Teach repository, staging, commit, branch, merge, and remote workflow concepts.
- Provide challenges, quiz feedback, and locally stored progress.
- Compare time complexity, auxiliary space, and algorithm stability.
- Illustrate common Big-O growth rates through an adjustable input size.
- Provide light and dark themes.

## 4. Technology Stack
| Technology | Purpose |
|---|---|
| React | Component-based interactive UI |
| TypeScript | Typed application logic |
| HTML and CSS | Structure, layout, styling, responsive interface |
| Vite | Development server and production build |
| Browser localStorage | Saves selected progress and theme preferences locally |

## 5. System Modules
### 5.1 Home and Dashboard
Introduce the application and provide links to its learning modules.

### 5.2 Algorithm Visualizer
Supports Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort, Heap Sort, Linear Search, and Binary Search. Each generated step includes array state, active indices, and an explanatory message. Binary Search operates on a sorted copy of the entered values.

### 5.3 Memory Tracker
Simulates variable creation, updates, and release to explain stack and heap concepts. It is a conceptual model and does not display actual runtime memory addresses or operating-system memory usage.

### 5.4 Git Learning
Introduces repositories, working directory, staging area, commits, branches, merging, and remote workflow through guided lessons.

### 5.5 Git Workflow Lab
Allows practice of file changes, staging, commits, branches, merge, and push/pull concepts in a simulated repository. It does not execute Git commands or connect to a remote repository.

### 5.6 Practice Challenges and DSA Quiz
Scenario-based challenges provide hints and feedback. The quiz evaluates multiple-choice answers, explains results, calculates a score, and saves a best score in browser storage.

### 5.7 Code and Pseudocode Explorer
Highlights pseudocode one line at a time and shows related complexity information.

### 5.8 Complexity Compare and Big-O Playground
Compares time complexity, auxiliary space, and stability for the eight algorithms. The Big-O playground uses illustrative growth values, not measured benchmark timings.

### 5.9 Progress and Badges
Displays selected module activity, challenge count, quiz results, and badges using local browser storage. This data is not synchronized between devices.

### 5.10 Theme Support
Switches between light and dark appearance and stores the selected preference locally.

## 6. General Workflow
1. Open the home page and choose a module.
2. Enter an array and inspect algorithm steps, or use the memory tracker to simulate variable operations.
3. Learn Git concepts and practise them in the simulated Git Lab.
4. Complete practice challenges and quiz questions.
5. Explore pseudocode and complexity information.
6. Review locally stored progress and badges.

## 7. Architecture
The application entry point is `src/main.tsx`; the main React application and module logic are in `src/App.tsx`; styles and responsive layouts are in `src/style.css`. Vite serves the development version and creates the production bundle. The general flow is: user interaction → React state update → UI refresh → selected values saved to localStorage. No server or database is included in this version.

## 8. Advantages
- Brings multiple foundational computing topics into one application.
- Shows algorithm state changes rather than only static explanations.
- Supports custom array input and repeated practice.
- Combines guided Git learning with a workflow simulator.
- Includes quizzes, challenges, complexity comparisons, and progress feedback.
- Runs locally without API keys or cloud services.

## 9. Limitations
- No login, backend, or shared database.
- Progress is limited to the current browser profile.
- Git operations and memory behavior are simulations.
- Big-O values are illustrative rather than benchmark results.
- Manual testing is required; automated test coverage can be added in future work.

## 10. Future Enhancements
- Add unit and component tests.
- Add optional user accounts and database-backed progress synchronization.
- Add more algorithm explanations and practice questions.
- Improve keyboard accessibility and perform cross-browser testing.
- Consider a safe, optional real-repository exercise for advanced learners.

## 11. Conclusion
CodeViz combines algorithm visualization, conceptual memory tracking, Git education, practice, and complexity exploration in a single browser-based application. It helps students connect theory with interactive examples and provides a foundation for future improvements in testing, accessibility, and persistence.
