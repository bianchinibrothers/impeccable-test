---
name: Blastradius
description: A drawn architecture plate — ochre survey paper, teal night regions, and a dependency map as the hero.
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
  on-night-dim: "oklch(66% 0.022 175)"
  focus: "oklch(58% 0.18 42)"
  glow-gold: "oklch(82% 0.11 79 / 0.5)"
  grain-light: "oklch(100% 0 0 / 0.6)"
  grain-mid: "oklch(36% 0.05 70 / 0.18)"
  grain-warm: "oklch(38% 0.07 35 / 0.14)"
  node-hit: "oklch(30% 0.07 60)"
  mag-rest: "oklch(52% 0.06 175)"
  mag-track-origin: "oklch(38% 0.09 45)"
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
  title:
    fontFamily: "Chakra Petch, Trebuchet MS, sans-serif"
    fontSize: "1.02rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "0.02em"
    textTransform: "uppercase"
  display-secondary:
    fontFamily: "Chakra Petch, Trebuchet MS, sans-serif"
    fontSize: "clamp(2.2rem, 5.2vw, 4.4rem)"
    fontWeight: 300
    lineHeight: 0.98
    letterSpacing: "-0.02em"
    textTransform: "uppercase"
  subhead:
    fontFamily: "Chakra Petch, Trebuchet MS, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "0.02em"
    textTransform: "uppercase"
  lead:
    fontFamily: "Zen Old Mincho, Georgia, serif"
    fontSize: "clamp(1.25rem, 2.1vw, 1.85rem)"
    fontWeight: 400
    lineHeight: 1.2
  summary:
    fontFamily: "Zen Old Mincho, Georgia, serif"
    fontSize: "clamp(1rem, 1.15vw, 1.12rem)"
    fontWeight: 400
    lineHeight: 1.5
  body-emphasis:
    fontFamily: "Zen Old Mincho, Georgia, serif"
    fontSize: "1.08rem"
    fontWeight: 400
    lineHeight: 1.55
  caption:
    fontFamily: "Zen Old Mincho, Georgia, serif"
    fontSize: "0.92rem"
    fontWeight: 400
    lineHeight: 1.45
  map-label:
    fontFamily: "Azeret Mono, ui-monospace, SFMono-Regular, monospace"
    fontSize: "11px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.02em"
  body:
    fontFamily: "Zen Old Mincho, Georgia, serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "Azeret Mono, ui-monospace, SFMono-Regular, monospace"
    fontSize: "0.75rem"
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: "0.1em"
    textTransform: "uppercase"
  telemetry:
    fontFamily: "Azeret Mono, ui-monospace, SFMono-Regular, monospace"
    fontSize: "0.8rem"
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: "0.04em"
    fontFeature: "tabular-nums"
rounded:
  none: "0"
spacing:
  gutter: "clamp(1.25rem, 4vw, 3.75rem)"
  grid: "112px"
  header: "74px"
  band: "clamp(3.5rem, 7vw, 7rem)"
  band-head: "clamp(2rem, 4vw, 3.25rem)"
  row: "1.4rem"
  plate: "1.1rem"
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
  plate:
    backgroundColor: "{colors.night}"
    textColor: "{colors.on-night}"
    rounded: "{rounded.none}"
    padding: "1.1rem 1.1rem 0"
  survey-row:
    textColor: "{colors.ink-soft}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: "1.4rem 0"
  survey-row-night:
    backgroundColor: "{colors.night}"
    textColor: "{colors.on-night}"
    padding: "1.4rem 0"
  node-box:
    backgroundColor: "{colors.night-soft}"
    textColor: "{colors.on-night}"
    rounded: "{rounded.none}"
    width: "128px"
    height: "34px"
  node-box-origin:
    backgroundColor: "{colors.sun-deep}"
    textColor: "{colors.rice}"
  node-box-hit:
    backgroundColor: "oklch(30% 0.07 60)"
    textColor: "{colors.gold-bright}"
---

# Design System: Blastradius

## Overview

**Creative North Star: "The Surveyor's Plate"**

Blastradius is drawn, not laid out. The page behaves like a large architecture sheet: ochre survey paper with a 112px grid ruled across it, a multiply grain sitting over the whole surface, and a single dark plate pinned onto it carrying the dependency map. Nothing floats, nothing rounds, nothing glows. Structure is made of hairlines and registration, and the reader's eye is trained by coordinates (`01 / SLO`, `06 / DEP`) rather than by boxes.

The world is Neo Mirai, pinned by the user and copied at the token level rather than paraphrased — the OKLCH values in `:root` are the canonical source and the frontmatter above holds them unconverted. It replaced a previous Bricolage Grotesque / IBM Plex / blue identity wholesale; that earlier system is anti-reference, not authority, and nothing from it survives in this build. The material range is deliberately wide and saturated: ochre paper, deep teal night, gold, burnt sun. Softening it toward cream-and-serif is the one move the world cannot absorb.

The type pairing is the second surprise and it is intentional: oversized Chakra Petch at weight 300 in uppercase, over Zen Old Mincho body copy — a serif with old-book weight distribution that is unusual for an ops product and gives the technical content a drawn, printed register. Azeret Mono carries everything numeric. Density is high but rhythmically ruled: long survey rows on hairlines, wide bands of vertical air between sections, and an alternating paper → night → paper → night → paper cadence where the night owns whole regions instead of tinting accents.

**Key Characteristics:**
- Ochre paper ground under a 112px survey grid and a fixed multiply grain layer
- Zero border-radius anywhere; hairline 1px rules are the only dividers
- Flat by default with tonal layering; exactly one lifted surface (the plate)
- Alternating paper and full-bleed teal-night sections, never tinted accents
- Oversized uppercase Chakra Petch display over Zen Old Mincho body, Azeret Mono telemetry
- Severity carried by size and colour together, never by colour alone
- Ruled survey rows (coordinate / term / definition) as the universal list primitive

## Colors

An ochre-paper world with a saturated four-way material range — warm ground, teal night, gold, and burnt sun — held together by ink-brown text and hairline rules.

### Primary
- **Burnt Sun** (`--sun`): the failure colour. Marks the origin node in the dependency map, the wordmark's square mark, and the severity figure in the readout. Rare by design — it appears where something is breaching, and nowhere decorative.
- **Sun Deep** (`--sun-deep`): the pressed/hover state of the primary action, the `radius` word in the hero headline, and the annotation colour for `.role-note`. Also the origin node's box fill under a `--sun` stroke.

### Secondary
- **Survey Gold** (`--gold`): the in-radius colour. Fills the magnitude bar of an affected node, lights the traced edge runs, and keys the readout labels on night ground.
- **Gold Bright** (`--gold-bright`): the emphatic gold — text selection background, hop counters (`+1`, `+2`), and the term column of survey rows when they sit on night.

### Tertiary
- **Teal Night** (`--night`): the ink of the world. Owns whole sections and the plate, and is the background of the primary action button.
- **Night Soft** (`--night-soft`) / **Night Line** (`--night-line`): the map's node fill and the hairline rule colour on night ground. `--night-line` also re-draws the 112px survey grid inside night bands.
- **On Night** (`--on-night`) / **On Night Soft** (`--on-night-soft`): body and secondary text on night ground.

### Neutral
- **Ochre Paper** (`--paper`): the page ground, under the grid and grain. Also the header's translucent background behind a 12px blur.
- **Paper Soft** (`--paper-soft`) / **Paper Deep** (`--paper-deep`): scrollbar track and the deeper tonal step; layering, not shadow, is how the paper gains depth.
- **Rice** (`--rice`): the lightest paper tone, used as text on night — headings in night bands, action labels, origin node labels.
- **Ink** (`--ink`) / **Ink Soft** (`--ink-soft`) / **Ash** (`--ash`): the text ramp on paper — headings, body copy, and quiet mono metadata respectively.
- **Rule Line** (`--line`): every hairline divider on paper, plus the scrollbar thumb.
- **Focus Orange** (`--focus`): the 3px focus ring, offset 4px, and the 2.5px node stroke on `:focus-visible`.

### Named Rules
**The Full Range Rule.** The ochre ground is only legitimate with the rest of the world present. Any surface using `--paper` must also carry the teal night, the gold, and the burnt sun. Ochre plus a serif and nothing else is the failure mode this palette was pinned to avoid — the ground is a saturated world's paper, not a beige theme.

**The Single-Ink Rule.** Night teal owns whole regions. A section is entirely paper or entirely night; night never appears as a tinted card, a stripe, or an accent block inside a paper section.

**The Size-And-Colour Rule.** Severity is never carried by colour alone. Every state that uses gold or sun also changes something non-chromatic — the magnitude bar's width, the stroke weight, a printed hop counter, or a word in the readout.

## Typography

**Display Font:** Chakra Petch (with Trebuchet MS, sans-serif)
**Body Font:** Zen Old Mincho (with Georgia, serif)
**Label/Mono Font:** Azeret Mono (with ui-monospace, SFMono-Regular, monospace)

**Character:** A thin, wide, uppercase technical sans set enormous, resting on an old-book Japanese serif — engineering drawing over printed page. The mono is not decoration; it is the register every number, coordinate, and state reading is spoken in.

### Hierarchy
- **Display** (300, `clamp(3.1rem, 6.9vw, 6.4rem)`, 0.94, -0.015em, uppercase): the hero headline only, broken onto three lines by explicit spans, capped at 6em measure.
- **Headline** (300, `clamp(1.9rem, 3.6vw, 3.1rem)`, 1, -0.01em, uppercase): section headings in band heads. The close section runs the same face heavier in scale (`clamp(2.2rem, 5.2vw, 4.4rem)`, 0.98).
- **Title** (600, 1.02rem–1.5rem, uppercase, 0.02em): survey-row and deploy-row terms, and role headings. The one place the display face runs at weight 600 rather than 300.
- **Lead** (Mincho 400, `clamp(1.25rem, 2.1vw, 1.85rem)`, 1.2): the single small serif line under the hero display, capped at 15ch.
- **Body** (Mincho 400, 1rem–1.08rem, 1.5–1.55): all prose. Measure is capped explicitly — 34ch for the hero summary, 46ch for band-head copy, 60–62ch for row definitions and role prose.
- **Label** (Mono 500, 0.72–0.75rem, 0.08–0.12em, uppercase): nav links, action buttons, legend terms, coordinates, the vertical rail (0.42em tracking).
- **Telemetry** (Mono 400, 0.78–0.8rem, 0.03–0.04em, tabular-nums): plate head, readout, footer, header status. Mixed-case, not uppercase; this is data being read, not a label.

### Named Rules
**The Inverted Heading Rule.** The large display line comes first and the small serif line sits beneath it. Nothing precedes a heading. Annotations that would conventionally be an eyebrow — `.role-note`'s "Primary audience" — are set after their block, in mono, deliberately. This world has no kicker position and never invents one.

**The Telemetry Mono Rule.** Every figure, coordinate, identifier, timestamp, and machine state is set in Azeret Mono with `font-variant-numeric: tabular-nums`. Prose is never mono; numbers are never serif.

**The Measure Rule.** Mincho body copy always carries an explicit `max-width` in `ch` (34–62ch depending on role). An unbounded serif paragraph is out of system.

## Layout

A single-column page of full-bleed bands, inset by a fluid gutter (`clamp(1.25rem, 4vw, 3.75rem)`) via the `.shell` wrapper. The governing structure is a **112px survey grid** painted into the body background as two 1px linear-gradient rulings over ochre, with a warm radial bloom at 72% 4%; night bands re-draw the same 112px grid in `--night-line` through a `::before` overlay, so the grid runs continuously through the page regardless of ground.

The fixed header is 74px, translucent ochre at 0.9 alpha over a 12px backdrop blur, with a hairline bottom rule. The hero is an asymmetric two-column grid (0.86fr copy / 1.14fr plate) that collapses to one column at 1080px; every grid child carries `min-width: 0` so the map's intrinsic width cannot widen the page. A vertical mono rail ("Dependency survey — sheet 01") runs down the left margin in `writing-mode: vertical-rl` and, below 1080px, turns horizontal and becomes a sheet stamp rather than disappearing.

Sections are `.band`s with `clamp(3.5rem, 7vw, 7rem)` vertical padding and a hairline bottom rule, alternating paper → night → paper → night → paper. Lists are ruled survey grids: a 5.5rem coordinate column, a 15rem term column, and a fluid definition column, each row on a 1.4rem block padding between hairlines, collapsing to a single stacked column at 760px. Breakpoints in use: 1080px (hero and roles collapse, pan hint appears), 760px (nav hides, rows stack, plate padding tightens), 560px (header status hides). Reduced motion collapses all transitions to 1ms and disables smooth scrolling.

### Named Rules
**The Survey Grid Rule.** 112px is the page's only spatial module. Grid overlays, on paper or on night, are drawn at `--grid` and never at a second interval.

**The Ruled List Rule.** Multi-item content is a survey — coordinate, term, definition, on hairlines. The three-up card triptych does not exist in this system; the signal list and the deploy list use the identical grammar on opposite grounds.

## Elevation & Depth

The system is **flat by default with tonal layering**, and carries exactly one shadow. Depth on paper comes from stepping `--paper` → `--paper-soft` → `--paper-deep` and from hairline rules; depth on night comes from `--night` → `--night-soft` with `--night-line` strokes. The fixed grain layer (three offset radial dot fields at 0.4 opacity in `mix-blend-mode: multiply`) supplies surface texture in place of elevation. The only two lifts in the entire build are the plate's shadow and a 4px `--sun` halo ring on the 11px wordmark mark.

### Shadow Vocabulary
- **Plate lift** (`box-shadow: 0 28px 90px oklch(24% 0.05 75 / 0.22)`): the single lifted surface. Reserved for the dark map plate — the one object that reads as pinned onto the sheet rather than printed into it.
- **Mark halo** (`box-shadow: 0 0 0 4px oklch(64% 0.19 43 / 0.2)`): a flat spread ring, no blur, on the wordmark square only.

### Named Rules
**The One Lifted Surface Rule.** A screen gets at most one shadowed object, and it is the plate. Everything else — cards, rows, headers, buttons, the map's own nodes — sits flat on its ground and is separated by hairline rules or by tone.

## Shapes

Zero radius, everywhere, without exception: buttons, the plate, node boxes, legend swatches, the wordmark mark, scrollbar thumbs. `rounded.none` is the only shape token the system has.

Form language is drawn rather than built: 1px strokes in `--line` on paper and `--night-line` on night, used as top and bottom rules on lists, a left rule on the minor role column (becoming a top rule when stacked), and a bottom rule under the fixed header. Fills are rectangular and axis-aligned — 128×34px node boxes, 13px legend swatches, 3px magnitude bars, a 4px gradient bar for the magnitude key. Edges in the map are orthogonal runs (vertical, horizontal, vertical) with no curves and no diagonals. Decorative terminations fade rather than stop: the rail's tail is a 1px `linear-gradient(var(--line), transparent)`.

## Components

### Buttons
- **Shape:** hard rectangle (0 radius), no border.
- **Primary (`.action`):** night ground with rice text, mono at 0.75rem/500 with 0.12em tracking, uppercase, padded 0.95rem × 1.6rem, with a 14px inline stroked SVG arrow at 1.5 weight.
- **Hover:** background moves night → sun-deep with a 2px lift (`translateY(-2px)`), 220ms on `cubic-bezier(0.16, 1, 0.3, 1)`.
- **Quiet (`.action-quiet`):** no ground at all — mono uppercase in ink-soft over a 1px `--line` underline, 0.3rem below the baseline. On hover, text goes sun-deep and the underline goes `--sun`.
- **Placement:** primary actions sit inline in content (under the hero summary, in the close band). The header carries no button.

### Navigation
Mono uppercase at 0.72rem with 0.1em tracking, ink-soft, on a transparent 1px bottom border that fills with `--sun` on hover while the text darkens to `--ink`. Four links, right-aligned, hidden entirely below 760px (the page is short and anchor-driven). The wordmark is the display face at 600/1.02rem with 0.11em tracking, preceded by an 11px sun square with a flat halo ring.

### Survey Rows (the list primitive)
- **Structure:** a three-column grid — coordinate (5.5rem, mono uppercase, ash or on-night-soft, tabular figures), term (15rem, display face at 600, uppercase), definition (fluid, Mincho, max 62ch), baseline-aligned.
- **Rules:** a top rule on the list, a bottom rule on every row. No cell backgrounds, no zebra, no radius, no internal padding beyond the 1.4rem block rhythm — the first row sitting directly on its own rule is intentional.
- **Grounds:** identical geometry on paper (`--line`, ink ramp) and on night (`--night-line`, gold-bright terms, on-night definitions).

### Legend
A definition list on hairlines: an 8.5rem term column carrying a 13px swatch with a 1px `--ink` border plus a mono uppercase label, and a definition column in ink-soft at 0.92rem. Four keys: origin (sun), in-radius (gold), clear (transparent with ash border), and magnitude (a 4px bar, gradient-filled to 60%) — so the non-chromatic channel is keyed as explicitly as the colours are.

### The Dependency Map (signature component)
The hero and the reason the system exists: an interactive SVG (`0 0 640 512`) of 13 synthetic services on a dark plate, tracing blast radius through real dependency edges.

- **Nodes:** 128×34px hard rectangles filled `--night-soft` on a `--night-line` stroke, with a mono 11px centred label and an in-box 3px magnitude bar whose width encodes the node's transitive dependent count against the graph maximum. Focusable (`tabindex="0"`, `role="button"`), activated by click, Enter, or Space, each with a `<title>` naming its dependent count.
- **Edges:** orthogonal survey runs (`M … V … H … V`) at 1px `--night-line`, leaving each box from the face pointing at its neighbour.
- **States:** *origin* — sun-deep fill, sun stroke, rice label, sun magnitude fill; *in-radius* — warm dark fill (`oklch(30% 0.07 60)`), gold stroke, gold-bright label, gold magnitude fill, and a printed hop counter above the box; *clear* — returns to night-soft with a dimmed label; *hover* — gold stroke; *focus-visible* — 2.5px `--focus` stroke. Traced edges go gold at 1.8px. All state transitions run 380ms on the standard ease.
- **Reporting:** the trace prints its verdict as content in the plate head and in a mono `aria-live="polite"` readout below the map — never as a chrome badge.
- **Responsive:** the map holds a 540px minimum width and pans horizontally inside `.map-scroll` rather than shrinking its labels; a gold pan hint appears below 1080px.

### The Plate (container)
The only lifted container: night ground, 1.1rem padding, `overflow: clip`, zero radius, carrying the plate lift shadow. Its head is a wrap-flex mono row at 0.8rem with tabular figures, hairline-ruled beneath; its foot is a mono caption and a `min-height: 5.6rem` readout well (8rem below 760px) so the trace output never reflows the page.

### Browser Surfaces
Themed from the palette, not left to the user agent: selection is gold-bright on ink, focus-visible is a 3px `--focus` ring at 4px offset, and the scrollbar is thin with a `--line` thumb on a `--paper-soft` track (ash on hover), 11px wide.

## Do's and Don'ts

### Do:
- **Do** carry the full material range on every surface — ochre paper, teal night, gold, and burnt sun together (The Full Range Rule).
- **Do** give night teal whole sections, and alternate paper → night → paper as the section rhythm.
- **Do** draw structure with 1px hairlines in `--line` on paper and `--night-line` on night, and keep every corner at 0 radius.
- **Do** use the ruled survey row — coordinate, term, definition — as the list primitive on both grounds.
- **Do** encode severity with size and colour together: a bar width, a stroke weight, or a printed hop count alongside every gold or sun state.
- **Do** set all figures, coordinates, and machine states in Azeret Mono with tabular figures, and all prose in Zen Old Mincho with an explicit `ch` measure.
- **Do** put the large display line first and the small serif line beneath it; place annotations after their block.
- **Do** theme browser surfaces from the palette — selection, scrollbar, and a 3px `--focus` ring at 4px offset.
- **Do** keep the 112px survey grid as the only spatial module, on paper and on night alike.
- **Do** print state as content in the plate head and a polite live readout, not as a floating badge.

### Don't:
- **Don't** soften the world to cream-and-serif. Ochre without the teal, gold, and sun around it is out of system.
- **Don't** add a second shadow. The plate is the only lifted surface; everything else is flat with tonal layering.
- **Don't** round anything. No radius token exists above 0.
- **Don't** use night teal as an accent tint, a stripe, or a coloured card inside a paper section.
- **Don't** convey severity or state by colour alone — the accessibility commitment requires a second, non-chromatic channel.
- **Don't** place a kicker or eyebrow above a heading. The inverted hierarchy is the world's own device and there is no eyebrow position to fill.
- **Don't** build a three-up feature-card triptych. Multi-item content is a ruled survey.
- **Don't** set body prose in mono or figures in the serif, and don't let a Mincho paragraph run without a `ch` cap.
- **Don't** shrink map type to fit a viewport; the map pans at its legible size instead.
- **Don't** reintroduce anything from the retired identity (Bricolage Grotesque, IBM Plex, blue `#2f4fd6`) — it is anti-reference, not heritage.
