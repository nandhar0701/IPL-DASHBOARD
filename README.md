# 🏟️ IPL Stats Dashboard

An interactive, single-file dashboard covering all-time IPL batting and bowling
records, franchise trophies, fan following, and a "GOAT Corner" — built with
plain HTML, CSS, and JavaScript. No frameworks, no build step, no dependencies.

🔗 https://nandhar0701.github.io/IPL-DASHBOARD/

## ✨ Features

- **👑 GOAT Corner** — top 3 all-time picks for Batting, Bowling, and Fielding
  within IPL history, each with the reasoning behind the ranking
- **🏏 Batting Records** — highest runs, most sixes, most fours, highest
  career strike rate
- **🎳 Bowling Records** — highest wickets, best bowling figures in a single
  match
- **🏆 Teams & Trophies** — all 10 current franchises with real logos, trophy
  cabinet, fan-following ranking, and all-time win record
- **Tap any player** to open a full profile — real photo, team badge, and
  every stat category they appear in, aggregated in one view
- Real player photos and team logos embedded directly in the file — works
  fully offline, nothing to download separately

## 🎨 Design

Stadium-themed dark UI — floodlight glow effects, pitch-stripe background
texture, scoreboard-style amber accents, and dashed "boundary rope" dividers
between leaderboard rows.

## 🛠️ Tech Stack

- **HTML/CSS/JavaScript** — no frameworks, no build tools
- All data and images are embedded directly in `index.html` as inline
  JSON and base64-encoded images, so the whole dashboard is a single
  portable file

## 📊 Data Sources

Compiled from ESPNcricinfo, IPL.com official records, Wikipedia, and cricket
news sources, cross-checked across multiple outlets. Current as of the
**2026 IPL season**.

**Honest caveats:**
- Fan-following numbers are an *estimate* (aggregated social media
  followers from third-party trackers), not an official IPL statistic
- GOAT Corner rankings are inherently subjective — they reflect commonly
  cited IPL-specific consensus, not a formal ranking system. MS Dhoni's
  #3 batting spot in particular is argued on **captaincy impact** (5
  titles, most successful leadership record) rather than raw batting
  numbers

## 🚀 Setup

Want to run this yourself or fork it?

1. Clone or download this repo
2. Open `index.html` directly in any browser — that's it, no server needed

### Enabling GitHub Pages (to get a live link)

1. Go to your repo's **Settings → Pages**
2. Under "Build and deployment", set **Source** to `Deploy from a branch`
3. Pick the `main` branch and `/ (root)` folder, then **Save**
4. Your dashboard will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`
   within a minute or two

## 📄 License / Attribution

This is a personal/academic project. Player photos and team logos were
sourced for personal, non-commercial use. All statistics are compiled from
public cricket data sources cited above.

---

*Built as a data analyst portfolio project.*
