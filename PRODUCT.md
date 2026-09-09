# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Parents and guardians keeping track of a young child's life across the domains that no single institution holds together: a pediatrician has the shot record, a school has the reports, nobody has the list of the friends who matter or the foods that cause a meltdown. Primary user is a parent on a phone, often filling something in right after an appointment or a pickup. A second caregiver (co-parent, grandparent, sitter) may be invited to read or contribute.

## Product Purpose

Kith is a private logbook for one childhood. Parents record health and immunizations, education milestones, the friends their child loves, and the preferences that make daily life work — in one place, structured, and theirs. It is the book someone wishes they had kept when a form asks "date of last tetanus booster" or "any allergies the class should know about".

## Positioning

Photo apps keep the pictures; Kith keeps the record. It is not a scrapbook and not a medical device — it is the structured, boring, useful history: dates, names, doses, teachers, the things a child is scared of and the song that calms them down. Where a shared album is a feed, Kith is a reference you can answer questions from years later.

## Operating Context

- Entries are made in short bursts, on a phone, between other tasks — the walk back from the car after a checkup
- The record is consulted at specific trigger moments: enrolment forms, a new babysitter, an ER visit, a house move, a custody handover
- Two households or two caregivers may need the same record; access is granted per person, not shared by password
- A child's data is sensitive by definition; parents are the data owners and expect to be able to export and delete everything
- The value compounds over years, so the product has to feel worth keeping open across a long, low-frequency relationship

## Capabilities and Constraints

**Core capabilities (all require an account and are not shown on the marketing site):**

- Record immunizations and health events with dates, and see what is due next against a standard childhood schedule
- Keep education entries — schools, terms, teachers, milestones, reports
- Keep a roster of the people in a child's life: friends they love, those friends' parents, how to reach them
- Keep preferences and needs — foods, allergies, fears, comforts, routines — in a form a new caregiver can read in two minutes
- Invite a co-caregiver with read or contribute access, scoped per child
- Export the full record and delete the account and its data on request

**Constraints:**

- Not a medical record system and not clinical advice; the immunization schedule is a general reference, not a prescription
- Every feature is behind login; the public site can demonstrate the shape of the record only with clearly synthetic data
- Children's data handling must meet applicable child-privacy law (e.g. GDPR / GDPR-K, COPPA where relevant); parental consent is the basis for processing
- Single-child records are the common case; multi-child households are supported but not the design center

## Brand Commitments

- Name: **Kith** — an old word for the people one knows and holds close; the product is about a child and their circle
- Working name pending the user's final choice; everything in the build uses "Kith" and can be renamed in one pass
- Visual world: **Neo Mirai**, inherited unchanged from the previous product on this codebase and reaffirmed by the user ("maintain the style and the fonts"). Ochre survey paper under a ruled grid, teal night owning whole regions, gold and burnt sun as the two signal colours, Chakra Petch 300 uppercase over Zen Old Mincho body over Azeret Mono telemetry, zero radius, hairline rules, one lifted surface. DESIGN.md is the authority and is re-recorded from this build.
- Tone: plain, exact, unsentimental about the record itself and quietly warm about why it is kept. No gamification, no streaks, no "parenting score"
- Responsive and accessible; the phone is the primary surface

## Evidence on Hand

- Landing page at `index.html`, rebuilt for Kith on the inherited Neo Mirai world; replaces the previous product's landing page wholesale (prior work remains in git history)
- No real users, prices, testimonials, security certifications, or partner institutions exist yet. The build must not invent them; pricing on the page is explicitly provisional and labelled as such
- Any record shown on the marketing site is synthetic and labelled synthetic
- `Log in` and `Contact` have no real destinations yet and are marked as open items to wire before launch

## Product Principles

1. **The record is the point** — structured facts a parent can answer a form from, not a feed to scroll
2. **Theirs to take** — the parent owns the data, can export all of it, and can delete all of it
3. **Written in a hurry, read years later** — capture is fast and forgiving; retrieval is precise
4. **The circle counts** — the people a child loves are first-class content, not a note field
5. **Quiet, not sentimental** — no streaks, badges, or scores; the reason to keep it is that it is useful when it matters

## Accessibility & Inclusion

- WCAG 2.1 AA
- Mobile-first: real touch targets, no hover-only affordances, works one-handed
- Colour never carries state alone — the burnt-sun "due" signal is always paired with a word or a date
- Content assumes many family shapes: two households, non-parent guardians, more than one primary caregiver
- Readable typography for long-term use; monospace only for dates, doses, and identifiers
