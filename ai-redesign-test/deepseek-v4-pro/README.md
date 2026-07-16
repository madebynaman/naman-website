# DeepSeek V4 Pro — 5 Design Directions

## d1 — The Architect's Blueprint (Precision / Drafting-table)

**Concept:** A portfolio structured like an architect's working drawing. Precision,
anti-decorative, every element measured. The language is technical but warm — Prussian
blue ink on cream paper, with marginal annotations and blueprint-style linework.

**Key decisions:**
- DM Sans for headings (geometric clarity) + Fira Code for annotations, metrics, and
  marginalia (technical precision) — the contrast between design thinking and engineering
  rigor in one pairing
- Cream paper (#F7F6F3) base with Prussian blue (#1B3A5C) primary, pale cyan
  (#A8D8EA) accents, annotation red (#D4675E) for critical emphasis
- Title block hero — name, role, location, status organized in a measured grid with
  thin rules, like a project sheet header
- Work entries with blueprint-style left-border markers and dot-grid pattern
  placeholders
- Process steps lettered A–D (architectural numbering) for principles

**Trade-offs:** The title block hero is information-dense and may feel cold to viewers
expecting a narrative hook. Marginal annotations are decorative rather than functional
in this context. The dot-grid placeholder pattern, while distinctive, is repeated —
lack of image variety is compensated for by structural variety.

---

## d2 — The Film Director (Cinematic / Narrative)

**Concept:** Portfolio as a storyboard — the title sequence of a design documentary.
Full-bleed dark and light scene bands alternating like a film reel. 16:9 widescreen
placeholders with letterbox framing. Dramatic typography and strong section markers
create a narrative pace.

**Key decisions:**
- Cormorant Garamond (elegant, cinematic display) + Work Sans (clean body) — the
  classic film-title pairing
- Deep charcoal (#161616) dark bands alternating with warm parchment (#F0EDE4) light
  bands — creates visual rhythm across the long scroll
- Golden amber (#E8A838) on dark, soft red (#C44536) on light — each band has its
  own accent color
- "Scene" markers (Scene 01–04) create segmentation without a traditional nav
- Widescreen placeholders with letterbox bars and play-button icons — unmistakably
  cinematic
- Stats as a simple four-column band between dark scenes

**Trade-offs:** Alternating dark/light bands create high contrast fatigue on long
scrolls. The "scene" metaphor, while distinctive, is decorative — the content isn't
actually a sequence in time. The widescreen letterbox pattern takes significant
vertical space and may feel repetitive by the fourth instance.

---

## d3 — The Indexer (Informationist / Encyclopedia)

**Concept:** Portfolio as a curated, cross-referenced archive. Library catalog meets
encyclopedia entry. A fixed sidebar index provides persistent navigation —
every section and work entry has an anchor link. Every work entry has rich metadata
tags (year, client, role, impact). "See also" cross-references link related sections.
The taxonomic precision itself is the personality.

**Key decisions:**
- IBM Plex Serif (scholarly headings) + IBM Plex Sans (clean metadata) — a library
  pairing with real weight
- Warm library page (#FBF9F5) with card catalog tan (#E8DCC8), classification red
  (#BF4B3B), and archival blue (#3A6170) — a color system built from physical library
  materials
- Fixed sidebar index with active-state highlighting via scroll observation — the
  signature interaction element
- Tag system with color-coded categories (client, year, role, impact) on each work
  entry
- Cross-reference blocks at the bottom of sections — making the page a web, not a
  line
- Spec table for capabilities — structured data presentation

**Trade-offs:** The fixed sidebar + scroll interaction is the most complex
implementation of the five directions. The metadata-heavy presentation may overwhelm
skimmers — this direction assumes a reader who wants to browse and cross-reference.
The sidebar takes 260px of horizontal space that is lost on narrower viewports.

---

## d4 — The Monospace Manifesto (Terminal / Code-native)

**Concept:** Naman's computer science background and "re-learning to code" framed as
a typographic-only portfolio. Everything lives in a single monospace typeface — Geist
Mono. The page reads like a beautiful README, a man page, a terminal session. No
imagery at all — the constraint IS the personality. Markdown-inspired heading syntax,
comment-line section dividers, terminal-block hero with blinking cursor, structured
data entries with bracket tags.

**Key decisions:**
- Geist Mono for everything — weight, size, and color differences do the typographic
  work that multiple families would normally handle
- Terminal black (#0D1117) with green phosphor (#00FF88), amber prompt (#FFB347),
  and comment gray (#6E7681) — a terminal palette that is both nostalgic and
  genuinely legible
- Hero is a simulated terminal session with `$` prompts, command output, and a
  blinking cursor
- Section dividers as comment-line rules (`// -----`)
- Work entries formatted as structured data blocks with `[tag]` notation
- No placeholder images — the monospace typography carries the entire visual weight

**Trade-offs:** Zero imagery is a bold constraint but may undersell the visual/UI
design dimension of Naman's work. The terminal aesthetic, while distinctive, can read
as gimmicky to non-technical audiences (recruiters, design leads who don't code).
All-monospace text at length is fatiguing for some readers.

---

## d5 — The Gallery Wall (Exhibition / Curatorial)

**Concept:** Portfolio as a museum exhibition. White cube gallery aesthetic —
enormous horizontal "artwork" placeholders with corner markers, tiny museum-style
object labels beneath each piece, and generous white space that lets the work breathe.
The design disappears and the content commands attention.

**Key decisions:**
- EB Garamond (elegant, art-world serif) + Outfit (clean sans for labels and
  metadata) — a museum catalog pairing
- Pure white (#FFFFFF) base with warm shadow (#E5E0D8) for subtle borders, bronze
  (#8C7A5E) for labels — there is almost no color
- Corner markers on each exhibit frame (TL/TR/BL/BR) — the only decorative elements,
  and they serve a function (framing)
- Museum object labels: artist (client), title (project), date (year), medium (role),
  description, impact — faithfully adapted from gallery conventions
- Stats as a gallery-wide border-separated band — the exhibition's contextual data
- Process rendered as a minimalist numbered list — no cards, no containers

**Trade-offs:** The near-complete absence of color risks feeling sterile or
impersonal. Maximal white space means the page is the longest of the five directions
vertically. The museum metaphor, while executed faithfully, is a well-known lens for
design portfolios — the execution must carry the distinction.
