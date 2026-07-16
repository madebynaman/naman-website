# Naman Sharma — 5 homepage directions (sonnet-5)

## d1 — Dossier

**Concept.** The homepage as a reviewed case file: folder-tab navigation
labeled as exhibits, a rotated "reviewed" stamp, and red-pen marginalia next
to each case study that reads like an editor's note on the work.

**Key decisions.** Fraunces (serif display) + IBM Plex Sans (body) + IBM
Plex Mono (all metadata/labels) — three distinct registers so the "case
file" metaphor holds together typographically. The redline `.annot` device
is the signature element: it lets the page comment on its own claims instead
of just stating them, which fits a research-led designer's voice better than
a plain caption would.

**Trade-offs.** The paper/redline palette is close to the "warm cream +
serif + terracotta" AI default the design skill warns about — mitigated by
pushing the accent to a true editorial red rather than terracotta, and by
making the case-file structure (tabs, stamp, exhibit numbering) do most of
the differentiating work rather than the palette. Numbering is justified
here because exhibits are a real filing convention, not decoration.

## d2 — Night Studio

**Concept.** A cinematic, kinetic-type direction: near-black canvas, a
scrolling marquee of real client names as a film-credits device, and a
cursor-following copper glow that turns the whole page into a spotlight.

**Key decisions.** Bricolage Grotesque for oversized display type (built to
be huge, so it needed a face with real personality at scale) + Inter for
body copy. Copper/amber instead of the acid-green/vermilion-on-black default
— warmer and less "AI dark mode." `mix-blend-mode:difference` on the header
keeps navigation legible over both the dark hero and the lighter glow
without a second color rule.

**Trade-offs.** The marquee and glow are the one bold motion move; everything
else (grid, spacing, type scale) stays quiet so the signature doesn't get
diluted. Marquee auto-scroll is disabled under `prefers-reduced-motion`.
Higher risk direction — a hiring manager who wants restraint may read this
as more "agency reel" than "product portfolio," which is the honest
trade-off of a cinematic bet.

## d3 — Studio Wall

**Concept.** A maximalist pinboard/collage: index cards at slight rotations,
pins, washi tape, and sticky notes — the physical desk of someone who
"gives a damn," including a Jerry-the-dog cameo, without tipping into
unprofessional.

**Key decisions.** Instrument Serif for display (irregular, handmade feel)
+ Space Grotesk for body/UI (keeps density readable despite the collage
layout). Every card has an independent rotation variable so the wall reads
as assembled over time rather than templated. Playfulness is spent on the
frame (pins, tape, stickies), not on the actual case-study language, which
stays factual and outcome-first.

**Trade-offs.** Highest execution risk of the five: rotated cards and dashed
placeholders must stay legible and not read as sloppy. Mobile collapses
rotation and hides floating stickies rather than trying to preserve the
effect at narrow widths, which is a deliberate simplification, not an
oversight.

## d4 — Quiet Systems

**Concept.** A restrained, Swiss-grid direction built around a persistent
left-rail index with scroll-spy-style anchor nav — the opposite bet from d2
and d3: let density and precision carry the page instead of a single loud
signature.

**Key decisions.** Newsreader (an italic serif) for the hero line and body
prose, paired with Archivo for all structural/UI text — inverting the usual
"serif for headlines, sans for body" convention so the display voice feels
literary rather than corporate. No numbered markers except where the record
(career history, process stages) is an actual sequence. Hairlines and a
three-column process grid are the only structural device; there is no
gradient, shadow, or rounded corner anywhere in this direction.

**Trade-offs.** The rail sacrifices some hero drama for legibility and
navigability across a long page — the right trade for a reviewer who wants
to jump straight to "work" or "record" rather than scroll a cinematic
sequence. Collapses to a top bar under 920px since a fixed side rail doesn't
survive narrow viewports.

## d5 — Blueprint

**Concept.** The homepage presented as its own annotated product spec:
frame labels, dimension lines, corner registration marks on every
placeholder, and a literal "change log" table for the career timeline — a
direction that borrows its visual language directly from the artifacts a
product/UX designer actually produces.

**Key decisions.** IBM Plex Mono for every spec/metadata element, Manrope
for prose and headings. Blueprint blue-on-light rather than the more
expected dark blueprint, so it reads as an active work-in-progress document
rather than a mood board. Red is reserved strictly for metrics (the one
thing worth making impossible to miss). The "frame" wrapper around each case
study and the dashed section rules are the throughline that makes the
metaphor legible without over-explaining it.

**Trade-offs.** Leans the most literal/conceptual of the five — it risks
feeling like a UI-design in-joke to a non-design hiring manager. Chosen
anyway because it's the direction most specific to who Naman is (a product
designer, not a generic "creative"), which the brief weights heavily.
</content>
