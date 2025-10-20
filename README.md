# Code Cracker — Matrix Password Checker 🔐💻

**Code Cracker** is an interactive, Matrix-themed password strength analyser built as a single-page HTML app. It provides real-time feedback on password quality, visual strength indicators, and an AI-style assistant that suggests improvements. The UI intentionally uses a retro “Matrix” aesthetic to make learning about password security engaging.

Files
- `code cracker.html` — main application (single-file web app using React via CDN and Babel in the browser). :contentReference[oaicite:1]{index=1}

---

## Demo / Purpose

**Purpose:** Teach users about password complexity and best practices by providing immediate, actionable feedback and suggestions.  
**Audience:** Students, apprentices, or anyone who wants a quick interactive tool to test and learn password hygiene.  
**Estimated time to use:** 2–5 minutes to test a few passwords and read the suggestions.

---

## Features

- Real-time password analysis (length, upper/lowercase, numbers, special chars).  
- Scoring and strength categories: `weak`, `fair`, `good`, `strong`.  
- Visual strength bar with animated Matrix background.  
- Quick help (short tips) and detailed guidance via an on-screen assistant.  
- Client-side only — no server or network required (works offline after download).  
- Built with accessible, copyable code so it’s easy to learn from or adapt.

---

## Built with

- HTML5 + CSS3  
- **React** & **ReactDOM** (CDN) for UI state & rendering  
- **Babel (in-browser)** to allow JSX — no build step required  
- Vanilla JavaScript for logic and simple "AI assistant" responses

> Note: The application uses CDN links to React, ReactDOM and Babel so you only need to open the HTML file in a modern browser.

---

## Run locally (quick)

### Option A — Open directly (simplest)
1. Download the repo or the single file `code cracker.html`.  
2. Double-click `code cracker.html` or open it in your browser (`File → Open File...`).  
Works in Chrome, Edge and Firefox.

### Option B — Serve via simple HTTP server (recommended for consistent behaviour)
```bash
# Python 3
python -m http.server 8000
# Then open http://localhost:8000/code%20cracker.html
