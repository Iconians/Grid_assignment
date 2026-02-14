### Graded Assignment: Grid Layout Mastery

**What this assignment is for:** You show that you can build a layout using only what you learned in Lessons 6.1–6.3 (grid container, columns/rows, placement, minmax, auto-fit/auto-fill). You do **not** need media queries; Grid’s own features (e.g. auto-fit, minmax) handle different widths.

**Requirements:**
1. Create a grid-based page layout with header, main content, sidebar, and footer using **only CSS Grid** for that layout.
2. Use `grid-template-areas` to name and place the main regions (header, main, sidebar, footer).
3. Include a card grid with at least 8 items using `repeat(auto-fit, minmax(...))` or `auto-fill` so the number of columns adjusts to width.
4. Use `minmax()` for at least one set of columns or rows.
5. Include at least one section that spans multiple grid cells (e.g. `grid-column: span 2` or `grid-area`).
6. Use grid alignment (e.g. `justify-items`, `align-items`) where it helps.
7. Include at least one nested grid (a grid item that is also `display: grid`).
8. Use `gap` (or row-gap/column-gap) for spacing.

**Deliverables:**
- HTML file with clear structure
- CSS file that uses Grid for layout as taught in this module
- Code comments that explain your Grid choices

**Grading Criteria:**
- Correct Grid syntax and properties from this module (30%)
- Use of grid-template-areas and placement (20%)
- Use of auto-fit/auto-fill and minmax (25%)
- Code organization and comments (15%)
- Layout and spacing (10%)
