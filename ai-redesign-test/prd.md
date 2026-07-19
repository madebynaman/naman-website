# PRD — AI Redesign Test (Portfolio)

An evaluation exercise: multiple AI models each redesign a single long-form
portfolio homepage for **Naman Sharma — Product/UX Designer** — to compare their
product-management and design skills. The output lets a human reviewer compare,
side by side, how well each model understands the person and how strong its
visual design judgment is. Work happens exclusively in
[`ai-redesign-test/`](./).

**Priority:** standalone experiment. This test must not depend on, modify, or
integrate with the rest of the `website/` Astro project.

## Goal

Each participating model produces **5 unique, distinct design directions** for
**one portfolio homepage** — a single, dense, multi-section long-scroll page
that introduces Naman, his work, his thinking, and his value, end to end. The
goal is a wide variety of homepage directions so the human reviewer can pick
the strongest section concepts and language from across them and expand those
into a full site later. The bar is world-class: beautiful, distinctive,
intentional, next-level UI — not a templated personal-site skeleton with a name
swapped in.

## Why a long homepage (not a full site)

The homepage is the highest-leverage screen of a portfolio: it has to do
everything — hook a stranger, communicate who you are, show range, handle
density, and route to deeper work. A single long page that contains a wide
variety of sections (intro, selected work, process, case-study teasers, about,
writings/speaking, contact, footer, and more) is the richest single artifact to
judge a model's design judgment on. Reviewers will harvest the best sections and
section-language from across the 5 directions per model, then expand the winners
into the rest of the site. **Do not build multi-page navigation, routing, or
separate routes** — one long page per direction, anchor-linked internally.

## Participants

The completed test includes one folder per model under `ai-redesign-test/`:
`deepseek-v4-flash`, `deepseek-v4-pro`, `fable`, `gemini-3.1-pro`,
`gemini-3.5-flash`, `glm-5.2`, `gpt-5.5`, `gpt-5.6-sol`, `gpt-5.6-terra`,
`grok-4.5`, `kimi-k2.6`, `mimo-v2.5`, `minimax-m3`, `opus-4.8`,
`qwen3.7-max`, and `sonnet-5`.

All 16 participants have submitted their five directions and rationale README,
for 80 completed directions total.

## Deliverables (per model)

Inside the model's own folder (e.g. `ai-redesign-test/fable/`):

1. **Five HTML files**, named `d1-<model>.html`, `d2-<model>.html`,
   `d3-<model>.html`, `d4-<model>.html`, `d5-<model>.html`
   (e.g. `d1-fable.html`). Each is one complete long-form homepage direction.
2. **One `README.md`** with a short rationale per direction — five sections
   (`d1`–`d5`), each naming the direction's concept, the key design decisions,
   and the trade-offs accepted. Brief and concrete; no marketing prose.

Nothing else. No build tooling, no package.json, no asset folders.

### HTML requirements

- **Fully self-contained, with one exception:** inline CSS (and inline JS only
  if a direction needs light interactivity). No external requests — no CDN
  scripts, no remote images — **except Google Fonts**: any typeface from
  [fonts.google.com](https://fonts.google.com) may be loaded via the standard
  `<link>` embed; there is no system-fonts-only restriction. Each font should
  still declare a sensible system fallback stack so the file degrades gracefully
  offline. Everything else must render completely when opened via `file://`.
- **No frameworks, no build step.** Plain HTML/CSS(/vanilla JS). Astro, React,
  Tailwind, component libraries, and any build tooling are explicitly out of
  scope and out of bounds for this test.
- Desktop-first is fine; a personal portfolio is a desktop-first context.
  Graceful behavior at narrower widths is a plus, not a requirement.
- **Realistic content drawn from the source documents** — your name, real
  roles, real projects, real case-study context, real dates, real clients —
  no lorem ipsum, no `Project 1/2/3` filler, no invented company names where the
  documents supply real ones. Where the documents are silent on a detail, invent
  plausible-but-clearly-aesthetic placeholder copy aligned with the persona; do
  not invent verifiable career facts.
- **Use placeholder visuals, not real images.** Real screenshots, photos, and
  case-study imagery will be dropped in by the human reviewer later, so do not
  attempt to source or reference real assets. Build every visual surface as a
  deliberate placeholder: CSS-drawn mockups, abstract gradient/shape blocks,
  labeled wireframe-style frames, typographic collages, or inline SVG — anything
  that holds the layout's weight and communicates the *kind* of image that
  belongs there (e.g. "case-study hero — Asian Paints dealer portal", "project
  mockup — Boost360 onboarding flow"). Keep placeholders intentional and
  on-brand for the direction; a visible `<img>` broken-link or a blank box is a
  failure. Do not use external images, stock photo URLs, or base64 blobs to fake
  real photography.

## Process requirements (per model)

- **Use the `frontend-design` skill** before designing. This is mandatory — the
  point of the test includes how well the model directs its own aesthetic
  choices.
- Read the product context first (see below). Directions that misunderstand who
  Naman is and what the portfolio is for fail regardless of polish.
- The five directions must be genuinely distinct from each other — different
  layout systems, personalities, typographic voices, or interaction models —
  not one design with five color swaps. Five real bets beat five minor
  variations of one safe idea.
- **Work in resumable chunks.** Usage limits may cut a session short, so
  complete and save one coherent piece at a time (e.g. one direction fully,
  then the next) rather than holding everything in flight. If needed, a model
  may keep a single progress file — `progress.md` inside its own folder —
  noting what is done and what remains, so a fresh session can pick up
  mid-task. That file (deleted or left) doesn't count against the deliverables
  list.

## Design constraints: free rein

This test deliberately places **no design restrictions** on the models. There
is no house style, no brand lock, no color palette, no typography spec, no grid
system, no design principles document to conform to. Each model invents its own
brand direction, palette, typography, voice, and layout system from the source
documents alone.

**Full creative liberty.** Models are encouraged to go wild: unconventional
layouts, strong aesthetic points of view, experimental interaction models,
editorial and brutalist and maximalist and quiet-luxury and everything-in-
between directions are all welcome. There is no penalty for boldness — the only
two tests a direction must pass are *good design* and *good product*. Safe,
conservative variations of one idea are worth less than five genuinely
different bets, even if some of those bets are risky.

No two directions from the same model should look like they came from the same
designer in the same mood.

## Product context (binding — read before designing)

Models must read the two context files in `ai-redesign-test/` before
designing:

- `resume.md` — full career history, skills, tools, and "ask me about" hooks.
- `portfolio-content.md` — full portfolio narrative: intro, principles,
  process, career timeline, and four case studies with problems, research,
  solutions, and business impact.

These markdown files are the canonical source for this test. They are
**read-only inputs** — do not edit them or reproduce them verbatim inside
your output.

Directions must be built on what these documents actually say. Product facts
every direction must respect (read the documents to confirm and expand on
these — the bullets are a floor, not a ceiling):

- Naman is a **Product / UX designer**. The portfolio is a professional portfolio
  whose job is to win him work and respect from hiring managers, recruiters,
  design leads, and peers — not a personal diary or a generic dev showcase.
- His portfolio leans on **real case studies and real outcomes** — informed by
  the projects, roles, and context in the documents. Tease case studies hard
  enough on the homepage that the reader wants the full story; do not fake
  metrics or invent numbers the documents do not support.
- Tone: credible, considered, design-literate. The portfolio should read as the
  work of someone who can hold a room with senior product and design people —
  not templated, not generic, not ego-project.
- The homepage must do a lot: introduce him, convey range and depth, surface
  selected work, give a sense of process and thinking, make contact frictionless,
  and leave a strong aftertaste.

## Hard boundaries (non-negotiable)

1. Each model works **only inside its own folder**. The folder is at
   **`website/ai-redesign-test/<model>/`** — not a sibling folder in another
   repo, not anywhere else. The full absolute path for the working directory
   is `<repo-root>/ai-redesign-test/<model>/`. If you are unsure which repo
   contains the test, check the path above.
2. **Every other path in the repo and on the machine is read-only** — no edits
   to `website/src`, the Astro config, `package.json`, or anything outside
   the model's own folder. `resume.md` and `portfolio-content.md` are
   **read-only inputs**.
3. **Never touch another model's folder** — no reading, writing, listing, or
   inspecting sibling folders. Directions must be independent work, not
   responses to sibling folders. A model that touches another model's folder —
   even to read or list — is disqualified from the test.
4. No git operations: no commits, branches, staging, or history changes. The
   human reviewer handles version control.
5. No network dependencies in the output (see HTML requirements) — except
   Google Fonts.
6. Do not echo, log, or transcribe the full contents of `resume.md` or
   `portfolio-content.md` into your output files, README, or progress notes.
   Treat them as source material; design from them, do not dump them.
7. **Use the `frontend-design` skill before designing.** This is mandatory and
   non-negotiable — the point of the test includes how well the model directs its
   own aesthetic choices. A direction produced without having loaded and
   followed that skill does not count as a deliverable.

## Evaluation criteria (for the human reviewer)

Not instructions to the models — this is how the output will be judged:

1. **Product understanding** — does the homepage reflect who Naman actually is
   and what a portfolio is for, or is it a generic personal-site template?
2. **Visual quality** — is the design genuinely distinctive and world-class, or
   templated defaults with a coat of paint?
3. **Information hierarchy** — density handled with structure and progressive
   disclosure across a long page, not sparseness or clutter.
4. **Usability** — legibility, scannability, sensible affordances; accessibility
   care (contrast, non-color status signals) counts in favor.
5. **Distinctness of the five directions** — five real ideas, not one idea five
   ways.
6. **Case-study teasing** — does the homepage sell the deeper work without
   faking it?
7. **Rationale quality** — does the README show deliberate trade-off thinking?

## Out of scope

- Astro, React, Tailwind, component libraries, or any integration with the wider
  `website/` project.
- Multi-page sites, routing, or full case-study pages. One long homepage per
  direction; everything else is a later expansion by the human reviewer.
- Mobile layouts, dark mode, white-labeling, i18n.
- Promoting any direction into the real site — that is a separate, later
  decision by the human reviewer.
