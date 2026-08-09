# "Does This Place Even Restock?" — Aspretto Stock Visibility Case Study

STET301 — Human-Computer Interaction (UI/UX) · Mid-term Examination: Empathy to Execution Flow
Prepared by Pranav Bagul

## What this is

A UX research case study on a real, recurring campus pain point: hostelers can't tell if Aspretto (the only non-coffee snack counter on campus) is stocked or staffed before making the walk over, so they regularly give up and wait until dinner.

This project runs the full empathy-to-execution process — persona research, empathy and journey mapping, card sorting, tree testing, and MoSCoW/DFV prioritization — to arrive at a validated, prioritized feature set. No UI screens, no app build. Just the research, structure, and prioritization behind one.

Built as a single scrolling page in plain HTML and CSS — no JavaScript, no frameworks, per the assignment brief.

## Live site

https://skylord69-py.github.io/Campus-Quick-Snack-Case-Study/

## What's inside

```
index.html                  the whole case study, one page
style.css                   all styling
images/                     12 hand-drawn research artifacts —
                             persona, empathy map, journey map, IA trees,
                             MoSCoW board, DFV matrix, observation log
data/
  survey-results.pdf        full 12-respondent survey export
  card-sort-results.pdf     full 11-respondent card sort export
```

## Process, briefly

1. **Empathize & Define** — proto-persona → 12-person survey + in-person observation → validated persona → empathy map → journey map with emotion line → pain point → 3 user stories
2. **Ideate & Evaluate** — 18 candidate features → hybrid card sort (11 valid responses) → V1 information architecture → tree test (6 participants, 10 tasks) → 2 structural pivots, evidenced by both the sort and the test → V2 IA
3. **Prioritize** — MoSCoW (exactly 4 Must-Haves) → DFV matrix to settle the hardest-debated feature for the final slot

Full data and reasoning for every step is on the page itself, with source PDFs linked where relevant.

## Viewing it locally

```bash
git clone <repo-url>
cd <repo-name>
open index.html      # macOS
# xdg-open index.html   (Linux)
# start index.html      (Windows)
```

No build step, no dependencies — it's a static page.

## Notes

- All research (survey, card sort, tree test, observation) was collected for this assignment; nothing here is placeholder or simulated data.
- Images are photographs of hand-drawn artifacts, not digital mockups.
