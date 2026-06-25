# 🌿 Daily Reset

> A calm, single-file daily command centre for people who feel overwhelmed and unfocused at work.

No app to install. No account to create. No subscription. Just one HTML file you open in your browser — and a clear shape for your day.

---

## What is this?

**Daily Reset** is a lightweight productivity tool built into a single self-contained HTML file. Open it in any browser, and it greets you with the time of day and a structured space to do four things:

- **Commit to your three most important tasks** — and nothing more
- **Park every other thought** so it's out of your head without being lost
- **Track a small set of daily habits** with visible streaks
- **See your momentum** across the past 7 days at a glance

It's designed around one core idea: **overwhelm comes from trying to hold too many things at once**. Daily Reset gives you a place to put them down.

---

## Why you should use it

Most productivity tools do too much — they become another thing to manage. Daily Reset does the opposite. It's deliberately minimal:

- **Zero setup.** Download the file. Open it. You're done.
- **Zero friction.** No login, no dashboard, no tutorial. The interface explains itself.
- **Zero cost.** It's a single HTML file. Host it yourself, open it locally, or share it freely.
- **It actually changes behaviour.** The "Three" cap forces a real choice about what matters. The parking lot stops the mental loop of "don't forget this." The habit streaks make showing up feel rewarding.
- **Your data stays yours.** Everything saves in your browser's local storage automatically. Nothing is sent anywhere.

If you've ever ended a day feeling busy but not productive — this is built for that feeling.

---

## Features

### ✅ Today's Three
Cap your daily priorities at exactly three. Not a to-do list — a commitment. You choose the three things that would make today feel like a win. Anything else goes in the parking lot. Each item has a checkbox; checking them off turns the number amber and strikes the task, giving you a small, satisfying signal of progress.

### 🅿️ Parking Lot
A frictionless brain dump. When something pops into your head mid-task, type it here and forget it — safely. Items sit in the lot until you're ready to deal with them. You can **promote** any item directly into Today's Three with one click (the tool tells you if your Three is already full). Clear the lot at any time.

### 🔁 Daily Habits
Four starter habits are included, tuned for focus and work-life balance:
- Set your Three before checking messages
- One distraction-free focus block
- A real break away from the screen
- Honor a hard stop to the workday

You can rename, remove, or add your own via the **Edit** button. Habits that you keep multiple days in a row show a **flame streak** badge so you can see the chain building.

### 📊 Momentum Strip
A 7-day grid at the bottom of the page — one dot per habit, per day. Dots light up amber when a habit is marked done. It's not a scorecard; it's a mirror. Watching the pattern fill in is what makes the routine stick.

---

## How it works

```
daily-reset.html  ← the entire app, one file
```

- Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step, no dependencies
- State is managed in memory and persisted automatically to browser storage between sessions
- Data is stored locally in your browser — nothing leaves your device
- Google Fonts (Fraunces + Instrument Sans) are loaded at runtime for typography; the app works without them if you're offline, falling back to system fonts

---

## Getting started

**Option 1 — Use it directly from GitHub Pages (easiest)**
Visit the live link and open it in your browser. Bookmark it or pin it as a tab.

**Option 2 — Download and open locally**
1. Download `daily-reset.html`
2. Open it in any modern browser
3. That's it — no server needed

**Option 3 — Host your own copy**
Fork this repo, enable GitHub Pages under Settings → Pages, and you'll have your own permanent URL within minutes.

---

## A note on data storage

Your data saves automatically to your browser's local storage every time you make a change. This means:

- ✅ It's there the next time you open the same browser on the same device
- ✅ Nothing is sent to any server — it's entirely private
- ⚠️ Clearing your browser's site data will erase it
- ⚠️ It won't follow you to a different browser or device

**Tip:** If you always open Daily Reset from the same pinned tab in the same browser, your data will reliably be there every morning.

---

## The philosophy behind it

Daily Reset is built on three well-established ideas in productivity research:

**1. Decision fatigue is real.** Every open loop in your head costs cognitive bandwidth. The parking lot gives those loops a home so your working memory can focus.

**2. Constraint improves output.** Capping priorities at three isn't arbitrary — it's a forcing function. When you can only pick three, you pick the right three.

**3. Habit stacking works through identity, not willpower.** Seeing a streak grow makes you want to protect it. The momentum strip makes the habit visible, which makes it easier to keep.

---

## Customising it

The file is intentionally readable. Open it in any text editor:

- **Change the default habits** — find `DEFAULT_HABITS` near the top of the `<script>` tag
- **Change the colour palette** — all colours are CSS custom properties in `:root { ... }`
- **Change the fonts** — swap the Google Fonts import URL at the top of the `<style>` tag

---

## Contributing

Issues, suggestions, and pull requests are welcome. Keep it simple — the goal is a tool that does a few things well, not a platform.

---

## License

MIT — use it, fork it, share it, adapt it.

---

*Built to solve a real problem: feeling busy but not focused. Open it tomorrow morning and see if three priorities changes how your day feels.*
