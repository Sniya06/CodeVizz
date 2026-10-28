# CodeViz — Manual Testing Checklist

Start the application using `npm install` and `npm run dev`. Record actual outcomes after testing; do not mark tests passed without running them.

| ID | Test | Expected result |
|---|---|---|
| T01 | Open `/` | Home page loads |
| T02 | Open each dashboard/module link | Correct module loads without a blank page |
| T03 | Run each sorting algorithm on `8,3,6,1,5` | Final array is sorted ascending |
| T04 | Linear Search for an existing value | Matching index is reported/highlighted |
| T05 | Linear Search for a missing value | Not-found result is shown |
| T06 | Binary Search for present and absent values | Correct result appears using sorted input |
| T07 | Create, update, release a memory entry | Simulated state reflects each operation |
| T08 | Move through Git Learning topics | Lesson content and navigation update |
| T09 | Modify, stage, and commit a sample file | Simulated repository state updates |
| T10 | Try branch and merge actions | Simulator displays the simulated result |
| T11 | Answer a practice challenge and show a hint | Feedback and hint display correctly |
| T12 | Complete the DSA quiz | Score screen appears and best score is saved locally |
| T13 | Step through pseudocode | Current line highlight updates |
| T14 | Open Complexity Compare | Eight algorithms and complexity information appear |
| T15 | Move Big-O input-size slider | Growth values and bars change |
| T16 | Revisit Progress after activity | Locally tracked progress is reflected |
| T17 | Toggle theme and reload | Theme preference persists in the same browser |
| T18 | Resize to narrow screen | Content remains usable without major overlap |
| T19 | Run `npm run build` | TypeScript check and Vite production build succeed |

Note: Git and memory behavior are educational simulations. Browser storage is local to the current browser profile.
