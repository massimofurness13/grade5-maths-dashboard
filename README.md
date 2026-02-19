# Grade 5 Mathematics Dashboard — BISES

Interactive data analysis dashboard for Grade 5 PTM (Progress Test in Mathematics) results at the British International School of El Salvador.

## Features

- **Skill Heatmaps** — Per-student performance across 18 skill categories, compared to UK averages
- **Class Performance Comparison** — SAS scores and attainment across all four Grade 5 classes
- **SAS Band Distribution** — Breakdown by GL Assessment standard age score bands
- **PTM Progress Tracking** — Student progress from May to October 2025
- **Test Completion Analysis** — Questions attempted vs SAS score, with missed-question pattern analysis
- **Question & Curriculum Analysis** — All 58 questions ranked by difficulty, with underperformance insights
- **Key Findings** — Per-class factual summaries of weak topics, students below average, progress changes, and strengths

## Privacy

Student names are encrypted (AES-256-GCM) and redacted by default. Enter the password to reveal real names.

## Usage

Open `index.html` in any modern browser. No server required — everything is self-contained in a single HTML file.

## Live Demo

Enable GitHub Pages on this repo to host it at `https://[username].github.io/grade5-maths-dashboard/`

## Tech

- Chart.js 4.4.1 (CDN)
- Web Crypto API (SubtleCrypto) for client-side AES-GCM decryption
- PBKDF2 key derivation (SHA-256, 100k iterations)
- Zero dependencies beyond Chart.js
