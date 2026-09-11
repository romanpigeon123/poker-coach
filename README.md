# Poker Coach — Chunk 3

Mobile-first PWA for structured MTT poker training.

## Chunk 3
- Day 3: 50 mixed-strategy BB-vs-RFI preflop spots.
- Every spot is taken from a chart cell that contains at least two non-zero actions.
- Covers UTG, UTG+1, LJ, HJ, CO, BTN and SB.
- No hand/position pair repeats Chunk 1 or Chunk 2.
- Uses the seven user-supplied 100bb 8-max BB-vs-RFI charts as the reference source.
- Mixed Raise/Call/Fold cells are preserved and scored by reference frequency.
- The drill intentionally focuses on mixed cells so the player learns not to force binary decisions where the reference strategy is mixed.

## PWA
- `manifest.json` included.
- `sw.js` cache version bumped to v6.
- iPhone standalone metadata and icons included.
- Offline cache includes the core app assets.
- Local storage migrates existing Chunk 1/2 progress into the v6 schema.

## Accuracy note
The supplied range screenshots are the reference source for these drills. Aggregate range percentages are retained exactly as shown in the screenshots. Because the screenshots do not expose numerical frequencies for every individual split cell, those individual mixes are represented in 5% increments based on the visible colour proportions rather than being presented as falsely exact solver exports.

Chunk 3 contains only cells with at least two non-zero actions. Each encoded cell sums to 100% and is checked before release.

## GitHub Pages
Upload/replace the files in the repository root and allow GitHub Pages a few minutes to publish. Keep the same repository and URL so the existing iPhone Home Screen shortcut remains pointed at the app.
