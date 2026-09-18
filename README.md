# EngiMind Quiz

A single-page, self-contained quiz app for testing knowledge of four developer fundamentals:

- **Claude Code** — slash commands, hooks, subagents, MCP servers, plugins
- **Git & GitHub** — commits, branches, pull requests, merge conflicts, workflows
- **Terminal** — navigation, file permissions, search, process inspection
- **Clean Code** — DRY, KISS, single responsibility, refactoring, testing, YAGNI

40 questions total (10 per category), each with instant feedback and a short explanation. Pick which categories to include and how many questions to answer, then review your per-category breakdown and missed answers at the end.

## Run it

Just open `index.html` in a browser — no build step, no dependencies.

## Deploy it (GitHub Pages)

1. Repo Settings → Pages
2. Source: Deploy from branch → `main` → `/ (root)`
3. Save — the app will be live at `https://sksarfarajali.github.io/EngiMind/`

## Tech

Plain HTML, CSS, and vanilla JavaScript. Light/dark theme aware (follows system preference, with a manual toggle). Best score is remembered locally in your browser via `localStorage`.
