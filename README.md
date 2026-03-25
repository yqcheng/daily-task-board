# 🗂 Daily Task Board

An AI-powered daily task board. Paste raw chaos — meeting notes, Notion dumps, brain dumps — and it organizes everything into a clean, interactive board.

## Features

- **AI parsing** — paste anything, Claude categorizes and deduplicates tasks automatically
- **Daily persistence** — board saves to localStorage, reopens where you left off
- **Carryover** — unfinished tasks from previous days carry forward automatically
- **Drag & drop** — drag tasks between categories, color follows automatically
- **Category management** — rename, recolor, delete categories; create new ones
- **Task management** — delete individual tasks; add more mid-day via AI
- **Filter pills** — click any category to zoom in
- **Celebrations** — particle burst per task, category glow + streak burst when a category is cleared, full-board 🎉 when everything's done
- **History** — view past days with completion stats
- **Auto-scroll while dragging** — page scrolls when you drag near top/bottom edge

## Setup

1. Download `index.html`
2. Open it in any browser (no server needed)
3. Get an [Anthropic API key](https://console.anthropic.com/settings/keys)
4. Paste your key into the app — it's saved to localStorage so you only enter it once

## Usage

1. Paste today's notes/tasks into the text area
2. Hit **ORGANIZE IT** — AI parses, deduplicates, and categorizes
3. Check off tasks as you go
4. Come back tomorrow — unfinished tasks carry over automatically

## Version History

### v1.0
- Initial release
- Full feature set: AI parsing, drag-and-drop, daily carryover, celebrations, history
