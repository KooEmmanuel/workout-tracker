# Workout tracker

Static HTML + CSV for the 12-week body recomposition plan.

## Use

Open `index.html` in a browser (double-click is fine). The plan is built into the page.

You should see: **Today: [session name]**, equipment list, the day poster, then each lift with how-to + set checkboxes.

Thursday in this plan is recovery. Upper strength is **Friday** — tap Fri if that’s the session you want.

## Files

| File | Role |
|---|---|
| `index.html` | Today’s session, set checkoffs, weight log |
| `plan.csv` | What to do each weekday (edit this to change the plan) |
| `images/` | Day guide posters |

Logs stay in the browser (`localStorage`). Use **Export log CSV** to keep a file.

Set **Plan start date** to the Monday you began (default 2026-07-28) so week 1–12 is right.
