# CUT. — AI Fat Loss Coach

A self-hosted fat loss tracking app powered by Claude AI. Designed specifically for your cut — blunt, data-first, no fluff.

## Features

- **Dashboard** — Weekly & monthly averages, trend chart, auto-generated recommendations
- **Log** — Daily weight, steps, calories, protein + noise flags (alcohol, deload, rash, etc.)
- **Measurements** — Waist, biceps (flexed/unflexed), chest tracking with body composition interpretation
- **AI Coach** — Ask anything about your cut; the coach has your full history in context
- **CSV Import** — Bulk load historical weight data

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `my-cut-tracker`)
2. Upload `index.html` to the root of the repository
3. Go to **Settings → Pages** and set source to `main` branch, root folder
4. Your app will be live at `https://yourusername.github.io/my-cut-tracker/`

## First-time setup

1. Open the app in your browser
2. Enter your **Anthropic API key** (get one at [console.anthropic.com](https://console.anthropic.com))
3. Your historical data is pre-loaded automatically
4. Go to **Settings** to confirm your profile (starting weight, goal, step/calorie targets)

## Your data

- All data is stored in your **browser's localStorage** — it never leaves your device
- Your API key is stored locally and sent only to Anthropic's servers for AI responses
- Use **Export JSON** in Settings to back up your data

## Adding new weigh-ins

**Option A — Manual (Log tab):**
Enter date + weight + optional flags

**Option B — CSV import (Log tab → bottom section):**
```
2025-06-09, 104.75
2025-06-10, 104.20
```

## AI Coach quick questions

The coach already knows:
- Your full weekly and monthly average history
- Your measurements and waist trend
- Your step/calorie/protein targets
- All the rules from your original ChatGPT coaching sessions

Try asking:
- *"Is this a true plateau?"*
- *"Should I drop calories?"*
- *"Am I losing muscle?"*
- *"What's my ETA to get shredded?"*
- *"What should I do next week?"*
