# Opus 4.8 — Portfolio Homepage Directions

Five distinct long-form homepage directions for **Naman Sharma — Product/UX
Designer**. Each is a single self-contained HTML file (inline CSS, small inline
vanilla JS, Google Fonts via `<link>`, all visuals CSS/SVG placeholders). Open
any `dN-opus-4.8.html` directly in a browser.

The five are deliberately different bets across the axes that matter most:
**layout system, personality, type voice, color ground, and interaction model** —
not one idea recolored. Grounds run warm-light → dark-amber → cool-light →
saturated → dark-slate; type voices run literary-serif → mono-brutalist →
minimal-grotesque → expressive-display → systematic UI.

Every direction respects the same product truth: Naman is a research-rooted,
anti-jargon Product/UX designer who makes complex things simple and takes
startups 0→1. Real case studies (Asian Paints +20% txn, Boost360 −60%
uninstalls, Wikipedia/KaiOS research n=25, freelance incl. Turns' $500K raise)
are teased hard with only the metrics the source documents support.

---

## d1 — "The Monograph"

**Concept.** The portfolio as a published design annual / magazine monograph.
Considered, literary, senior — the voice of someone who can hold a room.

**Key decisions.**
- Editorial grid with a persistent narrow *margin column* (running index +
  italic marginalia) beside a wide reading column, so density reads as a
  typeset feature, not a web dump.
- Fraunces (optical-sizing serif, used with italics as an editorial device) set
  against Archivo grotesque body; drop-caps and hairline rules carry rhythm.
- Warm **bone** paper `#f2efe7` deliberately cooler than the overused cream
  cliché, with a single **oxblood** `#6e1f1b` ink accent for links, rules and
  pulled numerals.
- Case studies are numbered feature articles (numbering is real — a sequence of
  works): meta block, labeled placeholder plate, problem / move split, and one
  large outcome metric.

**Trade-offs.** Committed single (light) theme — the "printed edition" idea
doesn't want a dark mode. Reading-first, so it's the least flashy of the five;
its power is in typographic craft and voice rather than spectacle.

## d2 — "Field Notes / Terminal"

**Concept.** Brutalist-engineering. The portfolio as an engineer's field
notebook / terminal — a nod to Naman's computer-science background and research
rigor. Honest, structural, un-precious.

**Key decisions.**
- Near-black ground `#0c0c0d` with paper-white panels and **one** signal accent,
  amber `#ffb000` (muted terminal-green as a sparing second data color).
- JetBrains Mono for all meta/labels/data (file paths like
  `/work/asian-paints_dealer-portal.case`, IST clock, status) with Archivo Black
  for oversized headlines. Exposed 1px keylines and box-drawing framing.
- Case studies are bordered **data records** with explicit fields
  (CLIENT / YEAR / ROLE / PROBLEM / ROOT CAUSE / MOVE → RESULT), each with a
  wireframe-style placeholder and a huge pulled result.
- Light interactivity: live IST clock, blinking cursor, `● AVAILABLE` status —
  all paused under `prefers-reduced-motion`.

**Trade-offs.** Committed dark, single-theme world. The terminal framing risks
gimmick; kept legible with strong amber-on-black contrast and real hierarchy so
it reads as rigor, not costume.

## d3 — "The Quiet Room"

**Concept.** Quiet-luxury minimalism. Restraint *is* the thesis — the confidence
to leave space. Gallery-quiet, precise, expensive-feeling.

**Key decisions.**
- Near-monochrome cool paper `#fafaf8` with soft `#f1f1ec` bands; body copy held
  near-black (never washed-out grey) so the light palette still passes contrast.
- Instrument Serif used large for a few key lines only (hero thesis, section
  openers) against small, tightly-tracked Hanken Grotesk; immense margins and a
  slow vertical rhythm.
- **One** whisper of color — a desaturated sage `#8c9a86` — appears only as a
  status dot, a hairline, and a hover underline. No loud accent anywhere.
- Progressive disclosure: work items are understated at rest and reveal an extra
  sentence on hover/focus, so density lives in generous space rather than clutter.

**Trade-offs.** The bet is that calm reads as premium; the risk is looking sparse
on a fast scroll. Mitigated by complete real content and precise alignment — the
craft is in the spacing, so it must be read slowly to be felt.

## d4 — "Delight" (Maximalist Pop)

**Concept.** Bold, joyful, high-energy — the visual expression of Naman's own
principle that *delight is what humans remember*, plus his personality (hip-hop,
video games, Jerry the dog). Confident maximalism that stays professional.

**Key decisions.**
- Color-blocked full-bleed bands (each major section owns a color): off-black ink
  and warm cream grounds with electric cobalt `#2b4dff`, acid lime `#c6f24e`,
  hot coral `#ff5c4d`.
- Bricolage Grotesque at huge sizes over DM Sans; hard offset shadows, sticker
  pills, rotated tags, and a CSS marquee of skills (pauses on hover and stops
  under reduced-motion).
- Case studies are big color "drops" with bold CSS mockup placeholders and a
  giant pulled metric (`+20%`, `60%↓`, `25`, `$500K`); Jerry gets a real
  personality card.
- Non-color status signals throughout (icons + labels), and text/background
  pairs chosen to pass contrast despite the loud palette.

**Trade-offs.** The riskiest bet — maximalism can tip into noise. Held together
by a strict grid, consistent border/shadow system, and a fixed 5-color set so it
reads as a controlled point of view, not chaos.

## d5 — "Product OS"

**Concept.** The portfolio *as a product he shipped* — a polished, systematic
software interface. Since Naman is a product designer, the strongest proof is a
piece of UI that operates like one.

**Key decisions.**
- Dark app shell: top bar (logo, `● Available`, live IST clock, contact) + a
  sticky left section-index sidebar that highlights the current section via
  IntersectionObserver. This is a UI to operate, not a document to read.
- Hanken Grotesk UI with IBM Plex Mono for all data; tabular-nums on every
  aligned figure. Deep slate surfaces, hairline borders, subtle dot grid.
- Impact is shown as **hand-built data-viz** (inline-SVG line and bar charts with
  faint grid, area fill, emphasized endpoint, animated draw-in) plus metric
  tiles and status pills — accent blue `#4c8dff` kept separate from semantic
  green/amber, which carry state.
- Case studies are "shipped projects" panels: status pill, role/team meta,
  metric tiles, an outcome chart, and a wireframe placeholder of the actual UI
  kind (dealer portal, signup flow, research artefacts).

**Trade-offs.** Committed dark, single-theme, and the most JS of the five (clock,
active-section, chart draw-in) — all degrade gracefully and respect
`prefers-reduced-motion`. The interface metaphor is the whole idea, so it leans
less on editorial typography than d1/d3.

---

### Notes
- All metrics are drawn only from the source documents; where copy was invented
  it is aesthetic section/label language, never fabricated career facts.
- Placeholders explicitly name the *kind* of image that belongs in each slot for
  the reviewer to drop real assets in later.
- Desktop-first, with graceful narrower-width behavior; accessibility care
  (contrast, focus-visible, semantic HTML, non-color status, reduced-motion) is
  built into every direction.
