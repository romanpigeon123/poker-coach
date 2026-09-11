# Poker Coach — Chunk 3

Mobile-first PWA for structured MTT poker training.

## Chunk 3
- Day 3: 50 mixed-strategy BB-vs-RFI preflop spots.
- Every spot is taken from a chart cell that contains at least two non-zero actions.
- Covers UTG, UTG+1, LJ, HJ, CO, BTN and SB.
- No hand/position pair repeats Chunk 1 or Chunk 2.
- Uses the seven supplied 100bb 8-max BB-vs-RFI charts as the reference source.
- Mixed Raise/Call/Fold cells are preserved and scored by reference frequency.
- The drill focuses on mixed cells so the player learns not to force binary decisions where the reference strategy is mixed.

## Drill and chart experience
- The current decision drill is the first thing shown on the Today screen.
- The reference range chart stays hidden until an action has been selected.
- After answering, the relevant chart opens below the feedback.
- Chart heading: **Big Blind Range Chart**.
- Chart selectors: **vs UTG RFI**, **vs UTG+1 RFI**, **vs LJ RFI**, **vs HJ RFI**, **vs CO RFI**, **vs BTN RFI**, **vs SB RFI**.
- Mixed cells remain visually split between Raise, Call and Fold.

## PWA
- `manifest.json` included.
- `sw.js` cache version bumped to v7.
- iPhone standalone metadata and icons included.
- Offline cache includes the core app assets.
- Local storage migrates existing progress into the v7 schema while retaining previous Chunk 1/2/3 data.

## GitHub Pages
Upload/replace the files in the repository root and allow GitHub Pages a few minutes to publish. Keep the same repository and URL so the existing iPhone Home Screen shortcut remains pointed at the app.
