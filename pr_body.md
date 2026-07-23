## Adding Notion-style Home & Tasks to community plugins

### Plugin
- **Name**: Notion-style Home & Tasks
- **ID**: `notion-home-plugin`
- **Repo**: https://github.com/suxin17/notion-home-plugin
- **Author**: suxin17
- **Latest release**: [v0.8.0](https://github.com/suxin17/notion-home-plugin/releases/tag/0.8.0)

### Description
A Notion-style Home page (banner + avatar + two columns) with a task manager featuring Table/Board/Gantt views, a built-in timer, a work-time heatmap, a pie chart, a sub-task editor, **Pomodoro focus mode, daily streak, habit tracker**, quick-capture templates (`/exp`, `/paper`, `/task`), and bilingual UI (中文 / English).

### What's new in v0.8.0
- 🍅 Pomodoro / focus mode attached to each task row (4 visual states)
- 🔥 Daily streak with configurable threshold (default 60s/any timing counts)
- 🌱 Habit tracker (binary + count mode, 7-day week strip, per-habit streak)
- ⚙️ Pomodoro config UI (focus/short-break/long-break minutes, auto-start options)
- 📊 Today's pomodoro count on Home streak card

### Submission checklist
- [x] Plugin follows [Obsidian developer policies](https://docs.obsidian.md/Developer+policies)
- [x] Plugin is not a duplicate of an existing community plugin
- [x] Plugin has a valid `manifest.json` with required fields (`id`, `name`, `version`, `minAppVersion`, `author`)
- [x] Plugin has a LICENSE (MIT, © 2026 suxin17)
- [x] Plugin has a README in English and Chinese with installation & usage instructions
- [x] Plugin has at least one GitHub release (v0.8.0) with the required files attached (`main.js`, `manifest.json`, `styles.css`)
- [x] The release tag version matches `manifest.json` `version` exactly
- [x] Plugin does not show dynamic advertisements
- [x] Plugin does not use the `requestUrl` API on mobile in a way that violates policy
- [x] Plugin is open source

### Testing
Tested on Windows 11 with Obsidian v1.4+. All three views (Table / Board / Timeline), the timer, the heatmap, the pie chart, sub-task editor, quick-capture templates, Pomodoro focus mode, streak card, and habit tracker are working as expected.

Thanks for the review! 🙏
