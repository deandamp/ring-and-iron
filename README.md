# Ring & Iron

A personal boxing & strength training planner — a small, self-contained web app (installable to your phone's home screen, works offline). All training data is stored locally in your own browser; nothing is sent anywhere and nothing personal lives in this repo.

**Live app:** https://deandamp.github.io/ring-and-iron/

## What it does
- 6-day boxing + strength week, with an **Ease Back** phase for returning from a layoff
- Tick-off sessions with **per-set weight logging** (shows last time's weight), and an editable **rep count on your last set** for when it falls short of the plan
- Log a **drop set** off the final set of any lift on strength days (up to three drops, weight × reps)
- **Progress** tab: bodyweight chart + per-lift top-set trends
- Boxing **round timer** with bell
- Swap any day for an alternative (Circuit / Solo Boxing / Quick Home / Cardio)
- Optional warm-up picker and optional finisher
- **Back up / Restore** your log to a file

## Tech
Plain HTML/CSS/JS in a single `index.html`, plus a web app manifest and a service worker for offline + install. No build step, no dependencies.
