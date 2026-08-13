# What Emmanuel wants (read this before changing the tracker)

This is a **gym tool I use on my phone**, not a hosting debate and not an architecture essay.

## Product (this is the job)

When I open the live page at the gym I need:

1. **Today’s session by name** — Push / Pull / Legs / recovery / Upper / Lower+core. Thursday is recovery. Upper is Friday. Recovery days are a checklist (Done), not Set / lb.
2. **Equipment for that day**, then **how to do each lift**, plus the **day image**.
3. **Light mode.**
4. **Useful training features**, not a pretty checklist:
   - last weight I used on that lift
   - rest timer after I check a set
   - this-week status and missed-day warning
   - Saturday check-in (weight, waist, protein)
   - mark session complete
5. **Logs stay in the browser.** Export CSV is the backup.

Hosting is **already done**: https://kooemmanuel.github.io/workout-tracker/  
Do not spend another turn on the URL, GitHub Pages, or “is it live.”

## Data (settled — do not re-litigate)

- **`plan.csv` is the only source of truth for the program.** Edit the spreadsheet-shaped file to change lifts.
- `index.html` must `fetch("plan.csv")` and parse quoted commas in `how_to`.
- Do **not** hardcode the 36 rows as a JavaScript array again.
- Do **not** delete `plan.csv`.
- `README.md` must match this: editing `plan.csv` changes the live plan after deploy.

## How to work

- Keep going on **features that help me train**.
- Do not “improve” working code I did not ask about.
- Do not ask me to choose CSV vs inline again. CSV won.
- If Cursor and Claude both touch this repo, follow this file. Product first, then CSV, never hosting.
