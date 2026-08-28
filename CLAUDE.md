# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository overview

This is `samuelp4065.github.io`, a single-page personal landing site hosted for free via GitHub Pages. There is no build system, no package manager, and no test suite — the entire site is `index.html`, a self-contained HTML file with inline CSS and no external dependencies or JavaScript.

## Development

- **Preview locally**: open `index.html` directly in a browser, or serve the directory (e.g. `python3 -m http.server`) and visit `http://localhost:8000`.
- **Deploy**: pushing to `main` publishes automatically via GitHub Pages — there is no separate build/deploy step.
- There is no linter, formatter, or test runner configured for this repo.

## Structure

- `index.html` — the entire site. Contains the page markup, inline `<style>` block (CSS custom properties for theming under `:root`, animated background blobs via CSS keyframes), and outbound links (GitHub, LinkedIn, YouTube, email).
- `Resume_SamuelPark.pdf`, `RoboticsEngineering_SamuelPark.pdf` — resume documents, not referenced from `index.html`.
