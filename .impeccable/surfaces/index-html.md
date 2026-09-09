---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

Scope: index.html, the Kith marketing landing page. Visitor mode: Persuade.

Audience: a parent (usually on a phone) deciding whether to keep one private record of their child's health, schooling, friends, and preferences. Action: create an account / log in; secondary, contact. Proof: the shape of the record itself, shown as a synthetic dated ledger page. Constraint: every real feature is behind login; no invented users, prices, certifications, or partners — pricing on the page is labelled provisional.

## Direction contract

THESIS: The page is an open ledger for one childhood — a two-page spread, pitch on the left leaf, a living dated record on the right. Refuses the SaaS stack of centered hero, three feature cards, logo wall, and refuses the scrapbook/photo-feed reading of "family app".

OWN-WORLD: Inherited Neo Mirai, unchanged. Ochre survey paper (oklch(94% 0.035 78)) under the 112px ruled grid and multiply grain; deep teal night (oklch(17% 0.035 185)) owns whole leaves and bands; gold (oklch(68% 0.145 74)) marks a kept entry, burnt sun (oklch(64% 0.19 43)) marks one thing due. Chakra Petch 300 oversized uppercase over Zen Old Mincho body over Azeret Mono for every date, dose, and identifier. Zero radius, hairline rules, one lifted surface (the right leaf).

STORY: This is the record I wish someone had kept for me — shots, schools, the friends who matter, the foods that don't work. It is structured, it is mine to export, and I can start it now.

FIRST VIEWPORT: A two-leaf spread bound at a centre gutter that is the page's governing vertical axis. Left leaf on ochre: oversized uppercase headline broken to three lines, one Zen Old Mincho line beneath, the primary action inline under it, a mono coordinate rail ("Record — leaf 01") down the outer margin. Right leaf as the lifted plate on teal night: a synthetic, clearly-labelled record page — hairline rows, each row a mono date + a domain coordinate (VAX / SCHL / KITH / PREF) + a short entry, one row in burnt sun reading "due", the rest in gold or dimmed. Header carries wordmark, a few anchors, and Log in; no button in the header.

FORM: The Ledger Spread — surface structure roll, seed key b3a21bd4, mode persuade, dealt lead (my ranked #6 of 7). World not rolled: Neo Mirai inherited from the prior product and reaffirmed by the user ("maintain the style and the fonts").

RAISE (from bioluminescent-plankton-wake, challenger to the lead): a kept row shows in gold and carries a mono "last kept" date; a long-untouched row fades toward dim on-night — tending the record is visible as light on the leaf, state always doubled by the date.
RAISE (from Miura-fold deployable sheet, challenger): the right leaf's rows deploy in one orchestrated unfold from the gutter on first view, not a per-element stagger.
RAISE (carried from the inherited world): state prints as content in a mono readout, never as a chrome badge; one governing vertical axis (here the gutter) every element registers to; single-ink — teal night owns whole leaves, never a tinted card.

NOTE: pinned world, full material range — ochre, teal, gold, sun, never softened to cream-and-serif for being a "family" product. Provisional pricing and the synthetic record are labelled as such; Log in and Contact are stubs flagged for wiring.

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance

## Unresolved decisions

- **Product name.** "Kith" is a working name chosen by the user; final name pending. One find-replace to change.
- **Log in destination.** `#login` stub; no auth flow exists. Wire before launch.
- **Contact destination.** `mailto:` with a marked-TODO address (reserved TLD). Point at a real inbox or form before launch.
- **Pricing.** Provisional tiers and numbers, labelled "not final" on the page. Replace with real figures before launch.
- **Synthetic record.** The right-leaf entries and any About-section record rows are invented and labelled synthetic; no real child data.

## Finish state

One review round spent. Round 1 (full review): disposition `fix`, 5 material findings — (1) mobile coordinate rail rendered as a kicker above the `<h1>`; (2) ledger rows shipped `<dd>` with no `<dt>`; (3) ledger deploy layered a per-row stagger on the gutter wipe; (4) DESIGN.md still described the retired Blastradius build; (5) desktop left leaf ended short of the record leaf, reading half-empty. All 5 fixed in one batch. Verdict pass: **all 5 resolved, disposition `ship`** (scope: the five fixes, not a fresh whole-surface pass). No material regressions; one noted minor overlap between the `.leaf-foot` line and the "Your data" note, judged acceptable.

DESIGN.md and `.impeccable/design.json` re-recorded from the shipped build by `impeccable-documenter` (Neo Mirai kept; dependency-map components replaced with the spread / record-leaf-ledger / ruled survey / tiers / contact / rail; grain-bloom colors and full type ramp now documented; `--on-night-dim` at `oklch(70% 0.025 175)`; Binding Axis Rule added).

Not canonised in DESIGN.md: `--ease-quart` and Zen Old Mincho 600/900 are declared/loaded in the build but unused — dead references, safe to prune on the next edit.

## Detector state

Inherited suppression: `cream-palette` scoped to index.html — the flagged ground is Neo Mirai's own `--paper` token and the user pinned that world. `cramped-padding` on the ruled survey rows and bands was adjudicated by the prior finish reviewer as a false positive (a survey table's first row sits on its own rule; bands carry 56–112px padding) and left unsuppressed on purpose.
