# 📅 Daily Schedule Planner

> **Plan your day. Track what you actually did. See exactly where your time went.**

A free, privacy-first, browser-based daily planner that goes beyond scheduling , it tracks your real productivity, logs your distractions, and generates weekly performance reports. No login. No subscription. No data leaves your device.


## 🌟 Why This Exists

Most productivity apps tell you what to *plan*. Almost none tell you the honest truth about what you *actually did* — and why you fell short.

**Daily Schedule Planner** is built around one core idea: **accountability without complexity**. You plan your day, log what really happened (including the Instagram scrolls and phone calls), and at the end of the week you have a clear picture of where your time went — and what's costing you your productivity.

It works for anyone:
- 🎓 **Students** tracking study sessions and revision blocks
- 💼 **Job seekers** managing applications, prep, and research time
- 💻 **Freelancers** logging billable hours across multiple clients
- 🏃 **Anyone** trying to build better daily habits


## ✨ Features

### 📋 Today Tab — Plan & Track

- **Fully customizable activity cards** — rename, add, or delete categories to match your life, not a template someone else designed
- **Editable schedule blocks** — click any time, name, or note to edit it directly; use ↑↓ arrow keys to nudge times by 5 minutes
- **＋ / − buttons** on every block , insert a new block directly below, or delete it silently
- **Category dropdown** — assign each block to the right activity; the name auto-fills from your card label
- **Inline break logging** — log a distraction inside any block (e.g. a 30-min phone call during Research time); net productive time recalculates automatically
- **Separate break blocks** — log standalone breaks like lunch, going out, or naps as their own blocks
- **Smart productivity tracking:**
  - **Productive time** = sum of all activity blocks minus inline breaks
  - **Breaks Lost** = inline breaks + separate break block durations combined
  - **Productivity bar** = productive time as a % of your total work day
- **Work day window** — set your personal start and end time (e.g. 06:00–22:00); used to calculate accurate percentages in your Excel report
- **Auto-save** — everything saves to your browser automatically; come back tomorrow and it is all there

### 📊 Weekly Report Tab — Reflect & Improve

- **Upload your daily Excel files** (one per day, up to 7) — the app reads them and builds your weekly report automatically
- **Weekly performance chart** — one bar chart showing all 7 days side by side: productive % vs breaks lost %
- **Download chart as PNG** — save or share your weekly performance visually
- **Download Word report (.docx)** — a clean summary table (each day × productive mins, break mins, %) plus a written paragraph covering best day, worst day, average productivity, and total break time lost

### 📥 Excel Download — End of Day

Each day's download includes:

- Full schedule: start time, end time, duration, activity name, note, category
- Inline Break Mins and Net Productive Mins per block
- Separate break blocks clearly marked as non-productive
- Summary table showing minutes worked per category
- **Percentage calculations** based on your personal work day window:
  - Productive % = productive mins ÷ total work day mins × 100
  - Breaks % = break mins ÷ total work day mins × 100
  - Unaccounted % = remaining time ÷ total work day mins × 100

---

## 🔒 Privacy First

**Your data never leaves your device.**

Everything is stored in your browser's localStorage — no server, no database, no account required. When you close the tab, your data stays on your machine. When someone else opens the same public link, they start with a completely blank slate. This is not a limitation — it is a feature. Your schedule is yours and yours alone.

---

## 🚀 Getting Started

### Option 1 — Use it instantly (no setup needed)

1. Download `daily_schedule_planner.html` : https://vocal-pastelito-c7fb7a.netlify.app/
2. Open it in any modern browser (Chrome recommended)
3. Start planning

### Option 2 — Host it publicly for free in 30 seconds

1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop `daily_schedule_planner.html` onto the page
3. Get a free public link instantly — share it with anyone

### Option 3 — GitHub Pages

1. Fork this repo
2. Go to **Settings → Pages → select `main` branch**
3. Your planner is live at `https://yourusername.github.io/daily-schedule-planner`

---

## 📖 How to Use

### Day setup
1. Enter your **Day Start** and **Day End** time at the top (e.g. 06:00 → 22:00)
2. Rename the activity cards to match your activities — click any label to edit it
3. Add or delete cards using **＋ add card** or the **−** button on each card

### Building your schedule
1. Click any time box, type a new time, and press Enter to confirm
2. Click the activity name to rename it, or pick from the category dropdown to auto-fill
3. Use **＋** to insert a block below and **−** to delete one
4. For interruptions during an activity (e.g. a call during study time), click **+ break** inside that block and enter the time range and reason — the net productive time updates automatically
5. For standalone break periods (lunch, going out), add a new block and assign it the **Break** category

### End of day
1. Click **Download Excel (.xlsx)** to save the day's full data
2. Store the file — you will upload it to the Weekly Report tab later

### Weekly report
1. Switch to the **Weekly Report** tab
2. Upload your saved daily Excel files (drag and drop or browse)
3. Your weekly performance chart appears instantly
4. Download the **Word report** for a written summary or the **PNG chart** to share

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| UI | Vanilla HTML, CSS, JavaScript — zero frameworks |
| Data storage | Browser localStorage (no backend needed) |
| Excel export | [SheetJS (xlsx)](https://sheetjs.com/) |
| Weekly chart | [Chart.js](https://www.chartjs.org/) |
| Word export | [docx.js](https://docx.js.org/) |
| Hosting | Any static host — Netlify, GitHub Pages, Vercel (all free) |

---

## 📁 Project Structure

```
daily-schedule-planner/
│
├── daily_schedule_planner.html   # The entire app — one single file
└── README.md                     # This file
```

The entire application is **one HTML file**. No build step, no dependencies to install, no Node.js, no npm. Just open and use.

---

## 🤝 Contributing

Contributions are welcome. If you have an idea or find a bug:

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-idea`
3. Make your changes in `daily_schedule_planner.html`
4. Open a pull request with a clear description of what you changed and why

Ideas for future contributions:
- Mobile-optimized layout
- Light/dark theme toggle
- Daily templates (save a layout and reuse it)
- Streak tracking across consecutive productive days
- Pomodoro timer integration
- Google Sheets export

---

## 📄 License

MIT License — free to use, modify, and distribute. If this tool helps you, a ⭐ on the repo goes a long way.

---

## 💬 A Note from the Creator

This tool was built out of a personal need — to stop *planning* productivity and start *measuring* it honestly. Most planners help you write down what you intend to do. This one helps you face what you actually did, understand where the time went, and improve one day at a time.

If it helps even one person get more out of their day, it was worth building.

---

<div align="center">

**Made with ☕ and a belief that awareness is the first step to improvement.**

[⭐ Star this repo](.) &nbsp;·&nbsp; [🐛 Report a bug](../../issues) &nbsp;·&nbsp; [💡 Request a feature](../../issues)

</div>
