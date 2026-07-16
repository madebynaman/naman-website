# Qwen 3.7 Max — Design Directions

## d1: The Evidence Board

**Concept:** A detective's investigation board. Naman's case studies are pinned evidence cards on a cork surface, connected by red string. The portfolio becomes a case file — the designer as investigator.

**Key decisions:**
- Cork-textured background with CSS noise and gradient layering to create tactile warmth
- "Special Elite" typewriter font for display type — reinforces the case-file/document aesthetic
- Cards are slightly rotated with tape and pin details, creating a physical, hand-placed feeling
- Metrics are highlighted with yellow marker-style badges — the "verdict" on each case
- About section presented as a "Subject Profile" dossier with field/value pairs
- Contact framed as "Open a Case" — extending the metaphor to the CTA

**Trade-offs:**
- The cork texture is heavy and may feel gimmicky at scale; it works for a single-page direction but would need toning down for a full site
- Card rotations reduce scannability slightly; prioritized atmosphere over pure readability
- The detective metaphor is strong for case studies but less natural for principles and process sections

## d2: The Signal

**Concept:** A broadcast/radio frequency aesthetic. Naman's work is a signal cutting through noise. Each project is a frequency with a signal-strength meter showing its impact. Deep indigo palette with electric coral and cyan accents.

**Key decisions:**
- Fixed grid background creates a technical, oscilloscope-like atmosphere
- "Space Grotesk" for display — geometric and modern, fits the broadcast/tech feel
- "JetBrains Mono" for labels and data — reinforces the technical instrument aesthetic
- Animated SVG waveform in the hero and static waveform dividers between sections
- Case study metrics shown as signal-strength bars — visual encoding of impact magnitude
- Process presented as a "Signal Chain" with connected nodes — input through output

**Trade-offs:**
- Dark background with bright accents is a common AI pattern; differentiated through the broadcast metaphor and waveform details rather than relying on color alone
- The signal metaphor stretches thin for the About section — "Transmitter Profile" is clever but slightly forced
- Animated waveform relies on CSS `d` property animation which has limited browser support

## d3: The Notebook

**Concept:** A designer's sketchbook. Graph paper background with ruled lines, a red margin line, hand-drawn borders, highlighter accents, and margin annotations. Design as a craft that starts with pencil on paper.

**Key decisions:**
- Graph paper created with repeating CSS linear gradients — no images needed
- Fixed red margin line on the left edge — authentic notebook detail
- "Caveat" handwritten font for display type — feels like actual handwriting
- Highlighter effects via semi-transparent yellow/pink backgrounds behind text
- Case study results in pink highlighter badges with slight rotation
- Margin notes rotated 90 degrees — a detail that sells the notebook illusion
- Process steps in hand-drawn boxes with alternating slight rotations

**Trade-offs:**
- The handwritten font sacrifices some readability for personality; body text uses "Nunito" for legibility
- Graph paper lines at 32px intervals may not align perfectly with all content heights
- The left margin reduces usable width; on narrow screens the margin notes are hidden
- Sketch aesthetic could feel juvenile if not balanced with professional content — mitigated by using real case study data and metrics

## d4: The Layer Cake

**Concept:** Bold horizontal color-blocked strata. Each section is a full-bleed band in a different color — deep teal, warm sand, soft coral, midnight blue, cream. The page reads as geological layers of expertise.

**Key decisions:**
- Five distinct color bands create strong visual rhythm and clear section boundaries without dividers
- "Space Grotesk" + "DM Sans" + "IBM Plex Mono" — three-type system with clear hierarchy
- Hero uses a two-column grid: identity on the left, key metrics as stat cards on the right
- Each work card has a gradient visual header color-coded to match its layer's palette
- Process section on coral background with circular icon steps — warm and inviting
- Principles on midnight blue with large numbered cards — dramatic contrast shift
- Teal bookends (hero and contact) create visual cohesion

**Trade-offs:**
- Full-bleed color bands are bold but can feel heavy; each band needs enough content to justify its visual weight
- The sand-colored work section has lower contrast for text — used darker card backgrounds to compensate
- Color blocking is a known pattern; differentiated through the specific palette choices and the stat-card hero layout
- Six-column process grid may be cramped on smaller screens; collapses to 2-column on mobile

## d5: The Conversation

**Concept:** A dialogue format. Each case study is presented as a conversation — the problem speaks on the left, the solution responds on the right, connected by a vertical timeline. Design as a dialogue between designer and problem.

**Key decisions:**
- "Playfair Display" serif for display type — editorial, literary quality
- "Work Sans" for body — clean, modern complement to the serif
- "Fira Code" for labels — adds a technical precision note
- Vertical timeline with dots at each dialogue junction — structural spine of the page
- Problem/solution split with color-coded voice labels (rose for problem, sage for solution)
- Hero uses italic serif for the thesis statement — sets the conversational, literary tone
- Principles as colored quote cards with large ghosted numbers
- Contact framed as "Continue the Conversation" — extending the metaphor
- Pill-shaped contact links — soft, approachable

**Trade-offs:**
- The two-column dialogue format is the most content-dense layout; requires careful reading order
- The vertical timeline line may not perfectly connect dialogue dots at all viewport widths
- Playfair Display is a popular serif choice; the italic usage and specific pairing with Work Sans differentiates it
- The conversation metaphor works best for case studies (problem → response) but is less natural for process and about sections
- Lighter overall palette may feel less "premium" than darker directions — intentional choice for warmth and approachability