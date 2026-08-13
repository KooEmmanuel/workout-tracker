# Workout tracker

Static HTML + CSV for the 12-week body recomposition plan.

## Use

Host the whole `workout-tracker` folder (Netlify, GitHub Pages, or any static host).  
Or from this folder:

```
npx --yes serve .
```

Then open the URL it prints. Don’t double-click `index.html` — the browser blocks `plan.csv`.

## Files

| File | Role |
|---|---|
| `index.html` | Today’s session, set checkoffs, weight log |
| `plan.csv` | What to do each weekday (edit this to change the plan) |
| `images/` | Day guide posters |

Logs stay in the browser (`localStorage`). Use **Export log CSV** to keep a file.

Set **Plan start date** to the Monday you began (default 2026-07-28) so week 1–12 is right.
