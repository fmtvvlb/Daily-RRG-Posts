# Daily RRG Posts

Daily Instagram carousel publishing engine for **@redribbongroup** — a Canadian real estate intelligence brand, Calgary-led.

## What this repo does

Every morning at 6 AM Mountain Time, an automated task:

1. Pulls news from 12 verified sources (CREB, CREA, CMHC, Bank of Canada, Statistics Canada, and 7 others)
2. Verifies every data point against a fetched primary source — no fabrication, no estimation, no uncited claims
3. Writes a 7-slide carousel: hook → stake → setup → big data → breakdown → implication → action
4. Renders the slides as PNG images
5. Pushes today's content to this repo under `docs/YYYY-MM-DD/`
6. GitHub Pages serves the gallery at the public URL below

## Public URLs

- **Daily landing page (list of all days):** https://fmtvvlb.github.io/Daily-RRG-Posts/
- **Today's carousel gallery:** `https://fmtvvlb.github.io/Daily-RRG-Posts/YYYY-MM-DD/viewer.html`

Each day's gallery has three buttons:
- **Download as PDF** — single PDF with all 7 slides
- **Download all (ZIP)** — 7 individual PNGs in a zip
- **Copy caption** — full caption + 5 hashtags to clipboard, ready to paste into Instagram

## Folder structure

```
docs/
├── index.html              ← landing page listing all available days
├── YYYY-MM-DD/             ← one folder per day
│   ├── viewer.html         ← gallery + download + copy buttons
│   ├── slide_1.png         ← 1080×1350 carousel slide
│   ├── slide_2.png
│   ├── slide_3.png
│   ├── slide_4.png
│   ├── slide_5.png
│   ├── slide_6.png
│   └── slide_7.png
```

## Brand spec

- Primary red `#A2182C`, gold `#97662D`, teal `#AEC6C8`, charcoal `#1C1C1C`
- Headlines: Anton (ALL CAPS condensed)
- Body: Inter
- Voice: calm, mechanic-not-guru, Hemingway grade 3-4
- No em-dashes, no exclamations, no emojis, no questions in hook
- Every data point traces to a fetched source URL

## How posts get reviewed

Each morning:
- Cowork sends an iMessage with the day's gallery URL
- You open the URL on any device
- Tap "Download as PDF" or "Download all (ZIP)"
- Tap "Copy caption" → paste into Instagram
- Post at 8 AM MT

To share with Matt for review: forward the URL via iMessage.

---

Maintained by the Cowork daily content engine. Documentation in `/Users/vittopessanha/Documents/CLAUDE/RRM/Content_Engine/`.
