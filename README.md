# Board Game Score Tracker

A professional, mobile-first score tracking web app for board games, card games, tabletop games, dice games, and family game nights. The entire application is contained in a single HTML file and runs offline after it is opened.

## Usage

Open `board-game-score-tracker.html` in any modern browser. No installation, build step, network access, framework, CDN, or external dependency is required.

Your game state is saved automatically in the browser with Local Storage, including players, scores, settings, notes, timer state, presets, history, and archived games.

## Features

- Fast score entry with `+1`, `+5`, `+10`, `-1`, `-5`, `-10`, large plus/minus buttons, custom keypad entry, and configurable scoring buttons.
- 1 to 6 players with editable names, emoji avatars, unique colors, color picker, locking, drag-and-drop ordering, and compact six-player mode.
- Live winner/leader detection with highest-score or lowest-score modes, tie display, leader glow, target score, and game-over celebration.
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
