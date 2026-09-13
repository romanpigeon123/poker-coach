# Poker Coach — Simplified GTO Training Build

Mobile-first PWA for progressive MTT GTO training.

## Pass 9 architecture
- Two tabs only: Drills and Progress.
- All training lessons live under Drills.
- Each lesson has a short concept explanation followed by 50 drill spots.
- Lessons remain accessible at all times; no artificial day locks.
- Progressive hand context: flop lessons begin with preflop; turn lessons begin with preflop + flop; river lessons begin with the full hand history.
- BTN sequence: preflop, flop, turn, river.
- BB sequence: preflop defence, flop defence, turn, river.
- Existing BB-vs-RFI 50-spot foundation is retained and migrated into the new lesson system.
- GTO-only focus; no population/exploitative adjustments.
- Conceptual material follows the supplied copy of Michael Acevedo's Modern Poker Theory. Exact solver frequencies are not invented where the source does not provide them.

## Install
Upload all files to the existing GitHub Pages repository/root. Keep the same URL.
