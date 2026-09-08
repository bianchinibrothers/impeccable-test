---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

Scope: index.html, the Blastradius marketing landing page. Visitor mode: Persuade.

Audience: on-call SREs evaluating an architecture portal; security engineers secondary. Action: book a walkthrough. Proof: an interactive dependency map that traces blast radius through real service dependencies. Constraint: self-host or cloud, SOC 2 Type II; no invented customers, prices, or benchmarks.

## Direction contract

THESIS: The page is a drawn architecture plate, not a product tour — the system map is the hero and the incident reads as propagation across it. Refuses the SaaS stack of centered hero, three feature cards, logo wall.

OWN-WORLD: Ochre paper ground (oklch(94% 0.035 78)) under a 112px survey grid and multiply grain; deep teal night (oklch(17% 0.035 185)) owns whole regions; gold (oklch(68% 0.145 74)) and burnt sun (oklch(64% 0.19 43)) mark healthy and breaching. Chakra Petch 300 in oversized uppercase over Zen Old Mincho body text; Azeret Mono for all telemetry. Zero radius, hairline rules, no drop shadows except the one lifted plate.

STORY: This is the map of my system, drawn — I can see what a failure touches before it touches me; book the walkthrough.

FIRST VIEWPORT: Full-bleed dark architecture plate right of center, services as nodes on the survey grid with one node in sun-orange and its dependency edges lit outward. Oversized uppercase headline in the left third over a paper scrim, small Mincho summary beneath, mono coordinate rail down the left margin. Primary action sits inline under the summary, not in the header.

FORM: Neo Mirai — user-pinned, beats the roll (seed key 7a766078, mode persuade, assignment index 5 superseded by the pin).

RAISE (from Daylight Section, competitive): every claim carries its component id and timestamp in tabular mono, pinned to coordinates.
RAISE (from Mesophotic Dive): one governing vertical axis every element registers to.
RAISE (from Phosphor Terminal): state prints itself as content, never as a chrome badge.
RAISE (from Telop Field): scale maps to severity magnitude, read before the words.
RAISE (from Linocut): single-ink commitment — night teal owns whole regions rather than tinting accents.

NOTE: pinned world, full material range. Ochre, teal, gold, sun — never softened to cream-and-serif.

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance

## Finish state

Two review rounds spent. Round 1 (full review): disposition fix, 8 material findings, all 8 addressed. Round 2 (verdict pass, run by a fresh reviewer from degraded/finish-reviewer.md because this harness has no agent continuation): 5 resolved, 2 partial, 3 regressions named, disposition fix.

The user was given the table at the two-round ceiling and chose "just fix the CTA, then stop". R1 was fixed; the remaining four items are knowingly open, not forgotten.

## Unresolved decisions

- **Booking destination.** Both CTAs work (hero scrolls to the close section; the close opens a mail composer), but the address is `walkthrough@blastradius.example` — an IANA-reserved TLD that cannot resolve. Must be pointed at the real booking flow before launch.
- **Timestamp annotation (open, material).** The Daylight Section RAISE promises component id *and* timestamp in tabular mono. Component ids and sheet coordinates ship; no tabular timestamp exists anywhere on the page. The RAISE is half-kept.
- **Map mono under the floor at mobile (open, material).** `svg.map` carries `min-width: 540px` against a `0 0 640 512` viewBox, so below ~640px the map paints at 0.84 scale and `.node-label` / `.node-hop` land at roughly 9.3–9.7 CSS px, under the 11.5px floor. Fix by raising the in-SVG sizes for that scale factor or reducing `min-width` against the viewBox — re-declaring the values alone will not do it.
- **Mobile reading order (open).** The legend stacks between the hero CTA and the plate, pushing the map below the first screen at 390px, so the reader meets the colour key before the map it keys. FIRST VIEWPORT promises the plate as the hero. Fix by moving the legend after the plate on narrow widths, or folding it into the plate's foot.
- **Header status reads as navigation (open).** `.header-status` at 0.78rem mixed-case mono sits at the nav's optical weight and baseline, so "Demo data · us-east-1 · 13 services" scans as a fourth nav item. Differentiate by figures, rule, size, or colour — not by returning to all-caps, which trips the detector.
- **Held as ceiling, not material:** sheet furniture (title block, registration ticks, scale bar).

## Detector state

Clean except `cramped-padding`, adjudicated by the finish reviewer as false positives (`.band` carries 56–112px padding; `.survey` legitimately has none because a survey table's first row sits on its own rule). Deliberately left unsuppressed on the reviewer's instruction — a file-wide ignore would blind the rule on later work. The only suppression on this project is `cream-palette` scoped to index.html, judged defensible because the flagged ground is Neo Mirai's own `--paper` token and the user pinned that world.
