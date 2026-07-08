# Board Game Score Tracker

A professional, mobile-first score tracking web app for board games, card games, tabletop games, dice games, and family game nights. The entire application is contained in a single HTML file and runs offline after it is opened.

## Usage

Open `board-game-score-tracker.html` in any modern browser. No installation, build step, network access, framework, CDN, or external dependency is required.

The main screen is optimized for fast table play: each player is shown as a large colored score card. Tap the left edge to subtract 1, tap the right edge to add 1, or tap the player name/score to open the focused scoring panel for larger custom adjustments. Use the visible `High wins` / `Low wins` scoring mode selector to control winner logic.

Your game state is saved automatically in the browser with Local Storage, including players, scores, settings, notes, timer state, presets, history, and archived games.

## Features

- Concise scoreboard layout with large stacked player cards, instant `-1` / `+1` card-edge controls, and a focused individual scoring panel from name/score taps.
- Fast score entry with quick values, compact custom amount entry, and configurable scoring buttons.
- 1 to 6 players with editable names, emoji avatars, unique colors, color picker, locking, drag-and-drop ordering, and compact six-player mode.
- Live winner/leader detection with explicit highest-score or lowest-score modes, tie display, leader glow, target score, end-game validation, and game-over celebration.
- Undo and redo for score changes, renames, player changes, deletes, score resets, and game resets.
- Score history with direct undo for individual score entries.
- Statistics for leader, last place, average score, high/low score, largest gain/loss, turns, points awarded, and points removed.
- Turn tracker with next/previous controls and optional auto-advance after scoring.
- Built-in game timer with start, pause, and reset.
- Dice roller for d4, d6, d8, d10, d12, and d20, plus coin flip and random player picker.
- Autosaved game notes, round support, game archive, lifetime player stats, and CSV export of completed games.
- Presets and quick templates for common game styles like family games, poker night, Catan, Dominion, and trick-taking games.
- Export/import game state as JSON, copy results summary, and copy/export archive data.
- Simple SVG score progression graph with no external libraries.
- Dark/light theme toggle, large-score mode, color-blind friendly palette, optional sound, optional haptics, fullscreen support, and Wake Lock support where available.
- Keyboard shortcuts: Arrow Up/Down to adjust selected player, Delete to reset selected player, Ctrl+Z undo, Ctrl+Y redo.

## Files

- `board-game-score-tracker.html` - the full self-contained application.
- `README.md` - this usage and feature guide.

## Privacy

All data stays in the browser on the device where the file is opened. The app does not call external APIs and does not send game data anywhere.
