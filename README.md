# ExperienceTracker

**A free, offline-first tool to organize your experiences for Portfolio, LinkedIn, and Resume — all in one place.**

No account. No subscription. No data sent anywhere. Everything stays in your browser.

🔗 **Live demo:** https://fangorr.github.io/experience-tracker/ (https://github.com)

---

## The Problem

Most people struggle with the same thing when building their portfolio or updating their LinkedIn:

- "What have I actually done in the past 2–3 years?"
- "Is this small project worth mentioning?"
- "How do I write the same experience differently for LinkedIn vs my resume?"

You end up either forgetting things, underselling yourself, or spending hours reformatting the same information for different platforms.

---

## What ExperienceTracker Does

ExperienceTracker is a single HTML file you can open in any browser. It gives you a structured way to:

1. **Dump everything first** — record every project, competition, event, freelance job, or activity without judging it
2. **Tag and prioritize** — mark each entry as Strong / Normal / Minor, and assign it to Portfolio, LinkedIn, Resume, or all three
3. **Generate ready-to-use output** — each tab formats your entries differently, optimized for that specific platform

---

## How It Works

### Step 1 — Add Entry

Fill in the details for each experience:

| Field | What to write |
|-------|--------------|
| **Title** | Name of the project, event, or role |
| **Year** | e.g. `2024` or `2023–2024` |
| **One-line summary** | What you did, in one clear sentence |
| **Details** | Your role, the context, measurable results |
| **Tools / Tech** | Software, languages, platforms used |
| **Role** | Your specific role e.g. Director, Developer |
| **Link** | URL to the project, video, or article |
| **Category** | Personal Project, Competition, Internship, etc. |
| **Importance** | ★ Strong / ◇ Normal / · Minor |
| **Include in** | Portfolio, LinkedIn, Resume (select multiple) |

### Step 2 — View & Filter

Switch between views in the left sidebar:

- **All Entries** — see everything, filter by importance or destination
- **Portfolio View** — formatted as project cards, ready to reference when building your portfolio
- **LinkedIn View** — formatted as bullet points, ready to copy into LinkedIn's Experience or Projects section
- **Resume View** — grouped by category, formatted as resume bullet points

### Step 3 — Export & Backup

Your data is saved in your browser's localStorage automatically. To keep a backup:

- **Export JSON** — save a `.json` file you can import back later
- **Export Text** — save a `.txt` file for reference or sharing
- **Import JSON** — load a previous backup, merges with existing data without duplicates

---

## Features

- **Zero dependencies** — one HTML file, works offline, no internet required after first load
- **Three output formats** — Portfolio, LinkedIn, Resume, each formatted differently
- **Import / Export** — back up your data as JSON, restore it anytime
- **Filter & search** — view only Strong entries, or only Portfolio-tagged items
- **Responsive** — works on desktop and mobile
- **Dark theme** — easy on the eyes for long sessions

---

## Who This Is For

- **Students** finishing university and preparing their first portfolio or LinkedIn
- **Fresh graduates** applying for jobs and struggling to remember what they've done
- **Freelancers** who work on many small projects and lose track of them
- **Anyone** who has ever said "I know I've done a lot, I just can't remember what"

---

## Getting Started

### Option A — Use it directly

Download `tracker.html` → open it in your browser → start adding entries.

No installation. No setup.

### Option B — Host it yourself (GitHub Pages)

1. Fork this repository
2. Go to Settings → Pages → Source: `main` branch
3. Your tracker will be live at `https://your-username.github.io/experience-tracker`

---

## Tips for Getting the Most Out of It

**Do a brain dump first.** On your first session, don't filter — just add everything you can remember from the past 2–3 years. Even small things. You can decide what to include later.

**Use the Importance field honestly.** Mark things as Strong only if you'd be proud to talk about them in an interview. It's okay if most things are Normal.

**Write the one-line summary as if explaining to a stranger.** Not "worked on a film" but "directed a 10-minute short film that won 2nd place at a national festival."

**Export weekly** if you're actively job hunting. LocalStorage can be cleared if you clear your browser data.

**Add results, not just actions.** "Edited videos" is weak. "Edited campus election videos that reached 12K views in 48 hours" is strong.

---

## Data & Privacy

All data is stored locally in your browser using `localStorage`. Nothing is sent to any server. Nothing is tracked. Clearing your browser data will delete your entries — export regularly to avoid losing your work.

---

## Built By

Built by [Vincent Kong](https://fangorr.github.io/vink-portfolio) — Filmmaker & Creative Technologist based in Malaysia.

Started as a personal tool to organize 3 years of university projects, competition entries, and freelance work before job hunting. Turned into something more useful, so here it is.

---

## License

MIT License — free to use, modify, and share.

---

*If this helped you, a star on the repo goes a long way. ⭐*
