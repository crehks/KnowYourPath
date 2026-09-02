# IS Career Launchpad

Prototype for the BYU IS 401 Junior Core Case ("IS Career Launchpad" — Fall 2026). A single-file
web app with two modules: a career path discovery tool covering six IS career tracks, and a mock
interview practice tool with automated feedback scoring.

## Running it

No build step, no dependencies. Just open `index.html` in any browser.

## What's in here

- `index.html` — the entire app (HTML/CSS/JS in one file, per the case's technical requirements).

## Team workflow

1. Clone the repo:
   ```
   git clone https://github.com/<owner>/is-career-launchpad.git
   cd is-career-launchpad
   ```
2. Make your changes to `index.html`.
3. Commit and push:
   ```
   git add .
   git commit -m "describe your change"
   git push
   ```
4. If you don't have push access yet, ask the repo owner to add you under
   **Settings → Collaborators**.

Since it's a single file, coordinate before editing at the same time as a teammate to avoid merge
conflicts — claim a section (e.g. "I've got the interview scoring logic") in your group chat before
you start.

## Notes for the individual reflection / evaluator questions

- Salary ranges and role data in the app are illustrative estimates (see the in-app sourcing notes
  and the footer disclaimer) — modeled on typical patterns from sources like the BLS Occupational
  Outlook Handbook, Glassdoor, and Levels.fyi. Spot-check current figures before presenting.
- Interview questions were drafted from general knowledge of entry-level IS interview formats, not
  a live pull from job postings/interview databases — the case's guiding questions ask how you
  validated this, so plan a quick research/spot-check pass per role before demo day.
