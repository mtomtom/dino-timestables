# 🦕 Dino Times Tables

Oct 8, 2026 · @Melissa Bayes

## Overview

Dino Times Tables is a free, browser-based multiplication practice game for primary school children. Players join Rex the T-Rex on a quest to master their times tables through a range of fast-paced game modes, boss battles, and a shop full of dino skins and backgrounds to unlock.

No installation, no accounts, no ads — just open the HTML file in a browser and play.

## Features

- 4 game modes: Practise, Raptor Rush, Storm Circle, and Dino Battle (boss fights)
- Choose any combination of times tables from 1× to 12×
- Dino Bucks currency — earned by playing, spent in the shop
- Shop with unlockable Rex skins and animated backgrounds
- Badges and achievements to collect
- Per-fact tracking so the game knows which answers you find tricky
- Daily streak counter and table mastery progress bars
- Sound effects with a mute toggle
- Save codes so progress can be backed up or moved to another device
- Fully self-contained — one HTML file, no internet connection required after download

## How to play

1. Open `dino-times-tables.html` in any modern web browser.
2. Enter your name when Rex asks — this is stored locally in your browser only.
3. Pick a game mode from the home screen.
4. Select which times tables you want to practise.
5. Type your answers into the box and press **Enter** (or tap **Submit** on mobile).
6. Earn Dino Bucks for correct answers and spend them in the shop.

Rex gives feedback after each answer and bounces when you get one right. A hint button appears if you're stuck.

## Game modes

**Practise** — Answer questions at your own pace with no time pressure. Great for learning new tables.

**Raptor Rush** — Answer as many questions as possible before the timer runs out. Your score is the number of correct answers.

**Storm Circle** — A survival mode where the "storm" closes in. Each wrong answer or slow response shrinks the safe zone. Aim for the highest score before the storm gets you.

**Dino Battle** — Face off against a boss dinosaur. The boss attacks every few seconds if you don't answer in time. Deplete the boss's health bar by answering correctly before it defeats Rex. There are 5 bosses to beat, each unlocking the next.

## Saving progress

Progress (name, Dino Bucks, skins, badges, stats, and streaks) is stored in your browser's `localStorage`. It stays between sessions on the same browser and device but will be lost if you clear your browser data.

**To back up or transfer progress:**

1. Go to ⚙️ **Settings** from the home screen.
2. Copy the **Save Code** (a `DINO1:…` string).
3. Paste it somewhere safe — a note, an email to yourself, etc.
4. On a new device or browser, open Settings and paste the code into the **Load a save code** box.

No data is ever sent over the internet. Everything stays on-device.

## Hosting on GitHub Pages

1. Create a public GitHub repository.
2. Add `dino-times-tables.html` to the repository root. Optionally rename it to `index.html` so your Pages URL opens the game directly.
3. Go to **Settings → Pages** in your repository and set the source to the `main` branch, root folder.
4. GitHub will provide a URL in the format `https://yourusername.github.io/your-repo/`.
5. Share that link — it works on any device with a modern browser.

**Technical notes:**

- Single file, no build step, no dependencies.
- No external scripts or fonts — the game works fully offline once loaded.
- HTTPS is provided automatically by GitHub Pages.
- No server-side code, no database, no user data collected.
- Tested in Chrome, Firefox, Safari, and Edge (desktop and mobile).

## Licence

Free to use, share, and adapt for personal or classroom use. If you make improvements, sharing them back is appreciated but not required.

All graphics are generated in-browser as SVG — no third-party artwork or assets are included.
