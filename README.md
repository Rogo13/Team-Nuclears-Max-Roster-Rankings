# Team Nuclear's Max Battle Analyzer

A single-page tool for ranking your Pokémon GO roster against Max Battle bosses. Pick a boss, add your Pokémon with their level and IVs, and get ranked recommendations across four roles.

**[Live version →](#)** https://rogo13.github.io/Team-Nuclears-Max-Roster-Rankings/<!-- add your GitHub Pages link once it's live -->

## What it does

- Ranks your roster against a selected boss across four roles:
  - ⚔️ **Attacker** — highest damage output
  - 🔵 **Shielder** — best at generating Max Guard shields
  - 🛡️ **Tank** — best at absorbing damage
  - 💚 **Healer** — best Max Spirit healing output
- Accounts for level, IVs, fast move choice, weather boost, and Dynamax Cannon boost
- Supports D-Max, G-Max, and the three special-case legendaries (Zacian, Zamazenta, Eternatus) that use fixed max moves instead
- Export/import your roster as a JSON file
- Shows the underlying scoring formulas for each role

## Roster database

- 155 catchable Pokémon
- 40 boss-eligible Pokémon (G-Max capable or Legendary/Mythical)
- 87 fast moves, 143 charged moves

## Running it

No build step, no dependencies. Download `index.html` and open it in a browser, or visit the live link above.

## Tech

Single HTML file — vanilla JS, inline CSS, no frameworks or external calls.

## Status

Actively maintained and updated as new Pokémon and moves are added.
