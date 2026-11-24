# Cyber Detective: Spot the Threat

A beginner-friendly cybersecurity awareness game. Study the evidence in each case and choose the safest response.

**Live demo:** https://radiant-klepon-7b8c81.netlify.app/

## Features
- 5 realistic cases: phishing email, CEO text scam, unknown USB drive, fake IT call, malicious attachment
- 30-second timer per case with a live countdown bar
- Optional hints (a hint halves the points for that case)
- Explanations after every answer, so players learn why
- Score, rank and total time on the results screen
- Blue theme, responsive layout, keyboard and screen-reader friendly

## Run it locally
No install needed. Download the repo and open `index.html` in a browser.

## Add your own cases
Open `index.html` and add an entry to the `CASES` array with a title, type, evidence, hint and four options (one marked `ok: true`).

## Built with
HTML, CSS and vanilla JavaScript in a single file.
