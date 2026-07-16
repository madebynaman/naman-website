# Kimi k2.6 — Design Directions

## d1 — Field Notes

**Concept:** A UX researcher's field notebook. Warm, tactile, editorial.

**Key decisions:**
- Parchment palette with terracotta and moss accents to evoke paper, ink, and outdoor research.
- Cormorant Garamond paired with Inter and JetBrains Mono for a scholarly-but-modern voice.
- "Pinned note" cards with CSS pinheads and tape effects as the signature element.
- Left-margin annotations on desktop that label sections like notebook margin notes.
- Stamped date markers and dashed borders on case-study visuals to evoke field documentation.

**Trade-offs:**
- The warm palette is distinctive but risks feeling "safe" if not pushed. The slight rotations and pin details are the edge.
- Margin annotations collapse on mobile; the design degrades to a centered layout without losing hierarchy.
- The editorial density could feel cluttered; whitespace is intentionally generous between sections to compensate.

## d2 — System

**Concept:** A well-designed operating system / design system documentation. Brutalist-leaning, engineering-minded.

**Key decisions:**
- Strict grid, zero border-radius, border-heavy cards that look like system modules or terminal windows.
- Space Grotesk + IBM Plex Mono to speak to Naman's CS background and current re-learning to code.
- Terminal-style hero with a typing animation cursor and command-line structure.
- Systematic section IDs (SYS.01, MOD.01) that encode information about the content hierarchy.
- Process flow as a connected node diagram — encoding sequence visually.

**Trade-offs:**
- The monospace-heavy aesthetic can feel cold. Inter is used for longer reading passages to soften it.
- The dense, utilitarian layout risks looking like a documentation site rather than a portfolio. The terminal hero and module status dots add personality.
- Desktop-first by design; the strict grid collapses gracefully to a single column on narrow widths.

## d3 — Growth

**Concept:** Design as a living, growing thing. Fluid, organic, maximalist.

**Key decisions:**
- Living CSS gradient blobs with `border-radius` morphing animations as ambient atmosphere.
- Organic card shapes with asymmetric border-radius (24px 8px 32px 16px) that feel hand-formed rather than machine-cut.
- Playfair Display + DM Sans for an elegant-but-readable voice.
- Nature metaphors throughout: "The Garden" for work, "Growth Rings" for process, "Root System" for principles, "Seed Packet" for contact.
- Sage, forest, coral, sand palette drawn from natural landscapes.

**Trade-offs:**
- The blob animations are computationally light (CSS only) but could be distracting. Opacity is kept low (0.4–0.5) to maintain subtlety.
- Maximalist organic shapes risk feeling chaotic. An underlying grid keeps the layout rational even when the surfaces break it.
- The nature metaphor could feel twee if overdone. It's used as section language, not decoration.

## d4 — Studio Wall

**Concept:** A physical studio wall — mixed-media collage, creative chaos organized by an underlying grid.

**Key decisions:**
- Masonry-style grid with overlapping elements, slight rotations, tape effects, and layered shadows.
- Syne as the display face for its characterful, almost hand-drawn quality.
- Polaroid frames, sticky notes, and pinned cards as the signature visual system.
- The wall mixes work artifacts (case studies), research insights (sticky notes), and process maps in one dense collage.
- Dot-grid background texture at low opacity to evoke a physical studio surface.

**Trade-offs:**
- Collage layouts can sacrifice scannability. The underlying 12-column grid and consistent card structures preserve hierarchy.
- Rotations and tape effects are CSS-only but could feel gimmicky. They are kept subtle (±1–2 degrees) and consistent.
- The creative-chaos aesthetic could understate the professional rigor of the case studies. Impact metrics and agency labels are preserved in high-contrast blocks.

## d5 — Sumi

**Concept:** Extreme Japanese-inspired restraint. Form follows function taken to its logical extreme.

**Key decisions:**
- Noto Serif JP used as the display face for its weight and character — a deliberate departure from Western serif defaults.
- Vast whitespace: 8rem section padding, narrow 720px container, single centered column.
- Vermillion (#E34234) used extremely sparingly — only for impact metrics, hover states, and the contact "seal."
- A fixed vertical brush-stroke line on the left edge (desktop only) as the signature connecting element.
- Japanese numerals (一, 二, 三...) for process steps to reinforce the concept without becoming decoration.
- Hairline rules and 1px borders as the only horizontal dividers.

**Trade-offs:**
- Extreme minimalism risks feeling empty rather than confident. Content density is preserved within each section; the whitespace lives between sections.
- The Noto Serif JP display face is readable but unfamiliar for Latin text. Inter is used for body copy to maintain legibility.
- The vertical brush line is decorative — it does not encode information. It was accepted as a pure aesthetic signature because the rest of the page is ruthlessly functional.
