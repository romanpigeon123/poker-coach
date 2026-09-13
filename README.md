# Poker Coach — Pass 9

Simplified mobile PWA training architecture.

- Only two tabs: **Drills** and **Progress**.
- Eight progressive 50-spot lessons: BTN Preflop/Flop/Turn/River and BB Preflop/Flop/Turn/River.
- Every street lesson shows the earlier streets first so decisions are learned in context.
- Lessons are always accessible; completion is never locked.
- Existing `pc_pwa_v8` localStorage is preserved for continuity.
- BB preflop spots use the supplied 100bb BB-vs-RFI chart data.
- Postflop spots are labelled GTO-principle coaching spots rather than invented solver frequencies.
