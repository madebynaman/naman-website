# MiMo V2.5 — Design Directions

## d1 — The Type Grid

**Concept:** Brutalist editorial — a design magazine spread as a portfolio. Heavy serif headlines, dense grid, black/white with a single red accent. Numbers and rules as structural elements.

**Key design decisions:**
- Massive `Instrument Serif` headlines at 90–140px create instant visual impact and signal design confidence — the kind of type that makes hiring managers stop scrolling.
- Two-column grid with heavy rules gives a newspaper/magazine feel that handles density well across a long page. Every section has clear visual boundaries.
- Numbered sections (01–04) with oversized numerals encode progression without being decorative — they give the reader a map of the page.
- Work metrics (20%, 60%, $500K) displayed as large data points in the hero create immediate credibility before the reader scrolls.

**Trade-offs:**
- Brutalist aesthetics can feel cold or aggressive to some reviewers. The warm cream background (#F5F0EB) softens this, but the direction deliberately sacrifices warmth for editorial authority.
- Dense grids work best on desktop. The responsive fallback is functional but loses the magazine-spread quality.

---

## d2 — Ink & Paper

**Concept:** Warm, tactile craft — like a physical portfolio laid on a table. Cream backgrounds, hand-drawn SVG accents, serif/display pairing, earth tones (terracotta, olive). Rounded cards with soft shadows.

**Key design decisions:**
- `Playfair Display` + `DM Sans` pairing creates a classic/editorial feel without being cold. The italic display face adds personality and warmth.
- Rounded cards with subtle hover transforms give a tactile, interactive quality — each project feels like a physical card you could pick up.
- Hand-drawn SVG doodles (circles, curves) at low opacity add craft without clutter. They signal "this person cares about details" without demanding attention.
- Tag-based metadata (role, year, skills) with pill-shaped borders feels organized and scannable — a designer's portfolio should demonstrate information design.

**Trade-offs:**
- This direction leans into a more traditional portfolio aesthetic. It's safe but polished — the warmth trades edge for approachability.
- The card-based layout is well-worn territory. The hand-drawn accents and deliberate type pairing are what differentiate it from a generic template.

---

## d3 — Terminal

**Concept:** Dark mode code-editor aesthetic. Monospace type, terminal windows, repos as work items, process as pseudocode. Speaks to Naman's CS background and technical fluency.

**Key design decisions:**
- `JetBrains Mono` as the primary face signals technical credibility without being a gimmick — it's what developers actually use, not a "hacker font" stereotype.
- Work items framed as GitHub repos (with repo names, language tags, stat dots) speaks the language of product teams and engineers. It says "I understand how you work."
- The hero terminal window with real commands (`cat about.md`, `ls highlights/`) is a functional intro that communicates the same information as a traditional hero but through a lens that resonates with technical stakeholders.
- Case studies as pull requests with "merged" badges reframe design work as engineering-adjacent collaboration — this portfolio would land well at a dev-forward company.

**Trade-offs:**
- The terminal aesthetic is polarizing. Some reviewers will find it gimmicky; others will see it as the most authentic expression of a CS-background designer.
- Monospace type at body size is less readable than proportional fonts for long-form text. The direction accepts this trade-off for cohesion.

---

## d4 — Mosaic

**Concept:** Bold contemporary — asymmetric masonry layout with large color blocks, geometric shapes, and a vibrant palette (coral, teal, purple, navy). Overlapping elements and dynamic spacing.

**Key design decisions:**
- Asymmetric masonry layout breaks the grid deliberately — it feels dynamic and confident, like a designer who doesn't need to play it safe.
- Four-color palette (coral, teal, purple, navy) gives visual richness without chaos. Each color maps to a type of content (coral = metrics, teal = process, purple = visual, navy = text).
- Rounded blocks with bold metrics (20%, 60%, $500K) as standalone visual elements create "stopping points" — the eye catches a big number, then reads the context.
- Process displayed as six equal-width pills with color-coded top borders feels modern and scannable — a departure from the typical numbered list.

**Trade-offs:**
- The vibrant palette and dense layout risk feeling busy. The direction leans into maximalism deliberately — it trades restraint for energy.
- Masonry layouts are harder to control across screen sizes. The responsive fallback collapses to single-column, losing the mosaic quality.

---

## d5 — Whisper

**Concept:** Ultra-minimal — huge whitespace, thin hairline rules, small refined type, muted palette with a single soft blue accent. Refined, quiet confidence.

**Key design decisions:**
- `Cormorant Garamond` (light weight) + `Karla` pairing is intentionally understated. The serif face at 300 weight feels editorial without shouting — it says "I don't need to prove anything."
- Work items as simple list rows with metadata on the left, description in the center, and a single metric on the right — maximum information density with minimum visual noise.
- Process grid uses 1px borders as dividers (not cards, not backgrounds) — the grid itself is the structure, not decoration. This is form following function at the layout level.
- Muted blue accent (#6B8FA3) is used sparingly — only for links, italics, and section labels. It creates a through-line without dominating.

**Trade-offs:**
- Ultra-minimal design is the hardest to execute well. Every pixel of whitespace, every font size, every border weight carries weight. This direction is the most unforgiving of mistakes.
- The quiet aesthetic may not grab attention in a side-by-side comparison with bolder directions. It trades impact for sophistication — a reviewer who appreciates restraint will love it; one scanning quickly might overlook it.
