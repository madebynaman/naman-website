# Gemini 3.5 Flash — Portfolio Homepage Redesigns

This directory contains five distinct design directions for Naman Sharma's Product/UX Design portfolio homepage. All files are fully self-contained HTML templates using inline CSS and pure vanilla JavaScript (with external fonts loaded from fonts.google.com).

---

## d1: The UX Blueprint

### Concept
A technical, grid-based layout mirroring an engineering blueprint. It emphasizes Naman's computer engineering background, logical mindset, and systematic design execution.

### Key Design Decisions
- **Typography:** Space Grotesk (geometric/expressive headings) paired with JetBrains Mono (monospaced structure).
- **Color Palette:** Deep Slate Charcoal (`#0b0f19`) base, stark slate gridlines, and a glowing Sky Cyan (`#38bdf8`) accent.
- **Key Layout:** Fixed left sidebar navigation on desktop for persistent section coordinates, with a tabular timeline.
- **Interactive Signature:** An "Interactive System Specs" block that allows hiring managers to click through Naman's stacks, tools, and principles as if browsing a software configuration dashboard.

### Trade-offs
- Maximize technical density at the cost of warm, organic storytelling.
- High visual structure (lines, metrics, boxes) might feel overly clinical to non-technical recruiters.

---

## d2: The Sage Chronotype

### Concept
An elegant, spacious, storytelling-first layout reminiscent of premium print journalism. It frames Naman as a mature product strategist who prioritizes plain speech over industry buzzwords.

### Key Design Decisions
- **Typography:** Fraunces (serif for headings/manifestos) paired with Instrument Sans (clean sans-serif body).
- **Color Palette:** Muted Sage Green (`#f1f5f2`) base, off-white card fills (`#fcfdfd`), and a subtle Sand Rose (`#8e6c58`) accent.
- **Key Layout:** Centered single-column layout with generous whitespace, large pull-quotes, and asymmetrical spacing to control reading speed.
- **Interactive Signature:** The "Anti-Jargon Converter" — an interactive manifesto text where common marketing buzzwords are struck through and can be clicked/hovered to reveal Naman's direct translations.

### Trade-offs
- Low-density layout means a longer page scroll.
- The editorial serif tone targets senior design leaders and executives, which might feel slow or verbose to recruiters looking for rapid bullet points.

---

## d3: The Curious Workspace

### Concept
A friendly, energetic, card-based interface focused on Naman's profile as a "no drama, curious generalist." It incorporates his personality hooks (dog Jerry, hip-hop, gaming) to create an immediate human connection.

### Key Design Decisions
- **Typography:** Lexend (rounded, friendly geometric display) paired with DM Sans (clean, standard body).
- **Color Palette:** Lavender Chalk (`#f5f3ff`) base, crisp white card containers, and a warm Amber (`#f59e0b`) accent.
- **Key Layout:** A central tabbed explorer component allowing the user to click between "Selected Work", "Core Ethos", "Log Timeline", and "Write Naman" in one clean viewport space.
- **Interactive Signature:** "Jerry the Mascot Tip" — a floating badge of Naman's dog Jerry. Hovering over different project cards triggers Jerry's speech bubble to display humorous, context-specific UX audits.

### Trade-offs
- Rounded borders and lavender hues trade away traditional "corporate" seriousness.
- Tab-based progressive disclosure requires active user interaction to see all data, rather than offering a standard long scroll layout.

---

## d4: The Metrics Terminal

### Concept
A stark, high-contrast, maximum-density dashboard. It is optimized for busy hiring directors who want to examine raw business telemetry, role details, and research outcomes with zero friction.

### Key Design Decisions
- **Typography:** DM Sans (functional body) paired with Fira Code (monospaced data tags).
- **Color Palette:** Obsidian Black (`#090d10`) base, Charcoal panels (`#111418`), and high-visibility Signal Green (`#10b981`) metrics.
- **Key Layout:** Desktop split-pane view: a pinned left sidebar showing the resume/logs/contact info, and a scrollable right panel showing project outcomes.
- **Interactive Signature:** "The Impact Filter Matrix" — an interactive filter system at the top of the workspace. Users can filter projects instantly by impact type (Conversions, Retention, Research).

### Trade-offs
- Low visual ornamentation, prioritizing absolute utility.
- Pinned split-pane layout can feel cramped on medium-sized screens (resolved via breakpoint wraps to standard column layouts).

---

## d5: The Tactile Dark

### Concept
An ultra-premium, quiet luxury dark layout highlighting visual refinement and smooth micro-animations. It targets brands that value high-end visual execution, tactile polish, and delightful craft.

### Key Design Decisions
- **Typography:** Outfit (sleek, futuristic display) paired with Plus Jakarta Sans (premium sans-serif).
- **Color Palette:** Espresso Slate (`#121110`) base, glowing background layers, and metallic Burnished Copper (`#c29b70`) accents.
- **Key Layout:** Wide horizon-based containers, full-bleed header with smooth gradient backdrops, and thin dividers.
- **Interactive Signature:** "Tactile Process Slider" — a horizontal timeline showing Naman's 6-step iteration loop. Clicking on any stage reveals specific methodology outcomes with slide-in animations.

### Trade-offs
- Dark espresso theme is highly dependent on clean screen contrast and rendering.
- Requires slight layout padding overhead to maintain a spacious, luxury aesthetic, reducing text scannability.
