---
name: Kith
description: An open ledger for one childhood — ochre survey paper, a teal-night record leaf, and a synthetic dated ledger as the proof.
colors:
  paper: "oklch(94% 0.035 78)"
  paper-soft: "oklch(91% 0.045 78)"
  paper-deep: "oklch(84% 0.06 73)"
  rice: "oklch(97% 0.02 82)"
  ink: "oklch(18% 0.035 82)"
  ink-soft: "oklch(32% 0.045 80)"
  ash: "oklch(42% 0.04 80)"
  line: "oklch(73% 0.055 77)"
  gold: "oklch(68% 0.145 74)"
  gold-bright: "oklch(76% 0.165 80)"
  sun: "oklch(64% 0.19 43)"
  sun-deep: "oklch(46% 0.165 37)"
  night: "oklch(17% 0.035 185)"
  night-soft: "oklch(24% 0.04 170)"
  night-line: "oklch(34% 0.045 175)"
  on-night: "oklch(80% 0.028 175)"
  on-night-soft: "oklch(68% 0.03 175)"
  on-night-dim: "oklch(70% 0.025 175)"
  focus: "oklch(58% 0.18 42)"
  bloom: "oklch(82% 0.11 79 / 0.5)"
  grain-light: "oklch(100% 0 0 / 0.6)"
  grain-mid: "oklch(36% 0.05 70 / 0.18)"
  grain-warm: "oklch(38% 0.07 35 / 0.14)"
  grid-paper: "oklch(20% 0.015 80 / 0.035)"
  grid-night: "oklch(34% 0.045 175 / 0.5)"
typography:
  display:
    fontFamily: "Chakra Petch, Trebuchet MS, sans-serif"
    fontSize: "clamp(3.1rem, 6.9vw, 6.4rem)"
    fontWeight: 300
    lineHeight: 0.94
    letterSpacing: "-0.015em"
    textTransform: "uppercase"
  headline:
    fontFamily: "Chakra Petch, Trebuchet MS, sans-serif"
    fontSize: "clamp(1.9rem, 3.6vw, 3.1rem)"
    fontWeight: 300
    lineHeight: 1
    letterSpacing: "-0.01em"
    textTransform: "uppercase"
  display-secondary:
    fontFamily: "Chakra Petch, Trebuchet MS, sans-serif"
    fontSize: "clamp(2.2rem, 5.2vw, 4.4rem)"
    fontWeight: 300
    lineHeight: 0.98
    letterSpacing: "normal"
    textTransform: "uppercase"
  title:
    fontFamily: "Chakra Petch, Trebuchet MS, sans-serif"
    fontSize: "1.02rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "0.02em"
    textTransform: "uppercase"
  lead:
    fontFamily: "Zen Old Mincho, Georgia, serif"
    fontSize: "clamp(1.25rem, 2.1vw, 1.85rem)"
    fontWeight: 400
    lineHeight: 1.2
  summary:
    fontFamily: "Zen Old Mincho, Georgia, serif"
    fontSize: "clamp(1rem, 1.15vw, 1.1rem)"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "Zen Old Mincho, Georgia, serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.55
  body-tight:
    fontFamily: "Zen Old Mincho, Georgia, serif"
    fontSize: "0.98rem"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Azeret Mono, ui-monospace, SFMono-Regular, monospace"
    fontSize: "0.72rem"
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: "0.1em"
    textTransform: "uppercase"
  telemetry:
    fontFamily: "Azeret Mono, ui-monospace, SFMono-Regular, monospace"
    fontSize: "0.78rem"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0.03em"
    fontFeature: "tabular-nums"
rounded:
  none: "0"
spacing:
  gutter: "clamp(1.25rem, 4vw, 3.75rem)"
  grid: "112px"
  header: "74px"
  spread-gap: "clamp(1.75rem, 4vw, 3.75rem)"
  band: "clamp(3.5rem, 7vw, 7rem)"
  band-head: "clamp(2rem, 4vw, 3.25rem)"
  survey-row: "1.4rem"
  tier-row: "1.6rem"
  ledger-row: "1.1rem"
components:
  action:
    backgroundColor: "{colors.night}"
    textColor: "{colors.rice}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0.95rem 1.6rem"
  action-hover:
    backgroundColor: "{colors.sun-deep}"
    textColor: "{colors.rice}"
  action-quiet:
    textColor: "{colors.ink-soft}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0 0 0.3rem"
  action-quiet-hover:
    textColor: "{colors.sun-deep}"
  nav-link:
    textColor: "{colors.ink-soft}"
    typography: "{typography.label}"
    padding: "0.4rem 0"
  nav-link-hover:
    textColor: "{colors.ink}"
  header-login:
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    padding: "0 0 0.25rem"
  header-login-hover:
    textColor: "{colors.sun-deep}"
  record-leaf:
    backgroundColor: "{colors.night}"
    textColor: "{colors.on-night}"
    rounded: "{rounded.none}"
    padding: "1.1rem 1.2rem 0"
  ledger-row:
    textColor: "{colors.on-night}"
    typography: "{typography.body-tight}"
    rounded: "{rounded.none}"
    padding: "1.1rem 0"
  ledger-row-due:
    textColor: "{colors.rice}"
  survey-row:
    textColor: "{colors.ink-soft}"
    typography: "{typography.body-tight}"
    rounded: "{rounded.none}"
    padding: "1.4rem 0"
  survey-row-night:
    backgroundColor: "{colors.night}"
    textColor: "{colors.on-night}"
    padding: "1.4rem 0"
  tier:
    backgroundColor: "{colors.night}"
    textColor: "{colors.on-night}"
    rounded: "{rounded.none}"
    padding: "1.6rem 0"
---

# Design System: Kith

## Overview

**Creative North Star: "The Ledger Spread"**

Kith is an open book, not a landing page. The first viewport is a two-leaf spread bound at a centre gutter — a single 1px hairline that is the page's governing vertical axis, the line every element registers to. The left leaf sits on ochre survey paper and carries the pitch: an oversized uppercase headline, one serif line beneath it, the primary action inline, a mono note at the foot, and a coordinate rail stamped down the outer margin. The right leaf is the one lifted surface in the whole build — a teal-night plate carrying a synthetic, clearly-labelled dated ledger of one child's record. Nothing floats, nothing rounds, nothing glows. Structure is hairlines and registration; the eye is trained by coordinates (`01 / HEALTH`, `A / FORM`) and by dated rows, not by boxes.

The world is Neo Mirai, pinned by the user and inherited unchanged when the product pivoted to Kith. The OKLCH values in `:root` are the canonical source and the frontmatter above holds them unconverted. The material range is deliberately wide and saturated: ochre paper, deep teal night, survey gold, burnt sun. Softening it toward cream-and-serif because Kith is a "family" product is the one move the world cannot absorb — the ochre is a saturated world's paper, not a beige theme, and it is only legitimate with the teal, gold, and sun present around it.

The type pairing is intentional and slightly against type for a consumer product: oversized Chakra Petch at weight 300 in uppercase over Zen Old Mincho body copy — a serif with old-book weight distribution — with Azeret Mono carrying every date, dose, coordinate, price, and identifier. Density is high but rhythmically ruled: dated ledger rows and long survey rows on hairlines, wide bands of vertical air between sections, and a paper → night → paper → night → paper cadence where the night owns whole regions instead of tinting accents. One authored motion moment: the ledger wipes open from the gutter on first view.

**Key Characteristics:**
- Two-leaf spread bound at a centre-gutter hairline that is the governing vertical axis
- Ochre paper ground under a 112px survey grid and a fixed multiply grain layer
- Zero border-radius anywhere; hairline 1px rules are the only dividers
- Flat by default with tonal layering; exactly one lifted surface (the record leaf)
- Alternating paper and full-bleed teal-night sections, never tinted accents
- Oversized uppercase Chakra Petch display over Zen Old Mincho body, Azeret Mono for all data
- Record state carried by light and by the printed date together, never by colour alone
- Ruled rows — coordinate / term / definition, or date / domain / entry — as the universal list primitive

## Colors

An ochre-paper world with a saturated four-way material range — warm ground, teal night, gold, and burnt sun — held together by ink-brown text and hairline rules.

### Primary
- **Burnt Sun** (`--sun`): the single "due" colour. Marks the one ledger row that needs action (its date and domain coordinate turn sun, its "DUE" sub-line goes sun uppercase), the wordmark's square mark, the `1 due` figure in the ledger tally, and the provisional-pricing note. Rare by design.
- **Sun Deep** (`--sun-deep`): the pressed/hover ground of the primary action, the `childhood` word in the hero headline (`.accent`), and the hover colour of every underlined quiet link (nav, quiet action, contact mail).

### Secondary
- **Survey Gold** (`--gold`): the "kept" colour on night ground — the domain coordinate (`Vax`, `Schl`, `Kith`, `Pref`, `Hlth`) of a current ledger row.
- **Gold Bright** (`--gold-bright`): the emphatic gold — text-selection background, the child's name in the record leaf head, and the term column of survey rows and pricing tiers when they sit on night.

### Tertiary
- **Teal Night** (`--night`): the ink of the world. Owns whole sections (What it keeps, Pricing) and the record leaf, and is the ground of the primary action button and the skip link.
- **Night Soft** (`--night-soft`): the deeper tonal step on night ground; layering, not shadow, is how night gains depth.
- **Night Line** (`--night-line`): every hairline on night ground, and the 112px grid redrawn inside night bands via a `::before` overlay.

### Neutral
- **Ochre Paper** (`--paper`): the page ground, under the grid and grain. Also the fixed header's translucent background (0.9 alpha) behind a 12px blur.
- **Paper Soft** (`--paper-soft`) / **Paper Deep** (`--paper-deep`): scrollbar track and the deepest tonal step on paper.
- **Rice** (`--rice`): the lightest tone, used as text on night — action labels, the "due" entry text, tier prices.
- **Drawing Ink** (`--ink`) / **Ink Soft** (`--ink-soft`) / **Ash** (`--ash`): the text ramp on paper — headings, body copy, and quiet mono metadata respectively.
- **Rule Line** (`--line`): every hairline divider on paper, plus the scrollbar thumb.
- **On Night** (`--on-night`) / **On Night Soft** (`--on-night-soft`) / **On Night Dim** (`--on-night-dim`): the text ramp on night — entry text, dates and secondary labels, and the dimmed metadata of a long-untouched ledger row. `--on-night-dim` ships at `oklch(70% 0.025 175)`, raised from a retired build's 66% for contrast on the night ground.
- **Focus Orange** (`--focus`): the 3px focus ring, offset 4px.

### Texture & Grid (inherited Neo Mirai, decorative — never take content)
- **Warm Bloom** (`bloom`, `oklch(82% 0.11 79 / 0.5)`): a single radial-gradient glow at 72% 4% of the body background, fading to transparent by 20rem — the sheet's one warm light source, top-right.
- **Grain Light / Grain Mid / Grain Warm** (`grain-light` `oklch(100% 0 0 / 0.6)`, `grain-mid` `oklch(36% 0.05 70 / 0.18)`, `grain-warm` `oklch(38% 0.07 35 / 0.14)`): three offset radial dot fields in `body::before`, `position: fixed`, `opacity: 0.4`, `mix-blend-mode: multiply`, `z-index: 60` — the paper tooth that stands in for elevation.
- **Grid rulings** (`grid-paper`, `grid-night`): the 112px grid is painted into the body background in `oklch(20% 0.015 80 / 0.035)` for verticals and `oklch(20% 0.015 80 / 0.028)` for horizontals on paper, and redrawn inside night bands in `oklch(34% 0.045 175 / 0.5)` / `oklch(34% 0.045 175 / 0.4)`. These alpha values are the grid and appear nowhere else.

### Named Rules
**The Full Range Rule.** The ochre ground is only legitimate with the rest of the world present. Any surface using `--paper` must also carry the teal night, the gold, and the burnt sun. Ochre plus a serif and nothing else is the failure mode this palette was pinned to avoid — the ground is a saturated world's paper, not a beige theme, and being a product about children is not licence to soften it.

**The Single-Ink Rule.** Night teal owns whole regions. A section is entirely paper or entirely night; the record leaf is night edge to edge. Night never appears as a tinted card, a stripe, or an accent block inside a paper section.

**The Size-And-Colour Rule.** Record state is never carried by colour alone. A freshly-kept row carries a bright gold domain tag; a long-untouched row dims its domain and metadata toward the ground — but the entry text stays fully legible and every row prints its date, so the state is always doubled by something non-chromatic. The one "due" row adds the literal word "DUE", set uppercase with wider tracking, alongside the sun colour.

## Typography

**Display Font:** Chakra Petch (with Trebuchet MS, sans-serif) — weights 300 and 600
**Body Font:** Zen Old Mincho (with Georgia, serif) — weight 400
**Label/Data Font:** Azeret Mono (with ui-monospace, SFMono-Regular, monospace) — weights 400 and 500

**Character:** A thin, wide, uppercase technical sans set large, resting on an old-book Japanese serif — engineering drawing over printed page. The mono is not decoration; it is the register every date, dose, coordinate, price, and identifier is spoken in.

### Hierarchy
- **Display** (300, `clamp(3.1rem, 6.9vw, 6.4rem)`, 0.94, -0.015em, uppercase): the hero headline only, broken onto three lines by explicit `<span>`s, capped at a 7em measure, `text-wrap: balance`. Its last line is `--sun-deep`.
- **Headline** (300, `clamp(1.9rem, 3.6vw, 3.1rem)`, 1, -0.01em, uppercase): section headings in band heads.
- **Display Secondary** (300, `clamp(2.2rem, 5.2vw, 4.4rem)`, 0.98, uppercase): the closing section heading only, capped at 15ch.
- **Title** (600, 1.02–1.05rem, 0.02em, uppercase): survey-row and pricing-tier terms (1.02–1.05rem), the "Your data" sub-head (1.05rem), the wordmark (1.02rem at 0.11em tracking). The one place the display face runs at weight 600.
- **Lead** (Mincho 400, `clamp(1.25rem, 2.1vw, 1.85rem)`, 1.2): the single serif line under the hero display, capped at 18ch, in `--ink`.
- **Summary** (Mincho 400, `clamp(1rem, 1.15vw, 1.1rem)` — effectively 1.05rem, 1.55): the hero summary, band-head copy, closing-section copy, and contact copy (1.02rem). The default reading size for a paragraph in the system.
- **Body** (Mincho 400, 1rem, 1.55): the inherited base size on `<body>`; almost every paragraph overrides to Summary or Body-Tight.
- **Body-Tight** (Mincho 400, 0.98rem, 1.5): ledger entries, pricing-tier descriptions, survey definitions, and the "Your data" note (0.97rem). Prose that sits inside a ruled row.
- **Label** (Mono 500, 0.7–0.75rem, 0.09–0.12em, uppercase): nav links and header login (0.72rem), action buttons and skip link (0.75rem), quiet action (0.73rem), row coordinates (0.72–0.75rem), the "Synthetic" tag and "kept" sub-line (0.72rem), the ledger domain coordinate (0.7rem), the vertical rail (0.72rem at 0.42em tracking).
- **Telemetry** (Mono 400–500, 0.78rem primary, 0.02–0.06em, tabular-nums, mixed-case): the data register. Neighbour sizes shipped in the build: 1.05rem (pricing amount), 0.95rem (contact address), 0.82rem (provisional-pricing note), 0.8rem (footer), 0.78rem (left-leaf foot note), 0.76rem (ledger date column `.when`), 0.74rem (record-leaf foot caption and tally). This is data being read, not a label.

### Named Rules
**The Inverted Heading Rule.** The large display line comes first and the small serif line sits beneath it. Nothing precedes a heading. The coordinate rail ("Record — leaf 01") is a vertical margin stamp on desktop and a trailing sheet stamp below the spread on mobile — it is never a kicker or eyebrow above the headline. This world has no kicker position and never invents one.

**The Telemetry Mono Rule.** Every date, dose, domain coordinate, price, tally, and identifier is set in Azeret Mono with `font-variant-numeric: tabular-nums`. Prose is never mono; dates and doses are never serif.

**The Measure Rule.** Mincho body copy always carries an explicit `max-width` in `ch`: 18ch hero lead, 40ch hero summary, 48ch band-head copy, 62ch survey definitions, 52ch tier descriptions, 46ch close copy, 56ch contact copy, 34ch record-leaf caption and left-leaf foot note. An unbounded serif paragraph is out of system.

## Layout

A single-column page of full-bleed bands inset by a fluid gutter (`clamp(1.25rem, 4vw, 3.75rem)`) via the `.shell` wrapper. The governing structure is a **112px survey grid** painted into the body background as two 1px linear-gradient rulings over ochre (`grid-paper`: `oklch(20% 0.015 80 / 0.035)` verticals, `/ 0.028` horizontals) with a warm `bloom` radial at 72% 4%; night bands redraw the same 112px grid in `grid-night` (`oklch(34% 0.045 175 / 0.5)` and `/ 0.4`) through a `::before` overlay, so the grid runs continuously regardless of ground. A fixed grain layer (`grain-light` / `grain-mid` / `grain-warm` dot fields, `opacity: 0.4`, `mix-blend-mode: multiply`) sits over the whole viewport.

The fixed header is 74px, translucent ochre at 0.9 alpha over a 12px backdrop blur, with a hairline bottom rule; its grid is `auto 1fr auto` (wordmark / nav / login).

**The spread** is the hero: a three-track grid `minmax(0, 0.92fr) 1px minmax(0, 1.08fr)` with `align-items: stretch`, a `clamp(1.75rem, 4vw, 3.75rem)` column gap, and the centre 1px track as the binding gutter (a `linear-gradient(var(--line) 62%, transparent)` hairline). The left leaf is a flex column so its mono foot note seats against the binding at full height. The coordinate rail is absolutely positioned in the outer margin (`left: calc(var(--gutter) * 0.28)`, `writing-mode: vertical-rl`, 0.42em tracking) with a fading 1px tail. At 1080px the spread collapses to a single flex column, the gutter turns horizontal, and the rail re-orders to trail the spread as a static horizontal sheet stamp with a top rule.

Sections are `.band`s with `clamp(3.5rem, 7vw, 7rem)` vertical padding and a hairline bottom rule, alternating paper → night → paper → night → paper. Band heads cap at 62rem with a `clamp(2rem, 4vw, 3.25rem)` bottom margin. Lists are ruled grids: survey rows are `6.5rem / minmax(0,15rem) / minmax(0,1fr)` on 1.4rem block padding between hairlines; pricing tiers are `4rem / minmax(0,12rem) / minmax(0,1fr) / auto` on 1.6rem; ledger rows are `6.1rem / 4.4rem / minmax(0,1fr)` on 1.1rem. The contact grid is `minmax(0,1.4fr) minmax(0,1fr)` with the data note carrying a left hairline rule.

Breakpoints in use: **1080px** (spread and contact grid collapse to one column, rail trails horizontal), **760px** (nav hides, survey rows stack, ledger rows go two-column with the entry spanning full width, tiers go two-column, record-leaf side padding tightens to 0.9rem), **560px** (header collapses to `1fr auto`). Reduced motion collapses all transitions to 1ms, disables smooth scrolling, and removes the ledger clip-path.

### Named Rules
**The Survey Grid Rule.** 112px is the page's only spatial module. Grid overlays, on paper (`grid-paper`) or on night (`grid-night`), are drawn at `--grid` and never at a second interval.

**The Ruled List Rule.** Multi-item content is a ruled row set — a coordinate or index, a term, a definition, on hairlines. The three-up card triptych does not exist in this system: the What-it-keeps list, the trigger-moments list, and the pricing tiers all use the identical grammar, pricing included (a right-aligned mono price is a fourth column, never a card).

**The Binding Axis Rule.** The spread has one governing vertical axis — the centre-gutter hairline — and every element in the first viewport registers to it. When the spread stacks, the axis becomes a horizontal rule between the leaves; it is never dropped.

## Elevation & Depth

The system is **flat by default with tonal layering**, and carries exactly one shadow. Depth on paper comes from stepping `--paper` → `--paper-soft` → `--paper-deep` and from hairline rules; depth on night comes from `--night` → `--night-soft` with `--night-line` strokes. A fixed grain layer (three offset radial dot fields — `grain-light` / `grain-mid` / `grain-warm` — at 0.4 opacity in `mix-blend-mode: multiply`, `z-index: 60`) supplies surface texture in place of elevation. The only two lifts in the entire build are the record leaf's shadow and a flat `--sun` halo ring on the 11px wordmark mark.

### Shadow Vocabulary
- **Leaf lift** (`box-shadow: 0 28px 90px oklch(24% 0.05 75 / 0.22)`, stored as `--plate-shadow`): the single lifted surface. Reserved for the right-leaf record plate — the one object that reads as pinned onto the sheet rather than printed into it.
- **Mark halo** (`box-shadow: 0 0 0 4px oklch(64% 0.19 43 / 0.2)`): a flat spread ring, no blur, on the wordmark square only. Not an elevation.

### Named Rules
**The One Lifted Surface Rule.** A screen gets at most one shadowed object, and it is the record leaf. Everything else — the left leaf, rows, header, buttons, tags — sits flat on its ground and is separated by hairline rules or by tone.

## Shapes

Zero radius, everywhere, without exception: buttons, the record leaf, the wordmark mark, the "Synthetic" tag, scrollbar thumbs. `rounded.none` is the only shape token the system has.

Form language is drawn rather than built: 1px strokes in `--line` on paper and `--night-line` on night, used as top and bottom rules on every row set, a left rule on the contact data note (becoming a top rule when stacked), a bottom rule under the fixed header, and a bordered rectangle around the mono "Synthetic" tag. Fills are rectangular and axis-aligned — an 11px wordmark square, the record leaf itself. Decorative terminations fade rather than stop: the binding gutter is a `linear-gradient(var(--line) 62%, transparent)` and the rail's tail is a `linear-gradient(var(--line), transparent)`. The record leaf sets `overflow: clip` so the ledger wipe is masked to its edge.

## Components

### Buttons
- **Shape:** hard rectangle (0 radius), no border.
- **Primary (`.action`):** night ground with rice text, mono 0.75rem/500 at 0.12em tracking, uppercase, padded `0.95rem 1.6rem`, with a 14px inline stroked SVG arrow at 1.5 weight. Appears inline in content (under the hero summary, in the close band) — never in the header.
- **Hover:** ground moves night → `--sun-deep` with a 2px lift (`translateY(-2px)`), 220ms on `--ease`.
- **Quiet (`.action-quiet`):** no ground — mono uppercase in `--ink-soft` over a 1px `--line` underline, 0.3rem below the baseline. On hover the text goes `--sun-deep` and the underline goes `--sun`.

### Navigation
- **Wordmark:** the display face at 600/1.02rem, 0.11em tracking, uppercase, preceded by an 11px `--sun` square carrying the flat halo ring.
- **Primary nav (`.site-nav`):** three mono uppercase anchors at 0.72rem/0.1em, `--ink-soft`, right-aligned, on a transparent 1px bottom border that fills with `--sun` on hover while the text darkens to `--ink`. Hidden entirely below 760px.
- **Header login (`.header-login`):** the same mono label, `--ink`, on a persistent 1px `--line` underline that goes `--sun` on hover (text `--sun-deep`). A link, never a button.

### The Spread (signature layout)
Two leaves bound at the centre gutter. `.leaf-a` (ochre, `0.92fr`) is a flex column: headline, serif lead, serif summary, inline actions, and a mono `.leaf-foot` note that seats against the binding at full height with a top rule. `.leaf-b` (`1.08fr`) is the record leaf. The `.gutter` is a 1px stretch track; the `.rail` is a margin stamp. Collapses to one flex column at 1080px with the rail re-ordered to trail. Never introduce a third leaf or a second axis.

### The Record Leaf & Ledger (signature)
- **Leaf (`.leaf-b`):** the one lifted surface — night ground, leaf-lift shadow, `padding: 1.1rem 1.2rem 0`, `overflow: clip`, zero radius.
- **Head (`.leaf-b-head`):** a mono 0.8rem/tabular row, `--on-night-soft`, hairline-ruled beneath; the child's name in `--gold-bright`; a bordered "Synthetic" tag in `--on-night-dim` (1px `--night-line` border, uppercase 0.72rem) that keeps the demo data honestly labelled.
- **Row (`.ledger-row`):** a three-column grid `6.1rem / 4.4rem / minmax(0,1fr)`, baseline-aligned, `padding-block: 1.1rem`, bottom hairline in `--night-line`. `<dt class="when">` is a mono tabular date (0.76rem) in `--on-night-soft`; `<dt class="dom">` is a mono uppercase domain coordinate (0.7rem, VAX / SCHL / KITH / PREF / HLTH) in `--gold`; `<dd class="entry">` is the serif entry in `--on-night` at 0.98rem with a mono `.kept` "kept &lt;date&gt;" sub-line (0.72rem) in `--on-night-dim`.
- **State:** `.is-aging` dims the domain to `--on-night-soft`; `.is-stale` dims the domain and kept metadata to `--on-night-dim` — the entry text stays fully legible and the printed date always doubles the signal. `.is-due` turns the date and domain `--sun`, the entry `--rice`, and the `.kept` line into the literal word "DUE" set `--sun` uppercase at 0.1em.
- **Foot (`.leaf-b-foot`):** a top-ruled row with a mono `--on-night-soft` caption (0.74rem, capped 34ch, restating that the entries are synthetic) and a mono `.tally` (0.74rem) — `7 kept · 1 due`, the `1 due` in `--sun`.
- **Motion:** one authored moment. `html.js .ledger` starts `clip-path: inset(0 100% 0 0)` and transitions to `inset(0)` over 820ms on `--ease` when the leaf enters the viewport (IntersectionObserver at threshold 0.35 on the container, with a 1600ms load-time safety net). No per-row stagger. Reduced motion removes the clip entirely.
- **Mobile (760px):** rows go two-column (`6.1rem / 1fr`) with the entry spanning full width; leaf side padding tightens to 0.9rem.

### Ruled Survey (the list primitive)
- **Structure:** a three-column grid — `.coord` (6.5rem, mono uppercase 0.72rem/0.09em, `--ash` or `--on-night-soft`, tabular), `<dt>` (up to 15rem, display face 600/1.02rem uppercase), `<dd>` (fluid, Mincho 0.98rem, max 62ch), baseline-aligned.
- **Rules:** a top rule on the list, a bottom rule on every row. No cell backgrounds, no zebra, no radius. Stacks to one column at 760px.
- **Grounds:** identical geometry on paper (`--line`, ink ramp) and on night (`--night-line`, `--gold-bright` terms, `--on-night` definitions).

### Pricing Tiers
The same ruled-row grammar, on night ground, never a card triptych. A `.price-note` in `--sun` (mono 0.82rem) above the list carries the provisional-pricing disclaimer. Each `.tier` is a four-column grid `4rem / minmax(0,12rem) / minmax(0,1fr) / auto` on 1.6rem block padding between `--night-line` hairlines: a Roman-numeral `.coord` (0.75rem), a `--gold-bright` display-face term (1.05rem), a Mincho description (0.98rem, max 52ch), and a right-aligned mono `.price` — a `--rice` amount block (1.05rem) over an uppercase `--on-night-dim` "provisional" unit label (0.72rem). At 760px the price rides the right column across two rows.

### Contact & Data Note
A two-column grid (`minmax(0,1.4fr) minmax(0,1fr)`). Left: a serif paragraph (1.02rem) and a mono `.contact-mail` address (0.95rem) on a 1px `--line` underline (hover `--sun` / `--sun-deep`). Right: `.data-note` set off by a left hairline rule and `clamp(1rem, 2vw, 2rem)` of left padding, with a display-face 600 sub-head (1.05rem) in `--ink-soft` and a serif paragraph at 0.97rem. At 1080px the grid stacks and the data note's left rule becomes a top rule.

### Coordinate Rail
The spread's margin stamp: a mono uppercase label ("Record — leaf 01") at 0.72rem/0.42em in `--ash`, `writing-mode: vertical-rl`, with a fading 1px `--line` tail. Below 1080px it turns horizontal (0.28em tracking), gains a top rule, and trails the spread as a sheet stamp — it never moves above the headline.

### Browser Surfaces
Themed from the palette: selection is `--gold-bright` on `--ink`; `:focus-visible` is a 3px `--focus` ring at 4px offset; the scrollbar is 11px with a `--line` thumb on a `--paper-soft` track (`--ash` on hover). The skip link is night ground / rice mono (0.75rem), revealed on focus.

## Do's and Don'ts

### Do:
- **Do** carry the full material range on every surface — ochre paper, teal night, gold, and burnt sun together (The Full Range Rule).
- **Do** bind the first viewport to one centre-gutter axis and register every element to it; keep the axis as a rule when the spread stacks.
- **Do** give night teal whole sections and the whole record leaf, and alternate paper → night → paper as the section rhythm.
- **Do** draw structure with 1px hairlines in `--line` on paper and `--night-line` on night, and keep every corner at 0 radius.
- **Do** carry the inherited grain (`grain-light` / `grain-mid` / `grain-warm`), the warm `bloom` at top-right, and the 112px grid rulings (`grid-paper` / `grid-night`) as the only decorative layers; they never take content.
- **Do** use the ruled row — coordinate / term / definition, or date / domain / entry — as the list primitive on both grounds, pricing included.
- **Do** double every record-state signal with something non-chromatic: a legible entry, a printed date, or the literal word "DUE".
- **Do** set every date, dose, domain coordinate, price, and identifier in Azeret Mono with tabular figures, and all prose in Zen Old Mincho with an explicit `ch` measure.
- **Do** put the large display line first and the small serif line beneath it; keep the coordinate rail in the margin or trailing, never above the heading.
- **Do** label synthetic demo data as synthetic in the leaf head and restate it in the foot; label provisional pricing as provisional.
- **Do** keep the 112px survey grid as the only spatial module, on paper and on night alike.
- **Do** animate the ledger as one orchestrated wipe from the gutter on first view; collapse it under reduced motion.

### Don't:
- **Don't** soften the world to cream-and-serif because Kith is about children. Ochre without the teal, gold, and sun around it is out of system.
- **Don't** add a second shadow. The record leaf is the only lifted surface; everything else is flat with tonal layering.
- **Don't** round anything. No radius token exists above 0.
- **Don't** use night teal as an accent tint, a stripe, or a coloured card inside a paper section.
- **Don't** convey record state by colour alone — the accessibility commitment requires a printed date or word alongside it.
- **Don't** place a kicker or eyebrow above a heading. The inverted hierarchy is the world's own device and there is no eyebrow position to fill.
- **Don't** build a three-up feature-card triptych or a pricing-card row. Multi-item content is a ruled row set.
- **Don't** set body prose in mono or dates in the serif, and don't let a Mincho paragraph run without a `ch` cap.
- **Don't** stagger the ledger rows individually; the wipe is a single unfold with no per-row timing.
- **Don't** put a button in the header. The header carries the wordmark, anchors, and an underlined login link only.
