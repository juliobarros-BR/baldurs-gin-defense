# Presenter Script — The Gin Defense of Wood Science Village

A cue sheet for running the live show: what to click, what to say, roughly
when. The actual on-screen wording lives in `content.md` — this file is about
pacing and stage directions, not exact copy.

**Everything advances via on-screen buttons.** No keyboard shortcuts to
remember or explain to anyone. (One hidden easter egg only you know about:
pressing `5` at any point pops up a full-screen "GIN" card, in case you ever
want a random joke beat — entirely optional, never required.)

## Before you start
- Open `index.html` full-screen in a browser on the machine wired to the projector.
- Have the physical puzzle ready near whoever is playing Falkorc for Trial III.
- Know who's playing Ingo, Falkorc, and Jonas for the OpenBIS round (Trial I) —
  they'll need their own device/tab open to your actual OpenBIS instance.

## Prologue (~2 min)
1. **Title** — click Begin.
2. **An Evening at Jonas' Gin Emporium** (bar.png) — narrate the community, tease "two faces deserve introduction."
3. **The Alchemist and the Sage** — Jonas/Elli and Ingo/Druidingo, side by side.
4. **The Rusty Mug** (FalkBar.png) — Falkorc's bar, once loud, now emptying out.
5. **Falkorc, Tavern Legend** — his portrait and intro.
6. **Falkorc Proposes a Battle** (battle.png) — the challenge is on: winner keeps both bars.

## Trial I — The Protocol Trials (~3–5 min, depends on your OpenBIS pace)
7. **Brief** — read the itemized OpenBIS steps aloud; call out the seniority
   order (Ingo, then Falkorc, then Elli).
   - **Pause here and actually run the OpenBIS exercise live**, outside this
     app, with your three contenders. Come back when they're all done.
8. **Name the Finalists** — Falkorc and Elli are pre-selected (that's the
   intended outcome). Click Confirm, or reshuffle live if you genuinely want
   a different pair — exactly two must be selected either way.

## Trial II — Naming the Gin (~3–4 min)
9. **Brief** — read the "someone got a little too tipsy and broke the naming
   widgets" setup out loud. This is the audience's cue that something's about
   to go visibly wrong.
10. **The Game** — Elli plays first: 3 rounds, controls behave normally
    (drag the sliders, try the dropdown, herd the owlbear into the green
    ward, click Lock Reading). Then Falkorc: same game, but his sliders move
    backwards and his dropdown opens upward — let the audience notice before
    you say anything. After his 3rd round the app auto-narrates that it's
    going badly, then a "bug found, fixing..." beat plays on its own into a
    bonus round that always lands him on the "GIN" punchline. You don't need
    to do anything during that sequence except let it play and read the beats
    aloud if you want extra drama.
11. **Bottled for the Village** — both results shown as bottle labels on a shelf.

## Trial III — The Puzzle of Tastes (~1–2 min)
12. **Brief** — read the one-minute puzzle setup.
13. **The Clock** — click "Start the Clock" the moment your Falkorc actor
    starts the physical puzzle. Two outcomes:
    - They finish within 60s → click **"Falkorc Solves It!"** → the app jumps
      to **The Village Rebels** (a twist beat), then a button takes you to the finale.
    - Time runs out first → the app jumps **straight to the finale** on its own,
      nothing to click.

## Epilogue
14. **Finale** (celebration.png) — the toast. Same slide either way Trial III went.

---

## Editing the show later
- **Slide text** (headings, body copy, lists): edit `content.md`, then run
  `python3 build.py` from this folder, then reload `index.html` in the browser.
- **Game internals** (flavor-name pools, loading lines, score-to-rarity
  labels): edit directly in `index.html` — search for `TIER0`, `LOADING`,
  `scoreLabel`.
- Timings above are rough estimates from a read-through, not a timed
  rehearsal — adjust once you've actually run it once live.
