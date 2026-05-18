# Monster Maker's Convention — Lesson 35

A gamified, single-page web companion to **Honors Language Arts 3, Lesson 35: Monster Maker's Convention — Peer Reviews** for a 3rd grade class.

## What it does
Students earn XP and badges by completing 5 quests built from the lesson:

1. **Read the Scroll** — log Stars / Pushes / Questions from teacher feedback (+10 XP)
2. **Spell Workshop** — learn Compliment vs. Suggestion sentence starters, then sort 6 example cards into bins (+15 XP)
3. **Revise the Prototype** — interactive revision checklist (+20 XP)
4. **Battle Arena** — pick Odysseus's move vs. the Labyrinthian Hydra, see a response, vote (+15 XP)
5. **Word Wizard** — flip vocab flashcards (cower, pithicus, raptor, rex, odon) and forge new monster names from word roots (+15 XP)

Progress, XP, and badges are saved in the browser via `localStorage`. Each student keeps their own progress on their device. A **Reset** button clears it.

## Run locally
Just open `index.html` in a browser. No build step.

## Deploy to GitHub Pages
```bash
cd C:\Users\maram\Dev\monster-makers-convention
git init
git add .
git commit -m "Lesson 35: gamified peer review page"
git branch -M main
git remote add origin https://github.com/Hyphysaurus/monster-makers-convention.git
git push -u origin main
```
Then on GitHub: **Settings → Pages → Branch: main / (root) → Save**. Site goes live at `https://hyphysaurus.github.io/monster-makers-convention/` in a minute or two.

## Customize
- All content is in one file (`index.html`).
- Swap the sort-game examples in `SORT_CARDS`, the battle responses in `BATTLE_RESPONSES`, or the name-forge prefixes/roots in `PREFIX_MEANINGS` / `ROOT_MEANINGS`.
