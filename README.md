# GanitGo

A simple, responsive single-page web app for practicing multiplication tables.

## Features

- **Table selection** — choose any combination of tables from 1–20 using the chips on the home screen. Nothing is selected by default; you'll be prompted to pick at least one before starting.
- **Practice mode** — 10 questions, drawn only from your selected tables. Type an answer and it auto-validates as soon as you've entered enough digits: correct answers turn green and auto-advance after 2 seconds; incorrect answers turn red, show the right answer, and wait for you to continue.
- **Race mode** — 60-second timed challenge with multiple-choice answers. Streaks increase your score bonus; a wrong answer resets the streak but not the clock.
- **Revise mode** — a plain reference view of the 11–20 times tables, no quiz involved. Pick a table via tabs to see all 12 rows (e.g. `11 × 1 = 11` through `11 × 12 = 132`). Always available, regardless of what's selected in the chips.
- **Results screen** — score, accuracy, and streak summary after each round, with options to replay or change tables.

No data is saved between sessions — refreshing or closing the app resets everything.

## Running it

This is a single self-contained HTML file with no build step or dependencies.

1. Open `index.html` (or `ganitgo.html`) directly in any modern browser, **or**
2. Host it on any static file server / CDN.

## Tech

Vanilla HTML, CSS, and JavaScript — no frameworks or external libraries required (Google Fonts are loaded via CDN for typography).
