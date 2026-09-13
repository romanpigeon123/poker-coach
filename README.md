# Poker Coach — Pass 8

Mobile-first poker training PWA for a GTO-first MTT study plan.

## Pass 8
- **BTN River Engine:** completes the BTN postflop sequence from flop → turn → river.
- River range reconstruction, fixed river hand values, hand-vs-range equity, polarized betting, value/bluff composition, Alpha/MDF, bluff-catching, blockers, sizing, traps and SPR.
- Source-backed river math examples are labelled as examples rather than universal frequencies.
- **BB Complete-Hand Engine:** builds on the existing supplied 100bb BB-vs-RFI charts and trains BB vs BTN/CO across preflop context, flop, turn and river.
- GTO only: no population exploits and no invented solver frequencies.
- Progress is saved locally; each module can be reset independently.

## Source
The training framework is grounded in the user's supplied copy of Michael Acevedo's *Modern Poker Theory: Building an unbeatable strategy based on GTO principles*. The app uses original paraphrases and authored drills rather than reproducing the book's text.

## Deploy
Replace the existing GitHub Pages files in the same repository. Keep `manifest.json`, icons and `sw.js` together with `index.html`.
