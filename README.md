# SabeelCode

SabeelCode is a small, local-first collection of programming problems and interactive problem pages — a lightweight, personal alternative to platforms like LeetCode designed for learning, practicing, and sharing algorithmic problems.

This repository contains example problem pages (HTML + Tailwind) and a simple UI to browse problems. It's intended to be a starting point: add problems, tests, and features to make it your own practice platform.

## Vision

- Host curated practice problems with clear statements, examples, and constraints.
- Provide an extensible UI for browsing problems (locked/unlocked states, categories, difficulty).
- Let users add solutions in multiple languages, run quick local tests, and track progress.

## Current features

- Static problem pages (example: `index.html` — "1. Sum")
- Responsive UI using Tailwind CSS (via CDN)
- Collapsible sidebar with placeholders for future problems and locked states

## Tech stack (current)

- Plain HTML/CSS/JS
- Tailwind CSS via CDN for styling

## Getting started (run locally)

1. Open `index.html` directly in a browser for a quick preview.
2. Or run a simple local server from the project root:

```bash
# from the project root
python -m http.server 8000
# then open http://localhost:8000
```

## How to contribute

- Add a new problem: create a new HTML file (or add to a problems directory) following the existing `index.html` structure.
- Extract shared assets: move inline scripts and styles to `assets/` (JS/CSS) for reuse.
- Add tests: include small example input/output tests (per problem) and a test runner script.
- Improve UX: add search, categories, difficulty tags, and user progress tracking.

Best practices: keep problem statements simple, include at least one example, and list constraints.

## Suggested roadmap

1. Project structure: create `problems/`, `assets/`, and `solutions/` folders.
2. Convert Tailwind CDN to a build step (optional) to support custom styles.
3. Add a small Node.js/Express or static site generator workflow for easier authoring.
4. Add solution runner for one or two languages (e.g., Node.js, Python) and simple unit tests per problem.

## License

Add a `LICENSE` file if you want to publish this project with a specific license. No license is included by default.

---

If you'd like, I can:

- Create the `problems/` and `assets/` folder layout and move `index.html` into `problems/`.
- Add a tiny Node or Python dev server with live reload.
- Scaffold a problem template HTML and a CONTRIBUTING.md.

Tell me which of the above you'd like next and I'll implement it.
