# glm-5.2 — five portfolio homepage directions

Five genuinely distinct design directions for **Naman Sharma — Product / UX
Designer**, each a complete long-form homepage. Built to the PRD in
`ai-redesign-test/prd.md` from `resume.md` and `portfolio-content.md` only —
every metric, role, date, and client is traceable to those source documents;
nothing was invented that reads as a verifiable career fact.

All five files are self-contained HTML/CSS/vanilla-JS. The only external
request is Google Fonts (via `<link>`, with system-font fallbacks). No
frameworks, no build step, no `<img>`, no remote images, no base64 photography.
Every visual is a deliberate CSS/SVG placeholder labeled with the *kind* of
image that belongs there, so a reviewer can drop real assets in later.

## How to view

Open any `dN-glm-5.2.html` directly in a browser (double-click / `file://`).
Desktop-first; each degrades gracefully to narrower widths.

## The five directions

| File | Name | One-line bet |
|---|---|---|
| `d1-glm-5.2.html` | The Index | A working bibliography — the portfolio as a quiet, archival card catalog. |
| `d2-glm-5.2.html` | Field Notes | A researcher's notebook — the portfolio as taped-in field research. |
| `d3-glm-5.2.html` | Form Follows Function | A working drawing — the page exposes its own construction. |
| `d4-glm-5.2.html` | Give a Damn | A Jaipur maximalist magazine — full-bleed color-blocked spreads. |
| `d5-glm-5.2.html` | Pixel at a Time | A studio console — the portfolio reads like the inside of a designer's tool. |

The five are deliberately different on every axis the frontend-design skill
names: layout system, personality, typographic voice, palette, and interaction
model. They are not one design in five colorways. Notes on each below —
concept, key decisions, and the trade-off accepted.

---

### d1 — The Index

**Concept.** Naman's value is a *body of considered work*, each piece a
citation you can trace. The homepage is a working bibliography — an archival
card catalog, not a gallery. Quiet, refined, library-voiced.

**Key decisions.**
- Palette is warm paper (`#F6F3EC`), deep ink, and an oxidized **rust**
  (`#B45B2E`) — chosen *not* terracotta, to dodge the default cream-and-
  terracotta-serif look the skill flags as an AI tell. Sage as a quiet
  secondary.
- Type: **Fraunces** (optical serif) for display, **Hanken Grotesk** for body,
  **IBM Plex Mono** for catalog call-numbers and metadata. The mono labels do
  the real work of making it read like a catalog.
- Layout: a sticky left **card-catalog index** with call numbers (000–007) and
  fake page numbers, plus a scroll-spy that lights the active entry and a
  reading-progress bar. This is the signature — the index is *alive*, not
  decorative.
- Case studies are "catalog entries" with call numbers, a §-marked findings
  list, "see also" cross-references, and outcome blocks. The anti-jargon
  manifesto becomes a "cross-references — retired phrases" ledger, struck
  through.
- Placeholder visuals are labeled **plates** (Plate 004.a, fig. 1, etc.) drawn
  in CSS — a catalog grid, an onboarding phone flow, a JioPhone article view,
  a freelance collage.

**Trade-off accepted.** An archival library metaphor risks reading as static
or cold. I bought life back with the scroll-spy index and the warm paper, but
the direction stays quiet by design — it is *not* the loud direction. That
restraint is the point, but it asks the reviewer to read rather than skim.

---

### d2 — Field Notes

**Concept.** Naman's work is research-rooted, so show the *thinking*, not the
polish. The homepage is a designer's field notebook — taped-in clippings,
margin annotations, highlighter, red pencil. The Wikipedia / KaiOS study
feels native here.

**Key decisions.**
- Palette is **manila kraft** (`#ECE3CF`), ink, **highlighter yellow** (used
  translucent, like a real marker), and **red pencil** for corrections and
  margin notes. A faded "tape" color for the corner tapes. Distinctly warmer
  and more saturated than d1's cool paper.
- Type: **Caveat** (handwriting) for annotations *only*, **Newsreader** serif
  for body (keeps it legible and professional), **JetBrains Mono** for stamps
  and data. Discipline: the hand face is for marginalia, never body copy —
  which is what keeps it from reading as juvenile.
- Layout: a ruled-notebook page with a **red left margin** (like a real
  notebook), handwritten notes in the margin, and the signature — case studies
  as **taped clippings** with tape at the corners, a slight tilt, a drop
  shadow, a handwritten letter label (A. B. C. D.), and a margin annotation
  beneath each.
- Principles get a red-pencil underline; the process is a 6-step "loop"
  sketched flow with a hand-drawn ↺. Career is a hand-drawn timeline. Clients
  are a taped card. The back cover is the contact page, taped in.

**Trade-off accepted.** A notebook metaphor is one gimmick away from childish.
I held it to "professional field researcher" by keeping body copy in a clean
serif and limiting the hand face to genuine annotations that carry insight
(e.g., "the real cause wasn't crashes — it was the gap between the ad and the
app"). The tape and tilt are restrained (≤1.4°). A reviewer who dislikes
tactile metaphors will like this least — it's the most committed to its
material.

---

### d3 — Form Follows Function

**Concept.** Take Naman's own axiom literally. The page is a **working
drawing** that shows its own construction — visible grid, dimension marks, a
title block, a labeled type scale. A designer who shows the working. Cool,
technical, precise.

**Key decisions.**
- Palette is **drafting white** (`#F4F6F8`, cool) over a visible 32px grid,
  **blueprint blue** (`#1E5FB4`) for construction lines and primary, and
  **dimension red** (`#D03A2C`) for measurement marks and key callouts. This
  is *not* the near-black + acid-accent default — it's a light drafting table.
- Type: **Space Grotesk** (technical display), **Hanken Grotesk** (body),
  **JetBrains Mono** (measurements, data, "ZONE" labels).
- Layout: a **title block** hero (drawing №, scale, drawn-by, status) like an
  engineering sheet; a sticky **mm ruler** across the top; sections labeled
  "ZONE A–G" with a "SCALE 1:1" tag; a **type-scale diagram** that literally
  labels the page's own H1/H2/H3/body/cap sizes in pt (construction shown, not
  hidden); method as a numbered process diagram; career as a **Gantt-style
  table** with a "now" marker line; clients as a "parts list" (BOM).
- Outcomes are rendered as **gauges** with little bar fills — measured, not
  decorative.

**Trade-off accepted.** A blueprint aesthetic is a known gimmick and can feel
like a costume. I kept content legible by using `<div>` zones with real
headings rather than literally hiding text inside a fake CAD drawing, and the
dimension annotations are sparing (ruler + a few labeled specs), not on every
element. The risk: a reviewer could read the exposed grid as decoration
rather than information. I tried to make the construction *true* — the type
scale diagram really is the page's type scale — so the metaphor earns itself.

---

### d4 — Give a Damn

**Concept.** Lean on "Give a damn" and Naman's being in Jaipur. The homepage
is a **bold, maximalist, art-directed magazine** — full-bleed color-blocked
spreads, oversized type, a strong point of view. The loud direction.

**Key decisions.**
- Palette is **saffron/marigold** (`#E89211`), **peacock indigo** (`#1F3A8A`),
  **rani pink** (`#C8287A`), and **chalk** — a Jaipur-inspired palette treated
  like a contemporary design magazine, not a tourism poster. Used as
  full-bleed section colors that alternate (saffron hero → chalk thesis →
  four principle blocks each a different color → indigo process → alternating
  study spreads → indigo contact finale).
- Type: **Bricolage Grotesque** (variable, characterful) for display at
  huge sizes (up to ~168px), **Schibsted Grotesk** for body, **JetBrains Mono**
  for tickers/captions.
- Signature: each section is a **full-bleed color spread** with oversized
  type. Principles are four color blocks (indigo / chalk / rani / ink) each
  with a giant numeral. The hero has a marigold radial mark and a ticker of
  the real metrics. Case studies are spreads with a giant index numeral,
  a big HMW headline, findings, a CSS-drawn plate, and a three-cell stats
  block with very large numbers.
- Career is a bold timeline with a highlighted "now" row. Clients are a
  wall of names with color emphasis. The contact finale is indigo with an
  outlined-stroke display headline.

**Trade-off accepted.** An Indian palette is one cliché away from a festival
poster. I avoided stock "Indian" ornamentation entirely — no mandalas, no
paisley, no faux-devanagari — and let the color blocking and modern type do
the work, closer to a Wallpaper\* spread than a tourism board. The maximalism
also demands the most execution discipline; if the type hierarchy slips, it
gets loud-ugly fast. It is the highest-risk direction and the one that most
separates "world-class" from "templated with a coat of paint."

---

### d5 — Pixel at a Time

**Concept.** From Naman's own intro ("one pixel at a time") and his
re-learning to code: the homepage is **the inside of a designer's tool** — a
single dark studio console with a status bar, a left rail, panels, a live
"now" widget, and a command bar. The only direction whose *interaction model*
is software, not document.

**Key decisions.**
- This is the **only dark direction** (d1–d4 are all light/paper), which buys
  immediate distinctness. Palette: near-black bg (`#14161B`), panel surfaces,
  **amber** (`#F5A623`) as the live signal, **green** for status, **blue** for
  links, **red** for alerts. Not the near-black + acid-green default — amber
  reads as terminal warmth, and the chrome is dense and app-like.
- Type: **JetBrains Mono** for *both* display and chrome/data (a mono display
  is unusual and very on-brand for a console), **Spline Sans** for readable
  body content. No serif anywhere — the furthest typographic voice from d1/d2.
- Layout: a real app shell — **status bar** (traffic lights, breadcrumb path
  that updates with scroll, live IST clock, "open to work"), **left rail nav**
  (with a live "now" widget showing status / based / role / "with jerry 🐕"),
  **main panels** with macOS-style window chrome (dots + path + meta), and a
  sticky bottom **command bar** with a prompt, a blinking cursor (respects
  `prefers-reduced-motion`), and kbd hints.
- Content is re-voiced for the metaphor: principles as `principles.conf`
  config rows (`consistency = > talent`), thesis with a `grep "buzzword"`
  log of retired phrases, process as a `pipeline`, timeline as a log table,
  clients as a chip grid, contact as `./hire-naman --research-first
  --outcomes-after`. Ask-me-about are "modules." A subtle boot sequence opens
  the hero.

**Trade-off accepted.** A console runs the risk of looking like a generic
admin dashboard. I fought that by making it clearly *personal* — the copy is
Naman's voice and his dog, the metrics are his real ones, the "now" widget is
his actual status — and by art-directing the chrome rather than using a
component library. The mono-everywhere choice also hurts long-form reading,
so body copy is in Spline Sans and kept tight. A reviewer who wants a
"document" portfolio may find the app framing precious; that's the bet.

---

## Shared commitments across all five

- **Content fidelity.** Real name, real roles, real projects (Asian Paints
  dealer portal; Boost360 onboarding; Wikipedia / KaiOS; freelance selection),
  real agencies (Thence, Hureo), real years, the real client list. The only
  metrics used are the documented ones (+20% transactions; −60% uninstalls;
  $500K pre-seed for Turns; 4.8★ for LetsConnect). No invented numbers.
- **No real images.** Every visual surface is a labeled CSS/SVG placeholder
  — catalog grids, phone flows, keypad article views, collages, gauges,
  stat cards — communicating the *kind* of image that belongs there.
- **Self-contained.** Inline CSS, minimal inline JS (scroll-spy, active nav,
  one live clock). Only external request is Google Fonts, each with a system
  fallback stack so files render offline.
- **Accessibility baseline.** Visible focus, `prefers-reduced-motion`
  honored (cursor blink and transitions disabled), semantic landmarks
  (`header/nav/main/section/article`), sufficient contrast on each palette.
- **Distinctness.** Five different layout systems, five personalities, five
  type voices (Fraunces serif; Newsreader + Caveat hand; Space Grotesk
  technical; Bricolage bold; JetBrains Mono console), five palettes, and five
  interaction models (living index; tabbed notebook; static drawing;
  scroll-spy spreads; app console). No two look like the same designer in
  the same mood.
