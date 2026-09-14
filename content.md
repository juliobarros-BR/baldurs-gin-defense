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
**Portrait1Name:** Jonas
**Portrait1Title:** Gin Alchemist
**Portrait1Body:** Jonas has spent years perfecting the old ways of the still. "Botanicals are my weapons."
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
**OrderNote:** Contenders enter in order of seniority: <b>Druidingo</b>, then <b>Falkorc</b>, then <b>Jonas</b>. Only two will continue.
**Button:** Return — Name the Finalists

## act1_finalists

**Eyebrow:** The Ledger Has Spoken
**Heading:** Name the Finalists
**Body:** Of the three who entered their craft into the record, only two may carry the trial forward. Click to crown exactly two.
**Button:** Confirm Finalists

## act1_grading

**Eyebrow:** Trial I — Complete
**Heading:** Grading the Protocols
**Body:** Judge what you actually saw in the Ledger — drag each slider to the grade each contender's protocol earned.
**Button:** Confirm Grades

## act2_brief

**Eyebrow:** Trial II
**Heading:** Naming the Gin
**Body:** Everyone in the village knows a gin's tasting name carries more than flavor — it carries feeling, memory, longing, the whole unreasonable weight of a good evening. And there's no truer test of a gin than the tonic poured beside it.
<br><br>Each contender mixes three gin tonics — choose the ingredient, raise the bottle, tilt it to the line. Pour close to the mark and the name that emerges is something to be proud of. Falkorc's bottle, for reasons nobody can explain, pours a great deal more eagerly than it should.
**Button:** Let the Mixing Begin

## act3_brief

**Eyebrow:** Trial III
**Heading:** The Puzzle of Tastes
**Body:** Things aren't going well for Falkorc, so he's staking everything on a crazy slogan for his gin. Both houses have six candidate slogans painted on the walls of the square — and one minute to match their colors on the great puzzle cube. Whichever slogans the cube actually matches are the ones that stick.
**Button:** Begin the Puzzle

## act3_slogans

**Eyebrow:** Trial III — In Progress
**Heading:** Matching the Slogans
**Button:** Start the Clock

## act3_recap

**Eyebrow:** The Night's Ledger
**Heading:** Wood Science Village Decides
**Body:** Protocol, flavor, and slogan — everything the village has seen tonight, side by side.
**Body2:** The crowd will decide who has the best gin!

## rebellion

**Eyebrow:** An Unexpected Turn
**Heading:** The Village Rebels
**Body:** The crowd leans toward Falkorc for a moment — his slogan lands, tankards rise in his name. But before the cheer even settles, a louder chant rises from the back of the square and does not stop: <i>"Jonas! Jonas! Jonas!"</i> Whatever the room decided a moment ago, Wood Science Village has now made up its mind.
**Button:** See How the Night Ends

## finale

**Eyebrow:** Epilogue
**Heading:** Jonas' Gin — Different Minds, Same Spirit(s)
**Body:** By nightfall the whole square is toasting — Ingo, Jonas, even Falkorc himself, glass raised beside the owlbear statue. Two bars, one crowd, one very loud verdict.
**Body2:** <b>In every world that matters: Jonas Maas has successfully defended his thesis.</b>
**Closing:** — The End —
