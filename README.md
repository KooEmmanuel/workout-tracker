# Workout tracker

Static HTML + CSV for the 12-week body recomposition plan.

Live: https://kooemmanuel.github.io/workout-tracker/

Read `OWNER.md` before changing anything.

## Use

Open the live URL on your phone. You should see today’s session name, equipment, the day poster, how-to for each lift, last weight, and a rest timer.

Thursday is recovery. Upper strength is **Friday** — tap Fri if that’s the session you want.

## Files

| File | Role |
|---|---|
| `index.html` | Session UI, set checkoffs, weight log, timer |
| `plan.csv` | **The plan.** Edit this to change exercises. `log` is `weight` or `check`. |
| `images/` | Day guide posters |
| `OWNER.md` | What this app is for (do not ignore) |

Logs stay in the browser (`localStorage`). Use **Export log CSV** to keep a file.

Set **Plan start date** to the Monday you began (default 2026-07-28) so week 1–12 is right.

Double-clicking `index.html` will not load the plan. Use the hosted URL.
