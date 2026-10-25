# 🦕 Dino Times Tables

## Overview

Dino Times Tables is a free, browser-based multiplication and division practice game for primary school children. Players join Rex the T-Rex on a quest to master their times tables through a range of fast-paced game modes, boss battles, a shop full of dino skins and backgrounds to unlock, and eggs that hatch into collectable dinosaurs.

No installation, no accounts, no ads — just open the HTML file in a browser and play.

## Features

- 4 game modes: Practise, Raptor Rush, Storm Circle, and Dino Battle (boss fights)
- Choose any combination of times tables from 2× to 12×
- Multiplication, division, or a mix of both — your choice, in every mode
- Dino Bucks currency — earned by playing, spent in the shop
- Shop with unlockable Rex skins and animated backgrounds
- Eggs that hatch into 18 collectable dinosaurs, from Common to Legendary
- Badges and achievements to collect
- Per-fact tracking so the game knows which answers you find tricky — separately for × and ÷
- Daily streak counter and table mastery progress bars
- Sound effects with a mute toggle
- Save codes so progress can be backed up or moved to another device
- Fully self-contained — one HTML file, no internet connection required after download

## How to play

1. Open dino-times-tables.html in any modern web browser, or visit the live version at https://mtomtom.github.io/dino-timestables/
2. Enter your name when Rex asks — this is stored locally in your browser only.
3. Pick a game mode from the home screen.
4. Choose ×, ÷ or a bit of both, then pick which tables you want to practise.
5. Type your answers into the box and press **Enter** (or tap **Submit** on mobile).
6. Earn Dino Bucks for correct answers and spend them in the shop.

Rex gives feedback after each answer and bounces when you get one right. A hint button appears if you're stuck.

## Game modes

Every mode except Dino Battle lets you choose the **operation** first:

- **× times tables** — the classic `7 × 8` questions.
- **÷ division** — the same facts the other way round. Pick the 7× table and you get questions like `56 ÷ 7`, so the table you choose is always the number you divide by. Answers are always whole numbers between 2 and 12.
- **×÷ a bit of both** — questions alternate randomly between the two.

If you're stuck on a division question, Rex's hint shows the link back to the times table you already know: *"÷ is × backwards. What times 7 makes 56?"*

**Practise** — Answer questions at your own pace with no time pressure. Great for learning new tables.

**Raptor Rush** — Answer as many questions as possible before the timer runs out. Your score is the number of correct answers.

**Storm Circle** — A survival mode where the "storm" closes in. Each wrong answer or slow response shrinks the safe zone. Aim for the highest score before the storm gets you.

**Dino Battle** — Face off against a boss dinosaur. The boss attacks every few seconds if you don't answer in time. Deplete the boss's health bar by answering correctly before it defeats Rex. There are 5 bosses to beat, each unlocking the next. The last two bosses, **Spino Supreme** and **The Mega-Hybrid**, mix division questions in with the times tables.

## Eggs and the Nest

Every **25 correct answers**, in any mode, earns an egg. The egg meter on the home screen shows how close you are to the next one.

Eggs hatch in the **🥚 Nest** (on the home screen, or as a tab in the Shop) into one of 18 dinosaurs that cannot be bought at any price:

| Rarity | Chance per egg | How many |
|---|---|---|
| Common | 58% | 6 |
| Rare | 28% | 5 |
| Epic | 11% | 4 |
| Legendary | 3% | 3 |

Two rules keep it from being frustrating for a child:

- **No duplicates.** Every egg hatches into a dinosaur you don't already have, so an egg is never wasted. The full set takes 18 eggs — about 450 correct answers.
- **Pity timer.** Go 12 eggs without an Epic or Legendary and the next one is guaranteed to be one.

Once the whole set is collected, further eggs pay out 60 Dino Bucks instead. Hatched dinosaurs are equipped from the Nest, exactly like shop skins.

## Saving progress

Progress (name, Dino Bucks, skins, hatched dinosaurs, eggs, badges, stats, and streaks) is stored in your browser's `localStorage`. It stays between sessions on the same browser and device but will be lost if you clear your browser data.

**To back up or transfer progress:**

1. Go to ⚙️ **Settings** from the home screen.
2. Copy the **Save Code** (a `DINO1:…` string).
3. Paste it somewhere safe — a note, an email to yourself, etc.
4. On a new device or browser, open Settings and paste the code into the **Load a save code** box.

No data is ever sent over the internet. Everything stays on-device.

**Technical notes:**

- Single file, no build step, no dependencies.
- Save data is forwards and backwards compatible: save codes made before division and eggs existed load into the current version with no loss, and multiplication progress is stored separately from division progress, so neither affects the other.
- No external scripts or fonts — the game works fully offline once loaded.
- HTTPS is provided automatically by GitHub Pages.
- No server-side code, no database, no user data collected.
- Tested in Chrome, Firefox, Safari, and Edge (desktop and mobile).

## Licence

Free to use, share, and adapt for personal or classroom use. If you make improvements, sharing them back is appreciated but not required.

All graphics are generated in-browser as SVG — no third-party artwork or assets are included.
