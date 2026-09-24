# Nguyen Vo An Vi - AI / ML Engineer Portfolio

A responsive one-page static portfolio aligned with the latest CV. The site highlights selected AI/ML projects, competition experience, awards, technical skills, education, and contact information.

It does not need Node.js, a database, environment variables, or a backend.

## Current content structure

- **About & Education** — UIT, B.Sc. Computer Science, GPA, English proficiency, technical skills
- **Selected Projects**
  - UIT Knowledge Retrieval Chatbot
  - AgriSmart Agricultural Marketplace
  - Face Recognition System
- **Competition Experience**
  - CLEF 2026 CheckThat! Lab
  - EXACT 2026 International Data Science Competition
- **Awards**
  - Hedge Fund Time-Series Forecasting (Kaggle) — Ranked 7th / 982 teams
  - Mastering IT 2026 — Top 5 Finalist & Consolation Prize
  - SPD Challenge 2026 — First Prize

## Preview locally

Open `index.html` directly in a browser, or run a local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy on Vercel

1. Push all files in this folder to the repository root.
2. In Vercel, choose **Add New > Project** and import the repository.
3. Choose **Other** as the framework preset if Vercel does not detect it automatically.
4. Leave Build Command empty and set Output Directory to `.` if Vercel asks.
5. Click **Deploy**.

## Main files

- `index.html` — portfolio content and external links
- `styles.css` — responsive visual design
- `script.js` — reveal-on-scroll animation
- `public/Nguyen_Vo_An_Vi_CV.pdf` — downloadable CV used by both Resume buttons
- `public/favicon.svg` — browser favicon
- `preview.png` — repository preview image

## Updating the CV later

Replace `public/Nguyen_Vo_An_Vi_CV.pdf` while keeping the same filename so all Resume links continue to work without changing the HTML.
