# Story Content — The Gin Defense of Wood Science Village

Edit the text below, then run `python3 build.py` from this folder to compile it
into `index.html`. Re-run the build every time you change this file — the app
itself doesn't read this file directly (it runs from a single self-contained
HTML file so it keeps working offline, with no server).

**Format rules the build script relies on — keep them exact:**
- `## scene_id` starts a new scene. Don't rename these (the app looks them up
  by id) — only edit the text under `**Field:**` labels.
- `**Field:** value` — everything after the colon, up to the next `**Field:**`
  or `##` heading, is that field's content. Multiple lines are fine.
- `**List:**` starts a bullet list — one item per `- ` line, until the next
  field or heading.
- Blank lines inside a field's text become a paragraph break (shown as space).

**What's NOT in this file:** the widget-game's flavor-name pools, loading
messages, and score labels live directly in `index.html` (search for `TIER0`,
`LOADING`, etc.) — they're long lookup tables rather than one-off slide copy,
so editing them in the file itself is easier than round-tripping through here.

---

## title

**Eyebrow:** An Alternative Trial, in Three Acts
**Heading:** The Gin Defense of Wood Science Village
**Body:** For years, one still has ruled the taverns of Wood Science Village. Tonight, that reign is challenged.
**Button:** Begin

## bar_intro

**Eyebrow:** I.
**Heading:** An Evening at Jonas' Gin Emporium
**Body:** Every night, the village gathers here — botanists, brewers, and the occasional wandering bard — for gin poured with a scientist's precision and a poet's excess. Two faces in this crowd deserve a proper introduction.
**Button:** Meet Them

## defenders

**Eyebrow:** II.
**Heading:** The Alchemist and the Sage
**Portrait1Name:** Elli
**Portrait1Title:** Gin Alchemist
**Portrait1Body:** Jonas — known behind this bar as Elli — has spent years perfecting the old ways of the still. "Botanicals are my weapons."
**Portrait2Name:** Druidingo
**Portrait2Title:** Support
**Portrait2Body:** Ingo, keeper of the wild botanicals, sworn to see the craft endure. "More botanicals! More friends!"
**Button:** Continue

## falkbar_intro

**Eyebrow:** III.
**Heading:** The Rusty Mug
**Body:** Once, this was the loudest tavern in the village — ale, spirits, and stories for every soul in Wood Science Village. Lately its tables sit a little emptier each night, as the crowds drift toward the warm lights of Jonas' Gin Emporium across the square.
**Button:** Continue

## falkorc_intro

**Eyebrow:** IV.
**Heading:** Falkorc, Tavern Legend
**Portrait1Name:** Falkorc
**Portrait1Title:** Tavern Legend
**Portrait1Body:** Famed for his cocktail nights and acclaimed across the village — "Good drinks bring people together!" — Falkorc has watched, night by night, as gin quietly wins over his public.
**Button:** Continue

## battle_proposal

**Eyebrow:** V.
**Heading:** Falkorc Proposes a Battle
**Body:** Enough watching. Falkorc marches into the Gin Emporium and slams a challenge on the bar: one battle, fair and public, for the thirsty inhabitants of Wood Science Village. Whoever makes the better gin keeps <b>both</b> bars.
**Button:** Let the Trials Begin

## act1_brief

**Eyebrow:** Trial I
**Heading:** The Protocol Trials
**Body:** Before a gin may be called a gin, its making must be written so that any hand could repeat it. Each contender must enter their craft into the record:
**List:**
- Enter your OpenBIS, and open "The Gin Making Space"
- Enter the following 3 ingredients in the "Ingredients" Project (add your initials to the ingredient you add): Grain Spirit, Orange Peel, Coriander Seeds
- Connect your respective protocol to the objects created
- Create a fancy name for your gin and connect the required protocol and ingredients
**OrderNote:** Contenders enter in order of seniority: <b>Druidingo</b>, then <b>Falkorc</b>, then <b>Elli</b>. Only two will continue.
**Button:** Return — Name the Finalists

## act1_finalists

**Eyebrow:** The Ledger Has Spoken
**Heading:** Name the Finalists
**Body:** Of the three who entered their craft into the record, only two may carry the trial forward. Click to crown exactly two.
**Button:** Confirm Finalists

## act2_brief

**Eyebrow:** Trial II
**Heading:** Naming the Gin
**Body:** Everyone in the village knows a gin's tasting name carries more than flavor — it carries feeling, memory, longing, the whole unreasonable weight of a good evening. And there is no finer way to choose such a name than through Widgets.
<br><br>Unfortunately, someone got a little too tipsy last night and thoroughly scrambled the naming widgets' code. The dropdowns misbehave. The sliders lie. Whoever handles a broken widget best, wins the name.
**Button:** Let the Naming Begin

## act3_brief

**Eyebrow:** Trial III
**Heading:** The Puzzle of Tastes
**Body:** By now, the village already leans toward Jonas' gin — you can hear it in the square. But Falkorc gets one last chance to win the whole bar back: a single puzzle, its faces bearing not colors but the sigils of science itself, matched face by face. One minute on the clock.
<br><br>If the puzzle falls into place before time runs out, Falkorc keeps his bar and wins Jonas'. If not, the village has already decided.
**Button:** Start the Clock

## act3_duel

**Eyebrow:** Trial III — In Progress
**Heading:** The Puzzle of Tastes
**Button:** Start the Clock

## rebellion

**Eyebrow:** An Unexpected Turn
**Heading:** The Village Rebels
**Body:** The puzzle clicks into place — Falkorc's, fair and square. But before the announcement is even finished, the square erupts. Tankards slam onto tables. A chant rises from the back of the crowd and does not stop: <i>"Jonas! Jonas! Jonas!"</i> Whatever the rules said, Wood Science Village has already made up its mind.
**Button:** See How the Night Ends

## finale

**Eyebrow:** Epilogue
**Heading:** Jonas' Gin — Different Minds, Same Spirit(s)
**Body:** By nightfall the whole square is toasting — Ingo, Elli, even Falkorc himself, glass raised beside the owlbear statue. Two bars, one crowd, one very loud verdict.
**Body2:** <b>In every world that matters: Jonas Maas has successfully defended his thesis.</b>
**Closing:** — The End —
