# MiniMax M3 — AI Redesign Test

Five design directions for a single long-form portfolio homepage for
**Naman Sharma, Product/UX Designer** (Jaipur, IN). Each file in this folder
is one complete, self-contained long-scroll homepage — no build step, no
external assets beyond Google Fonts.

## How to read this

Open any `dN-*.html` file directly via `file://`. The companion `progress.md`
in this folder tracks build order and notes for resuming a partial session.

The five directions are deliberately not five colour swaps of the same idea.
They sit at five different points in the design space:

| # | Codename | Voice | Density | Risk |
|---|----------|-------|---------|------|
| d1 | Founder Letter | Quiet, conversational, reading-first | Low | Reads as a website, not a letter |
| d2 | Spec Sheet | Engineering, dry, precise | High | Cold / "designer as a system" cliché |
| d3 | Indie Zine | Personal, maximalist editorial | High | Visual noise over clarity |
| d4 | Bento Studio | Structured, modern, calm | Medium | Bento-as-default look |
| d5 | Poster Series | Loud, swiss-punk, typographic | Medium | Too loud for a portfolio |

Each direction is paired with a "why this for Naman" — the connection from
the source documents to the design choice. The "Jerry" signature is
intentional: the source portfolio ends with *"Jerry says hi!"*, so a dog
recurring across the page is a Naman-specific move, not a stock device.

## d1 — Founder Letter

**Concept.** The page is a letter to a hiring manager, not a marketing site.
Single column, ~640px reading measure, generous line-height, sticky left
scroll-rail for orientation, marginalia in the right gutter.

**Key decisions.**
- Body: Source Serif 4 (variable, characterful, not the default cream+terracotta serif).
- Marginalia: JetBrains Mono labels; Jerry paw SVG appears at section transitions.
- Principles rendered as side-rail notes (not numbered — they aren't a sequence).
- Process *is* a sequence, so 01–06 is appropriate there.
- Case studies presented as numbered "figures" with a small wireframe placeholder
  per project (dealer-portal wireframe, three-phone onboarding, research affinity cluster).
- Yellow accent reserved for Jerry + emphasis, never decoration.

**Trade-off accepted.** Reading-first means case-study visuals get less real
estate than in d2/d4. A hiring manager who skims will miss detail. The bet is
that the ones who *read* are the ones worth having.

## d2 — Spec Sheet

**Concept.** The portfolio as a technical datasheet: "naman_sharma / Product_UX_Designer / v3.2".
Engineering voice, dense data, version-controlled, with a live "system status"
pulse in the top bar.

**Key decisions.**
- Type: IBM Plex Sans + IBM Plex Mono. Strict engineering register throughout.
- The "system status" pulse is the signature — a literal `0A86B` status
  dot with an expanding ring animation, in the top bar, "All systems operational".
- Performance metrics are presented as four big numbers from real outcomes
  (no invented metrics): +20%, −60%, ~30m, $500K. Each has a source.
- Career rendered as a `git log` of commits with hashes, dates, and tag types
  (`new`, `feat`, `fix`).
- Modules = case studies. Each is a labeled `FIG. 01`–`FIG. 04` with a small
  engineering schematic placeholder.
- Contact framed as `Inputs accepted` and `Endpoints` — API-style honesty.

**Trade-off accepted.** The cobalt-blueprint register can read as "engineering
blog" rather than "designer." The mitigation is the warmth of the personal
copy inside each module ("a UX problem hiding inside a positioning problem")
and the `v3.2` versioning that undercuts any pretense of being an actual
production system.

## d3 — Indie Zine

**Concept.** The page is a personal design zine — *Issue 01, Summer 2026*.
A real magazine cover, masthead, contents page, editor's letter, three feature
spreads, an interview, classifieds, and a colophon.

**Key decisions.**
- Type: Fraunces (variable, with `SOFT` axis for warmth), Inter, Caveat (handwritten),
  Space Mono.
- Palette: cream-rose paper, deep forest green, mustard, ink — with terracotta
  reserved for the rose accent. Deliberately *not* the cream+terracotta default,
  rose + forest is the differentiator.
- Jerry is promoted to *contributor*. His notes are mustard/rose/green sticky
  notes taped into the gutter with a small "tape" SVG on top.
- Each case study is a full magazine feature with a cover-art placeholder
  (portal wireframe in a green/mustard block, four-phone onboarding, an
  affinity cluster of stickies around a "Why JioPhone?" core).
- Principles rendered as an *interview* between the editor and the subject,
  with the question on the left and the four answers as a column on the right.
- Tools are presented as a "classifieds" page, twelve little ads in a 4×3 grid.

**Trade-off accepted.** Maximalist editorial is easy to over-design. The
discipline here is that every "tilt," "tape," and color block is a deliberate
element with meaning (Jerry's color, the section color, the dept color), not
random chaos. The interview framing for principles is the structural move
that keeps the editorial energy from dissolving into noise.

## d4 — Bento Studio

**Concept.** The page as a working studio: a bento grid of cards that
introduce everything at once, followed by long-scroll detailed case studies.
The signature is a persistent **"Now: Available for freelance, Q3 2026"**
pill in the top bar with a live pulse — and a "Current focus: Re-learning to
code" card on the bento itself.

**Key decisions.**
- Type: Inter (geometric, modern) for body, Instrument Serif for one or two
  display moments in the hero card.
- Palette: sage `#9CA889`, cream `#F4EFE6`, coral `#FF6B4A`, ink — sage is
  the deliberate departure from the typical bento template (which usually
  leans monochrome or warm-only).
- The hero is a 6-column, multi-row bento: 1 large intro card, 1 coral status
  card, 1 ink "current focus" card with a progress bar, 3 case-study cards with
  tiny in-card placeholders, 1 clients card, 1 tools card, 1 "ask me about" card.
- After the bento, the same three case studies get full-detail sections.
- Principles are a 2×2 grid with mixed card treatments (default, sage, coral, ink).
- Career is a clean list with sage-org tag and a "where" column.

**Trade-off accepted.** Bento is the trendy 2024 look. The differentiation
move is the sage palette + coral accent (instead of the usual mono-cream
or warm-cream) and the *content* of the bento cards: each card has a real
sentence of copy and a real metric, not just a label.

## d5 — Poster Series

**Concept.** The page as five full-bleed typographic posters: a 1970s
editorial-poster series in the spirit of Müller-Brockmann with punk attitude.
Each poster takes a viewport. The signature is a **massive rotated
"NAMAN/"** wordmark in the hero and a live **"01/05" section counter**
fixed to the right edge that ticks as you scroll.

**Key decisions.**
- Type: Archivo Black (display), Space Grotesk (body), Space Mono (captions).
  All high-impact, all readable.
- Palette: paper white, ink, hot red-orange `#E8341A`, deep purple `#2D1B4E`,
  yellow accent. Each poster is a different treatment of the same five colors
  — P1 paper hero, P2 ink-on-paper, P3 paper with purple display, P4 full red,
  P5 ink with red callout.
- The page is structurally five full-bleed sections, each anchored to a
  case study or the contact section, with the 01/05 counter and a vertical
  `01/ 02/ 03/ 04/ 05/` jump nav in the top bar.
- The "image" for each case study is a typographic poster of its own — a
  portal wireframe framed in a red border on the ink poster, four phone
  mockups in a purple poster, a yellow meta-strip of study numbers on the
  red research poster.
- The research poster also contains the four principles, in yellow-on-red
  cards — the thinking section lives inside the research poster, which
  makes a rhetorical point: research *is* the thinking.

**Trade-off accepted.** Loud, full-bleed typography is not for every hiring
manager. The bet is that the same design hires well in two opposite
directions: bold companies who want signal, and quiet companies who want
proof the designer can hold a point of view.

## Cross-cutting choices

- **No real images.** All "case study" placeholders are CSS-drawn: a portal
  wireframe, three-phone onboarding flows, an affinity cluster. This honors
  the PRD — the human reviewer will drop real assets in later.
- **No invented metrics.** The numbers shown (`+20%`, `−60%`, `~30m`, `$500K`,
  `25` interviews, `3` cities) are all from the source `portfolio-content.md`.
  No `Project 1/2/3` filler, no lorem ipsum.
- **Jerry everywhere, but never as a stock device.** Jerry shows up in d1
  (marginalia footnotes), d2 (the live status metaphor — "supervises
  correspondence"), d3 (promoted to contributor with sticky notes), d4
  (a handwritten ask-card and a paw emoji in the signoff), d5 (the "Hello,
  stranger!" sticker and the "with Jerry nearby" signoff). The consistency
  is the joke, and it's grounded in the source.
- **No frameworks, no build, no Tailwind, no remote images.** Plain HTML +
  inline CSS, with a few lines of vanilla JS where interactivity helps
  (scroll progress, active-nav highlight, section counter tick).
- **Desktop-first, with graceful narrow-width fallbacks.** Bents collapse,
  grids stack, marginalia hides. The PRD's "graceful at narrower widths is
  a plus" is honored without re-engineering for mobile.
- **Reduced motion respected.** The two motion moments that exist
  (d2's pulse, d4's pulse, d5's pulse) all disable their `animation` under
  `prefers-reduced-motion: reduce`.

## Files

- `d1-minimax-m3.html` — Founder Letter
- `d2-minimax-m3.html` — Spec Sheet
- `d3-minimax-m3.html` — Indie Zine
- `d4-minimax-m3.html` — Bento Studio
- `d5-minimax-m3.html` — Poster Series
- `README.md` — this file
- `progress.md` — build-order notes (deleted or kept per session)
