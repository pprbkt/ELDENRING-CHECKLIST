# Elden Ring Checklist

Progress tracker for Elden Ring — quests, items, and bosses, with search, filtering, and completion tracking saved locally.

**Live:** https://eldenringchecklist.netlify.app/

## ▌Overview

A static web tracker for the Lands Between. Mark quests, items, and bosses as done as you go; progress bars show completion at a glance, and everything persists in the browser via localStorage — no account, no backend.

## ▌Tech Stack

```
Frontend   HTML • CSS • Vanilla JS
Storage    localStorage
```

## ▌Features

- Quest tracker — grouped by NPC, mark complete, track progress
- Item tracker — collectibles and their locations
- Boss tracker — track defeats across the map
- Search and NPC filter for quests
- Completion percentage via progress bars
- Local persistence — pick up where you left off

## ▌Project Structure

```
ELDENRING-CHECKLIST/
├── index.html              Dashboard
├── quests.html              Quest tracker
├── items.html                Item tracker
├── bosses.html                Boss tracker
├── quests_cleaned.json         Quest data
├── items_clean.json             Item data
├── bosses.json                   Boss data
├── script.js                      Shared logic
└── style.css
```

## ▌Run

```bash
git clone https://github.com/pprbkt/ELDENRING-CHECKLIST.git
cd ELDENRING-CHECKLIST

npx http-server
# or
python -m http.server
```

Open `http://localhost:8080/index.html`.

## ▌Usage

Navigate between Quests / Items / Bosses from the top bar. On the Quests page, search or filter by NPC, then check off quests as completed — saved automatically to localStorage.

## ▌Credits

- Quest, item, and boss data sourced from [Fextralife](https://eldenring.wiki.fextralife.com/)
- Inspired by the Excel-based [Elden Ring Progression Checklist mod](https://www.nexusmods.com/eldenring/mods/542) by Koal05
