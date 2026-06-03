# 027 · Habit Heatmap

**AppADay · Day 027**
Track up to five daily habits with a GitHub-style heatmap grid. Mark days done, watch streaks build, and switch between habits with a single tap.

## What It Does

Habit Heatmap displays the current month as a calendar grid. Tap any past or current day to toggle it complete — it fills bright green and your streak counter updates instantly. Future days are ghosted and untappable. Up to five habits can be tracked simultaneously, each with its own grid and statistics.

## How to Use

1. **Track a habit** — tap any day in the grid to mark it done. Tap again to unmark.
2. **Switch habits** — tap any pill tab at the top to view a different habit's grid.
3. **Manage habits** — tap ⚙️ to open the settings sheet. Rename habits, add new ones (up to 5), or delete one. Deleting removes that habit's data permanently.

## Technical Notes

- Single-file vanilla HTML/CSS/JS — no frameworks, no build step
- Data stored in `localStorage` per habit per month (key format: `heatmap-data-[id]-YYYY-MM`)
- Habit list stored under `heatmap-habits-v2`
- Each month gets its own storage bucket — historical months are preserved
- Clearing browser data or using private/incognito mode will erase stored habits

## Definition of Complete

- [x] Functional — habits toggle correctly, streaks calculate accurately
- [x] Single purpose — tracks daily habit completion, nothing else
- [x] Mobile friendly — wrapping tab layout, tap targets sized correctly, safe area insets applied
- [x] Visually polished — dark forest aesthetic, Playfair Display + JetBrains Mono, smooth transitions
- [x] Published — live on GitHub Pages before midnight CDT

## Stack

HTML · CSS · JavaScript · Google Fonts (Playfair Display, JetBrains Mono)

---

[← Back to AppADay Portfolio](https://augustineiacopelli.github.io/appaday)
