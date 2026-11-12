# Edubull Studio

Redesigned `/studio` page for edubull.com — a single, self-contained HTML file (`index.html`) with no build step.

## Workflow
1. **Choose a class** — Early Years (Nursery, LKG, UKG), Primary (Class 1–5), Middle (Class 6–8).
2. **Pick a subject** — filter chips show only the subjects that have games for that class.
3. **Play** — each game card links to its studio URL.

## Features
- Class-first navigation with a persistent sidebar (matches the EduLibrary dashboard), breadcrumbs, prev/next class, hash routing (`#/class/class3`) so links are shareable.
- Global search (`/` to focus, `Esc` to clear/go back) across games, subjects and classes.
- Light/dark themes, favourites and sidebar state remembered in `localStorage`.
- Fully responsive (mobile drawer sidebar), keyboard accessible, reduced-motion safe.

## Editing content
All classes, subjects and games live in the `DATA` block at the top of the `<script>` in `index.html`.
Add a game by appending to `GAMES` with its `subject`, the `classes` it belongs to, and its `url`.
