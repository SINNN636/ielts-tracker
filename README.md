# IELTS TRACKER

A personal IELTS study dashboard — 12-week plan, daily check-in, vocabulary book
(刘洪波《雅思词汇真经》22 章 3674 词), error notebook, mock test log, and analytics.

Everything runs in the browser. No backend, no tracking, no accounts.

## Features

- **Dashboard** — countdown to exam, streak, today's progress, skill heatmap, weekly
  trend charts.
- **Phase Plan** — three training phases (基础 / 强化 / 冲刺) mapped onto the
  12-week timeline, with goal lines per skill.
- **Daily Check-in** — log minutes spent on 8 training categories, capture the
  hardest problem of the day.
- **Vocabulary Book** — 22-chapter word list with three modes:
  - **Browse** (词组视图 / 单词列表) — read words, examples, mastery pills
  - **Search** — filter by word, meaning, example, or part of speech
  - **Typing** (跟打练习) — recall + spell words from your collection
- **Error Notebook** — log wrong answers by subject/section, track patterns
- **Mock Test** — record L/R/W/S scores after each full practice test
- **Analytics** — streak, completion, category distribution, score trends
- **Topic Library** — bubble-map index of all IELTS topics across 8 themes

## Quick start

Just open `index.html` in any modern browser. Or serve it locally:

```bash
python -m http.server 8080
# then visit http://localhost:8080
```

## Data

All data lives in your browser's `localStorage` under the key
`ielts-tracker-v1`. Nothing is sent to any server. Use **Settings → 数据管理**
to export, import, or wipe your data.

- **Export** — downloads a JSON file with every entry (days, vocab, errors, mocks)
- **Import** — restores a previously exported JSON
- **Clear all data** — wipes localStorage and reloads

## Deploying to GitHub Pages

1. Push the contents of this folder to a repo.
2. Settings → Pages → Branch: `main` / root.
3. Visit `https://<user>.github.io/<repo>/`.

That's it. No build step, no dependencies.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The full app (HTML + CSS + JS in one file, no build step) |
| `vocab-book.js` | 22-chapter IELTS vocabulary (刘洪波《雅思词汇真经》) |
| `README.md` | This file |

## Configuration

On first launch the dashboard shows a hint banner prompting you to fill in:

- **Exam date** — drives the countdown (`days to go`), phase progress, and heatmap layout
- **Target score** (Overall) — typically 6.5 / 7.0 / 7.5 / 8.0
- **Training items** — tick which daily training categories you want to track
  (each with a custom daily target)

All of these live under **设置** (Settings). Once you set the exam date, the
hero banner automatically swaps from a generic label to your actual date
(e.g. `2026.12.03 雅思机考`).

## Customizing the look

The two accent colors are CSS variables at the top of `index.html`:

```css
--bg-page  /* page background */
--accent   /* primary accent (used for buttons, charts, today) */
```

Change them once and the whole UI follows.

## Credits

- Vocabulary content: 刘洪波《雅思词汇真经》(22 chapters, 3674 words)
- Built with vanilla HTML/CSS/JS, [Chart.js](https://www.chartjs.org/) (CDN), and
  a lot of ☕.
