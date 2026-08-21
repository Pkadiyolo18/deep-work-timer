# Deep Work Timer

A minimal, single-file web app for tracking focused study/work chunks and totaling how much deep work you actually put in each day.

- **Stopwatch** mode: free-running count up, log whenever you stop.
- **Countdown** mode: click the clock and type a duration (e.g. `45` or `45:30`), or use the quick presets — auto-logs when it hits zero.
- Label each chunk with an **activity** so you know what the time went to.
- Track **breaks** (pausing counts as a break) and **distractions** (enter a count in the popup when you log a session) per session.
- Daily totals are **hidden until you click to reveal them** — stay focused instead of clock-watching.
- History view with a per-day breakdown you can expand to see individual logged sessions.
- **Charts** tab: a weekly bar chart scaled against an 8-hour daily goal, and a year-long heatmap you can click into for any day's detail.
- Auto-pauses if your computer goes to sleep, so idle time never gets counted as focus time.

No build step, no server, no dependencies — it's one HTML file.

## Using it

Just open `index.html` in a browser (or visit the hosted link, if this repo has GitHub Pages enabled).

**Your data never leaves your device.** Everything is saved to your browser's local storage — there's no backend, database, or account. That also means:
- Your history is tied to *this specific browser* on *this device*. Switching browsers (or clearing site data) starts fresh.
- If multiple people use the hosted link, each person's logged sessions stay private to their own browser — nobody else can see them.

## Background photo credit

Coastline photo by [Qingbao Meng](https://unsplash.com/@qingbao) via [Unsplash](https://unsplash.com/photos/igFr7hd4).


edited 8/6/2026. 
