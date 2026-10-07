# O'clock 🕐

A to-do and reminder web app with a live ticking analog clock, a time-based daily agenda, and browser notifications — built as a single self-contained HTML file (no build step, no framework, no backend).

## Features

- **Live analog clock** — SVG clock face with hour/minute/second hands that actually tick
- **Add tasks** with an optional date and time
- **Agenda grouped by Today / Tomorrow / Later / No time set**, sorted by time
- **Overdue tasks** are flagged in a contrasting color
- **Reminders** — browser notifications + a gentle chime (Web Audio API) when a timed task comes due
- **Light & dark themes** — pink/violet in light mode, purple/indigo in dark mode, toggle in the header
- **Persistence** via `localStorage` — no account, no server, your data stays in your browser

## Usage

Open `index.html` in any modern browser — no installation or build step required. You can also enable GitHub Pages on this repo (Settings → Pages → deploy from `main` branch) to host it at a public URL.

## Stack

Plain HTML, CSS (custom properties for theming), and vanilla JavaScript. Fonts (Fraunces, JetBrains Mono, Inter) are loaded from Google Fonts.
