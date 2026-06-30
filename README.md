# MobiGlas // SC Companion

An unofficial, Star Citizen–themed companion web app. Single HTML file, no build step, no dependencies. Runs anywhere — and is ready to host free on **GitHub Pages**.

![status](https://img.shields.io/badge/status-online-3ddc84) ![type](https://img.shields.io/badge/build-static%20site-22d3ee)

## Features

- **Trade Route Calculator** — enter live buy/sell prices; get units, profit/unit, total profit and aUEC/hour per route, with the best route highlighted.
- **Mining / Refining Calculator** — enter SCU mined and refined prices per ore; gross and net-after-refining totals.
- **Ship Comparison** — sortable table of cargo, crew, role, price and aUEC-per-SCU; editable, add your own ships.
- **Loadout / DPS Planner** — weapon damage × fire rate × mounts → sustained DPS and time-to-kill.
- **Run Log** — record runs; totals, best run and count update live and persist in your browser (localStorage).

Prices in Star Citizen change constantly, so this is an **input-driven calculator**, not a static price list. Pull current numbers from [UEX Corp](https://uexcorp.space/), [SC-Trade Tools](https://sc-trade.tools/) or [HubCitizen](https://hubcitizen.com/commodities).

## Run locally

Just open `index.html` in any browser. That's it.

## Deploy free to GitHub Pages

1. Create a new repo on GitHub, e.g. `sc-companion` (Public).
2. Upload `index.html` and `README.md` to the repo (drag-and-drop in the GitHub web UI, or use git — see below).
3. In the repo: **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Branch: `main`, folder: `/ (root)`. Save.
6. Wait ~1 minute. Your site goes live at:
   `https://YOUR-USERNAME.github.io/sc-companion/`

### Or via command line

```bash
cd sc-companion
git init
git add .
git commit -m "MobiGlas SC Companion"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/sc-companion.git
git push -u origin main
```

Then enable Pages as in steps 3–6 above.

## Notes

Unofficial fan project. Not affiliated with or endorsed by Cloud Imperium Games or Roberts Space Industries. Star Citizen is a trademark of CIG. Seed data reflects the ~4.x patch era and is approximate — always verify against live tools. o7
