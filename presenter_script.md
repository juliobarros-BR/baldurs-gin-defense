# Presenter Script — The Gin Defense of Wood Science Village

A cue sheet for running the live show: what to click, what to say, roughly
when. The actual on-screen wording lives in `content.md` — this file is about
pacing and stage directions, not exact copy.

**Navigation:** every scene has an on-screen Continue-style button — that's
what the audience sees you use. Arrow keys (Right = forward, Left = back)
also work anywhere as a presenter shortcut, for rehearsing or jumping past a
section without playing it out fully; Right jumps to the next major scene
(it doesn't try to track mid-game progress, so use it between sections, not
mid-round). One more hidden easter egg: pressing `5` at any point pops up a
joke "GIN" card — entirely optional, never required.

## Before you start
- Open `index.html` full-screen in a browser on the machine wired to the projector.
- Have the physical cube puzzle ready for Trial III, plus the six slogan
  images per side (J1-J6, F1-F6) visible or printed somewhere near it — the
  app just shows them as a grid, it doesn't control the physical cube.
- Know who's playing Ingo, Falkorc, and Jonas for the OpenBIS round (Trial I).

## Prologue (~2 min)
1. Title → Begin.
2. An Evening at Jonas' Gin Emporium (bar.png).
3. The Alchemist and the Sage — Jonas and Druidingo, side by side.
4. The Rusty Mug (FalkBar.png) — Falkorc's bar, emptying out.
5. Falkorc, Tavern Legend.
6. Falkorc Proposes a Battle (battle.png).

## Trial I — The Protocol Trials (~3–5 min)
7. Brief — read the OpenBIS steps aloud; call out the seniority order
   (Ingo, then Falkorc, then Jonas).
   - **Pause here and run the OpenBIS exercise live**, outside this app.
8. Name the Finalists — Falkorc and Jonas pre-selected; click Confirm (or
   reshuffle if it genuinely went differently — exactly two required).
9. **Grading the Protocols** (new) — drag a slider each for Jonas and
   Falkorc to whatever grade you judge their actual submissions earned.
   This number resurfaces on the final recap table.

## Trial II — Naming the Gin (~4–5 min)
10. Brief — mixing three gin tonics sets each contender's names.
11. **Mixing the Gin Tonic** — your real bottle/cup/gin-tonic art now: the
    cup sits fixed, the selected bottle actually lifts and tilts as you
    work the sliders, and both bottle and cup show a translucent tinted
    liquid level masked to the real artwork's silhouette (bottle drains as
    the cup fills). Three widgets: a dropdown to pick the ingredient, a
    vertical slider to raise the bottle (too low or too high and some of
    the pour is wasted — "SPILLING!"), and a horizontal slider to tilt it
    (controls pour rate once raised into the sweet spot). Switching the
    ingredient swaps in the other bottle and drops both sliders back to
    zero. Click Serve This Round whenever you're happy with the level, then
    an explicit button takes you to the next round (or to your three names
    on round 3 — nothing ever auto-advances).
    - **Jonas plays first**, 3 rounds, pour response is smooth and linear.
    - **Falkorc plays second**, 3 rounds — his bottle is just far more
      sensitive: small tilt changes swing the pour rate hard, and it keeps
      dribbling for a moment after you back off the tilt. Same widgets,
      same rules, just twitchy.
    - Each round produces one candidate name. After 3 rounds, **each player
      picks their favorite of their own 3 names** for the bottle label —
      but all three names for both contenders carry through to the final
      recap table, not just the chosen one.
12. Bottled for the Village — both chosen names shown as bottle labels.

## Trial III — The Puzzle of Tastes (~2–3 min)
13. Brief — the crazy-slogan/cube-matching setup.
14. **Matching the Slogans** — a 6-tile grid per side (the J1–J6 / F1–F6
    poster art). Click Start the Clock when the physical cube attempt
    begins (60s, just a visual timer — it doesn't stop anything on its
    own). As you watch the real cube, **click every slogan tile whose color
    the cube actually matched** for each side — toggle on/off freely, no
    fixed count required. Click Confirm & Continue when done.
15. **Wood Science Village Decides** (recap) — a table of both contenders'
    protocol grade, chosen flavor name, and collected slogans, side by
    side. Read it out, let the room react, then click whichever the crowd
    actually favored:
    - **Crowd Favors Jonas** → straight to the finale.
    - **Crowd Favors Falkorc** → a short twist scene (The Village Rebels)
      plays first, then a button takes you to the same finale.

## Epilogue
16. Finale (celebration.png) — the toast. Identical either way Trial III went.

---

## Editing the show later
- **Slide text**: edit `content.md`, then run `python3 build.py`, then
  reload `index.html`.
- **Game internals** (flavor-name pools, loading lines, score-to-rarity
  labels, pour sensitivity/target ranges): edit directly in `index.html` —
  search `TIER0`, `LOADING`, `scoreLabel`, `renderRound`.
- **Bottle art**: the bottle graphics on the "Bottled for the Village"
  screen are CSS-drawn glass shapes for now. If you add a `bottle.png` to
  `Characters/`, tell Claude and it'll wire it in as the real bottle image
  with the chosen name printed on the label.
- Timings above are estimates from a read-through, not a timed rehearsal —
  adjust once you've actually run it live once.
