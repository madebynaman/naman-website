# Naman Sharma: Portfolio Content (Rewrite)

> **Working doc for the website rewrite** · July 2026
> Built from `portfolio-content.md` + `resume.md` · Covers 2017 to 2026
> Status: v2 draft. Deliberately generous. Prune with the guide at the end.

**How to use this doc**

- Sections are in site order, top of page to bottom.
- Plain text is ready-to-paste copy.
- `[Visual: ...]` is the imagery that section needs.
- `{curly braces}` are placeholders for you to fill.
- `[NDA]` never goes public. Password-protected area only.
- `[Optional]` is first out when pruning.

**Two things to settle before any of this ships**

1. **Assets.** The layout is planned visual-first, and every photo and mockup on
   the checklist near the end is still unshot. Until that shoot happens the page
   cannot be built as written. There is a copy-forward fallback described with
   the checklist.
2. **NDA scope.** The source file is `NamanSharma_ProductUXDesigner_PortfolioNDA.pdf`,
   which suggests the whole portfolio was gated, not only the client work marked
   `[NDA]` here. Confirm with Hureo, and with Wikimedia if needed, that the KaiOS
   study can be named publicly. It is treated as public throughout this doc, and
   that is an assumption, not a fact. Asian Paints, NowFloats and Shiprocket are
   treated as private throughout.

---

## Voice rules (the whole site follows these)

- Short sentences. One idea per line. Plain words.
- Specifics over adjectives. "4.8★" beats "loved by users."
- First person. Contractions. Write like you talk.
- Playful, but not at one volume the whole way down. Warm in the hero and the
  personal sections, dry in the middle, straight inside the case studies.
- Not every section needs a punchline. Two or three across the page is plenty.
  More than that and the casualness starts to read as engineered.
- Banned words: passionate, delightful, delight, craft (as a verb), seamless,
  pixel-perfect, world-class, leverage, synergy, utilize, innovative,
  cutting-edge, "solutions".
- No em dashes. Use a full stop, a comma, a colon, or brackets.
- No claim without proof nearby: a metric, a story, or a quote.
- Never put quote marks around something a user did not actually say. A
  paraphrase is fine. A paraphrase dressed as a quotation is not.

---

# HOMEPAGE SECTIONS

## 1. Hero

Purpose: in five seconds a stranger knows who you are, what you do, whether
you're available, and likes you.

Headline options (pick one):

1. **I make complex products simple.**
2. **Complex problems in. Simple products out.**
3. **Hi, I'm Naman. I untangle complicated products.**

Sub (works with any option):

> I'm Naman Sharma, a product and UX designer. Designing since 2017, in UX
> since 2019. I help teams turn messy problems into products people actually
> understand. Based in Jaipur, working everywhere.

Availability line, directly under the sub:

> {One line, e.g. "Designing {thing} at {Company}. Open to freelance." or
> "Open to product design roles."}

Proof strip. Four numbers, set large, all public-safe:

- **$500K** pre-seed raised after the Turns website and brand revamp
- **4.8★** on the Play Store after the LetsConnect redesign
- **25** in-person interviews for the Wikimedia Foundation, across 3 cities
- **15+** clients since 2017

Buttons: **See my work** · **Say hi**
Small line underneath: *Always up for a good conversation.*

[Visual: large, warm photo of you. Real rather than corporate. Bonus points if
Jerry is in it.]

> Note: the Asian Paints 20% is a stronger number than three of these, and it
> stays out of the hero because that case study is behind the password. Don't
> let it leak up here by accident.

---

## 2. The no-jargon promise

Heading: **A no-jargon promise**

> Most designer portfolios promise to *synergize aesthetics with
> functionality* and *craft delightful experiences*.
> This one doesn't.
>
> I hate jargon. So, for the record, I do not:
> foster innovation through synergizing aesthetics and functionality ·
> navigate the confluence of form and function · orchestrate design
> revolutions · instigate paradigmatic evolutions · seamlessly integrate
> cutting-edge methodologies · engineer experiential marvels · champion
> transformative ideation in the ever-evolving design ethos · perpetuate
> narratives that transcend boundaries.
>
> Here's what I actually do:
> I listen to users. I sketch. I test. I simplify. I ship. Then I check if
> it worked.
>
> That's the whole trick.

[Visual: the jargon list styled with strikethrough, the "what I actually do"
list big and clean. This section is the copy. It needs no imagery.]

**Accessibility note, and it matters here more than anywhere else on the
page.** All the meaning in this section lives in the strikethrough. Screen
readers announce struck-through text as ordinary text by default, so a blind
visitor hears you sincerely claiming to orchestrate design revolutions. Wrap
the jargon in `<del>` and put a visually hidden "things I do not do:" ahead of
the list, so the negation survives without the styling.

---

## 3. Selected work

Section line:

> A few favourites. Short versions here. Ask me for the long ones.

### Card 1: Turns
Tag: Website · Brand · Design system
{one line on what Turns does}

**New website, new brand, new design system. They raised $500K pre-seed after
the revamp.**

[Visual: website mockup on laptop and phone.]

### Card 2: Wikipedia × KaiOS
Tag: Field research · 25 users · 3 cities

**25 in-person interviews for the Wikimedia Foundation, with JioPhone users in
Pune, Mumbai and Delhi.**
Tiny screens, real keypads, and for most participants the only
internet-connected device in the house.

[Visual: a JioPhone, field notes, an interview photo.]

### Card 3: LetsConnect
Tag: Mobile app · UX redesign
{one line on what LetsConnect does}

**Rebuilt the experience from user feedback. Now at 4.8★ on the Play Store.**

[Visual: before and after phone screens.]

### Card 4: Gadivan
Tag: 0 to 1 · Multiple apps
{one line on what Gadivan does}

**Designed the whole product from a blank page. Different apps for different
users, one system underneath.**

[Visual: family shot of the apps.]

### Card 5: [NDA] Two more, behind a password

> A dealer portal for one of India's largest paint companies. An onboarding
> rescue for a small-business app. Real numbers, real impact, both under NDA.
>
> **Leave your email and the password comes back automatically.** {email field}

> Why a field and not "ask me for it": this card reaches the reader at the
> moment they are most interested. Asking them to stop, open their mail client
> and compose a message loses most of them. If a form is too much to build, use
> a `mailto:` link with the subject line pre-filled so the ask costs one click.

[Visual: two blurred or locked mockups.]

[Optional] A slim "more work" list under the cards: Parentverse, Venyou,
Sharent, Spirinova, Gorico, RedShilliz, DGlobalist, Pahoti Wellness,
Ivy Malik, PhotoFinder, Olsub, Learn Theta, as plain text links.

---

## 4. How I work

Heading: **How I work**

> Six steps. The order matters more than the labels.

1. **Listen.** Users, founders, analytics, support tickets. Most of what I need
   already exists inside the company. It just isn't in one place yet.
2. **Map.** The full journey, end to end, until I can see where it breaks.
3. **Explore.** Go wide before narrowing. I would rather throw away ten
   directions than defend the first one.
4. **Refine.** Pick a direction and sweat the details.
5. **Ship.** Stay with engineering through the build, screen by screen, until
   it's live.
6. **Check.** Watch the numbers afterwards. Fix what moved, and fix what
   didn't.

[Visual: six small icons, or one simple horizontal diagram.]

---

## 5. Kind words

Heading: **Kind words**

Three short testimonials. Rules: specific beats glowing. One to three lines
each. Name, role, company.

1. "{Quote about what it's like to work with you, ideally with a number or a
   specific moment.}" {Name}, {Role}, {Company}
2. "{Quote about the quality of the work itself.}" {Name}, {Role}, {Company}
3. "{Quote about you catching or fixing something nobody asked you to.}"
   {Name}, {Role}, {Company}

Who to ask: a Turns founder, a Gadivan founder, your Thence design manager,
your Hureo founder, a LetsConnect stakeholder.

> When you ask, don't brief them on which of your principles to confirm. Ask
> what they remember about working with you and use whatever they say. A quote
> that happens to prove your own values page reads exactly like a quote you
> wrote yourself.

[Visual: quote marks, faces if allowed, otherwise just names.]

---

## 6. Designer who codes

Heading options: **A designer who codes** / **I design it, then I help build
it.**

> I have a computer engineering degree. For years I barely used it, and it has
> turned out to be one of the more useful things I own.
>
> It means I know what's expensive to build before I draw it, I can read the
> codebase instead of guessing, and engineers don't have to translate for me.
> When a handoff goes sideways, I can usually work out why on my own.
>
> I'm re-learning to code properly now, and I build with AI most days. This
> site is where that started: I gave the same brief to 16 AI models, got 80
> redesign directions back, and went through all of them to work out what I
> actually wanted. Useful exercise. The design decisions are still mine.

[Visual: a small terminal window, a code snippet, or a before and after of the
site itself.]

> Note on framing: the credential here is the engineering degree and being able
> to talk to engineers. The 16-model experiment is a story, not a
> qualification, and if it leads the section it invites the reader to wonder
> whether a model designed the page they're looking at. Keep it in third
> position, where it currently sits.

---

## 7. About me

Heading: **The longer version**

> I'm a self-taught designer with a computer engineering degree. Halfway
> through the degree I worked out that I liked designing products more than
> writing code, so I taught myself design properly: books, courses, YouTube,
> and a lot of bad early work.
>
> It started in 2017 with graphic design. Logos, posters, a board game, a kids'
> eBook. In 2019 I found UX research and never looked back. Since then I've
> done field research, usability testing, web apps, mobile apps, websites,
> brands, packaging, and social media graphics. Print and pixels and most
> things in between.
>
> I'm a curious generalist, and I think that's the useful part. Range lets me
> see the whole problem rather than only my corner of it.
>
> **Right now:** {current role, one line, e.g. "designing {thing} at
> {Company}"}. Living in Jaipur with Jerry. Reading {current book}, playing
> {current game}.

Keep that last paragraph to four lines and update it every few months. It's the
one part of the page that should look recently touched.

[Visual: two or three real photos. Working, a candid, one with Jerry. A photo
strip rather than a gallery.]

---

## 8. Jerry

Heading options: **Jerry** / **The real boss**

> Jerry is a four-year-old indie street dog, and the love of my life.
>
> I met him when he was four weeks old. He was malnourished, separated from his
> mother and litter, and far too young to survive on his own, so I brought him
> home. My parents took some convincing.
>
> He grew up stubborn, smart and deeply introverted, and he is extremely
> selective about who may pet him. If he ever lets you, take it as a five-star
> review.
>
> He's asleep next to my desk right now, supervising. He says hi.

Small caption under the photo: *Dogs rescued: 1.*

[Visual: one great photo of Jerry, or the two of you. This photo matters more
than any mockup on the site.]

---

## 9. Principles

Heading options: **What I believe** / **Four things I design by**

### Consistency beats talent
I'm not the most talented designer in the world. I show up every day instead,
and that compounds. Designing since 2017, in UX since 2019, 15+ clients, no
year off.

### Curiosity is the job
I know a little about a lot, which helps me connect things other people keep
separate. The Wikipedia study is the clearest case: understanding why someone
picks a keypad phone over a smartphone shaped the recommendations far more than
anything I knew about interface design.

### Form follows function
Function solves the problem. Beauty is what makes people remember it, and you
earn the second by doing the first. On the Boost360 onboarding, no amount of
visual polish would have moved the number until research found the real
problem, which was that the ads promised something the signup flow didn't
deliver.

### Give a damn
I work with a founder's mindset and take ownership of what I touch. At Turns
that meant setting up brand guidelines and a design system so the team could
keep shipping consistently after I left. Nobody asked for that part.

[Visual: four numbered statements, type-led. Avoid stock icons.]

---

## 10. Beyond design [Optional]

Heading: **Ask me about**

Short lines, real specifics. Conversation starters for interviews and calls.

- **Hip-hop.** Raised on old school, Eminem and 50 Cent. These days deep into
  Desi Hip Hop. {name two or three DHH artists}
- **Video games.** Need for Speed: Most Wanted (2005, the correct answer), the
  Call of Duty series, Prince of Persia: Warrior Within. Still play a bit of
  everything.
- **Computers and tech.** Engineering kid who never grew out of taking things
  apart.
- **Personal finance and investing.** Slow, boring, long-term, on purpose.
- **Education.** How people learn fascinates me, and it shows up in how I
  design.

[Visual: small personal touches. A playlist card, a game cover, a bookshelf.
Keep them tiny.]

---

## 11. Where I've been

Heading: **Where I've been**

Prose rather than a table. A seven-row table that is half placeholders is the
weakest module on a long page, and the dates carry better as short paragraphs
with the years set large.

> **2025 to now.** {Role} at {Company}. {One line on what you design there.}
>
> **2022 to 2025.** Independent product, UX and web designer. Turns, Gadivan,
> LetsConnect, LearnApp and a dozen others. Website and brand work, 0 to 1
> product design, UX audits, design systems.
>
> **2021 to 2022.** UX designer at Thence, a UX studio. Client work for large
> Indian brands, plus mentoring interns.
>
> **2019 to 2020.** UX research intern at Hureo. Field research for the
> Wikimedia Foundation.
>
> **2017 to 2019.** Graphic design, first at Skillovate and then at HappleyFit,
> alongside freelance work. Logos, a mascot, posters, a board game, a kids'
> eBook, an exhibition booth, and my first WordPress site.

Education: B.E. Computer Engineering, Smt. Kashibai Navale College of
Engineering, Pune University, 2017 to 2021.

### People I've worked with

Turns, LetsConnect, Gadivan, LearnApp, Parentverse, Venyou, Sharent, Spirinova,
Gorico, RedShilliz, DGlobalist, Pahoti Wellness, Ivy Malik, PhotoFinder, Olsub,
Learn Theta.

Agency-side: Thence, a UX studio, and research for the Wikimedia Foundation via
Hureo. [NDA] Asian Paints, NowFloats and Shiprocket never appear by name in
public.

[Optional] One line of context per name where it isn't obvious: {Turns},
{LetsConnect}, {Gadivan}, {LearnApp}.

[Visual: a clean vertical timeline with the dates set large. Small logos
underneath if you have them, otherwise clean text.]

---

## 12. Contact

Heading options: **Say hi** / **Let's talk**

> Whether it's a role, a project, or just a good conversation about design,
> hip-hop, or dogs, my inbox is open.
>
> **madebynaman@gmail.com**
>
> Or find me on LinkedIn, Instagram and Twitter.

{Availability line, the same one as the hero. Repeat it here rather than
inventing a second version.}

Small print [Optional]: Jaipur, India (GMT+5:30). Replies within a day, usually
faster.

Phone: {keep or drop, your call. Email-first is cleaner and safer for privacy.}

[Visual: one more photo of you, relaxed. Good place to end on a face rather
than a form.]

---

## 13. Footer notes [Optional]

Small, dry, human. Pick two:

- No jargon was used on this website.
- Designed and built by me. The first draft had help from 16 AI models.
- Jerry approved this site.

> "No trackers either" was in the last draft and is now cut. It stops being
> true the day you add analytics, and a false claim in the footer is a strange
> thing to have to quietly delete later.

---
---

# FULL CASE STUDIES

Serious tone from here on. Short paragraphs, plain words, numbers first. Each
one follows the same shape: outcome, context, problem, what I did, what
happened, what I learned.

> The bold labels below are scaffolding for writing, not final copy. On the
> page they should become real headings or dissolve into the prose. A run of
> bolded one-word labels reads like a template, which is the opposite of what
> these are supposed to prove.

---

## Case study: Turns

**Outcome first.** The redesigned website and brand helped Turns raise
**$500K in pre-seed funding**, and conversions went up after launch.

**Context.** Turns is {what Turns does, one sentence}. They needed a website
that explained the product clearly and a brand that looked like a company
investors could trust. I worked directly with the founding team.

**Problem.** {What was broken about the old site and brand, 2 to 3 lines.
Confusing story? Weak credibility? No system?}

**What I did.**

- Redesigned the website and key landing pages end to end.
- Ran UX audits to find where visitors dropped off.
- Built brand guidelines that work across web, mobile and print.
- Set up a design system so the team could ship consistently after I left.

**What happened.** Conversions rose after launch. The team used the new site
and brand in their fundraise and closed a $500K pre-seed round. {Is the design
system still in use there? The resume doesn't say, so confirm it with them
before claiming it.}

**What I learned.** {1 to 2 honest lines, e.g. what a website actually does
inside a fundraise, or designing for investors versus users.}

[Visuals: before and after of the homepage, three or four page mockups, a slice
of the brand guidelines, design-system components.]

---

## Case study: LetsConnect

**Outcome first.** After the redesign, LetsConnect sits at **4.8★ on the Play
Store**.

**Context.** LetsConnect is {what it does, one sentence}. Users liked the idea
but struggled with the product.

**Problem.** Reviews and feedback pointed at the same things: {the recurring
usability issues, 2 to 3 lines}. The app worked. It just didn't feel like it.

**What I did.**

- Read through user feedback and reviews, and grouped the recurring complaints.
- Mapped the core journeys and found where people got lost.
- Redesigned the end-to-end experience around those pain points.
- Worked with the team through release, screen by screen.

**What happened.** The redesigned app reached 4.8 stars on the Play Store.
{If you have a real before-and-after review to quote, put it here. Pull the
exact words from the Play Store listing. Don't paraphrase one into quote
marks.}

**What I learned.** {1 to 2 honest lines.}

[Visuals: review snippets before and after, journey map photo, key screens.]

---

## Case study: Wikipedia × KaiOS

**Outcome first.** 25 in-person interviews across 3 Indian cities gave the
Wikimedia Foundation direct evidence about a user group it had almost no data
on, plus a concrete list of what to fix.

**Context.** In 2020 the Wikimedia Foundation wanted to understand people who
use JioPhones, smart feature phones running KaiOS. They're cheap, durable and
keypad-driven, and for many people in India they are the only internet-connected
device in the house. I was a UX research intern at Hureo, working with senior
researchers.

**What we did.**

- 25 one-on-one, in-person sessions in Pune, Mumbai and Delhi.
- 45 to 60 minutes each. First an interview covering background, reading
  habits, phone and internet use, then observed tasks on the participants' own
  devices.
- Participants: students, businessmen, homemakers, bank employees, salesmen and
  field executives, aged 18 to 40, reading in Hindi, basic English and regional
  languages.

**Why people choose a JioPhone** (what we heard):

- Smartphone features at a fraction of the price
- Cheap and easy to repair
- Durable enough for real life
- Keypads they already know
- Battery that lasts
- Family already on the Jio network

**What Wikipedia users asked for:**

- More images and video, fewer walls of text
- English numerals in Hindi and regional articles
- A table of contents to jump around
- Search inside articles
- Newest information first
- Bigger fonts, more colour
- Simpler Hindi words
- A news section
- The ability to copy text

**What we recommended:**

- Voice search and voice navigation. Typing on a keypad is the real barrier.
- Readability first: shorter articles, bigger text, better tables and images on
  small screens.
- Video formats for people who don't read long text online.
- Make search impossible to miss.
- SEO for regional languages. Most participants didn't know Wikipedia speaks
  their language.

**What happened.** The findings went to the Wikimedia Foundation as personas,
journey maps, ecosystem maps and a full research report.

**What I learned.** Most of the internet is designed for people like me, on
devices like mine. This study changed how I think about "the user."

[Visuals: a JioPhone, field notes, session photos (with consent), persona
cards, the journey map.]

---

## Case study: Gadivan

**Outcome first.** A complete product designed from zero: multiple apps for
different stakeholders, one design system underneath.

**Context.** Gadivan is {what Gadivan does, one sentence}. When we started
there was no product, just an idea and a founding team.

**Problem.** Different stakeholders needed different things: {who the apps
served, e.g. customers, drivers, ops team, 2 to 3 lines}. The product had to
feel like one company rather than three disconnected apps.

**What I did.**

- Worked with the founders to turn the idea into defined user journeys.
- Designed the end-to-end experience for each app from scratch.
- Built one shared design language so every app felt related.
- Stayed through development, iterating with the team until launch.

**What happened.** The product went from a blank page to 0 to 1. {Add an honest
result: a launch date, user numbers, or "still live today". The resume supports
0 to 1 and nothing beyond it, so don't stretch this one.}

**What I learned.** {1 to 2 honest lines on what designing 0 to 1 actually
demands.}

[Visuals: the app family together, early sketches next to final screens, one
full user flow.]

---
---

# [NDA] CASE STUDIES: password-protected area, never public

Keep these complete. On the public site they exist only as the locked teaser
(section 3, card 5). Client names and numbers stay behind the password.

> **Confirm the Boost360 result before it goes anywhere, and note this isn't
> just a disagreement about one digit.** The resume says "up to 50% decrease in
> uninstalls and app abandonment within the first 2 weeks." The portfolio says
> "60% decrease in app uninstall rate." Those are two different metrics
> measured over two different windows, and one of them is hedged with "up to."
> Find the original measurement and state the number, the metric and the window
> together.

---

## [NDA] Case study: Asian Paints Dealer Portal

- Agency: Thence · 2021 · Role: UX research, UX design, UI design
- With: UI designer, PM, design manager, client team

**Problem.** Dealers had to call a salesperson for every order. Every
competitor already had a portal, and dealers hated all of them. The goal was to
digitize ordering and supply-chain tracking, and to grow transaction volume and
average order value.

**What the research said.**

- Dealers don't want to talk to a salesperson every time they order
- They already use competitor portals, reluctantly
- Every existing portal frustrates them
- Different dealer staff need different access levels
- Asian Paints has demand data it can use to nudge smarter ordering

**What I designed.**

- Heuristic evaluation, then an end-to-end redesign of the portal
- Features that cut the dealer's dependency on a salesperson, and the cost that
  came with it
- Personalized product recommendations from order history
- Personalized discounts and loyalty points
- Data-driven promotions based on geography and demand trends
- Order-size and periodic incentives to lift AOV
- Barcode scan ordering, with products in the cart in under 10 seconds

**Screens.** Home, Trending Products, Categories, Catalog, Product Listing,
Place Order, Stock Check, Wishlist, Cart, Order Tracking, Account Management,
Reports.

**Impact.** **20% increase in online transaction volume**, plus a healthy rise
in engagement and loyalty.

[Visuals: portal screens, the barcode flow, recommendation UI.]

---

## [NDA] Case study: Boost360 Onboarding

- Agency: Thence · 2021 · Role: UX research, UX design, UI design, usability
  testing
- With: UI designer, motion designer, PM, design manager, client team

**Problem.** New users installed the app and left before signing up. Uninstalls
happened within 4 hours. Signup success was 20%, and a successful signup took
30 minutes.

**Hypotheses.** Everything from crashes on low-end devices and late OTPs to too
many ads, too many permissions, language barriers, and a gap between what the
ads promised and what the app did.

**What research found.** The real causes:

- The signup UX was poor and hard to understand
- Marketing set expectations the product didn't meet
- Users hit paid features they expected to be free

Root cause: an expectation mismatch, created by the ad and discovered at the
signup form.

**What I designed.**

- A visual, self-explanatory signup flow
- App USPs communicated during onboarding rather than after
- Social proof inside the flow, to build trust early
- Quick wins, so the user sees a real result in minutes
- Screen-level UX fixes throughout
- A direct line to support when stuck
- A communication audit across every marketing touchpoint

**Usability testing.** The new flow tested well:

- Users understood what the app does straight away
- Nobody got stuck or confused inside the flow
- Most skipped the optional onboarding screens entirely
- Almost everyone was surprised they could build a business website that
  quickly

> The research report summarised these sessions in its own words. If you want a
> participant quote on the page, pull a real one from the session notes. Don't
> promote a summary line into quotation marks.

**Impact.** **{Confirm the number, the metric and the window}% decrease in app
uninstalls**, and a significant drop in time to signup.

[Visuals: old and new signup flow side by side, the quick-win moment, usability
test notes.]

---
---

# PHOTO & ASSET CHECKLIST

**This list is the blocker on the whole site.** The layout is planned
visual-first and none of these exist yet. Shoot them before build, or ship the
copy-forward fallback below.

- [ ] Warm portrait for the hero (face visible, natural light)
- [ ] Jerry: one great shot, and one of the two of you
- [ ] Two or three candids for About (working, whiteboard, chai)
- [ ] Turns: website mockups, brand guideline spreads
- [ ] LetsConnect: before and after screens, Play Store review screenshots
- [ ] Wikipedia: JioPhone, field notes, session photo (consented)
- [ ] Gadivan: app family shot
- [ ] Client logos (ask permission where unsure)

**Copy-forward fallback.** If the shoot slips, the page can ship on typography
alone. Set the four hero numbers large. Run the no-jargon section as a
full-bleed type treatment, which it wants to be anyway. Render each work card
as a title, a tag row, the outcome line, and a solid colour field where the
mockup goes. Only two images are genuinely irreplaceable: the hero portrait and
the photo of Jerry. Ship without the case-study mockups if you have to, but not
without a face.

---

# PRUNING GUIDE

If the site feels long, cut in this order:

1. Section 13 (footer notes). Keep one line at most.
2. Section 10 (Beyond design). Fold one line into About.
3. Section 11's optional client one-liners. Go back to a plain name list.
4. Section 9 (Principles). Cut to two, keeping the two with the strongest proof
   attached.
5. The "more work" list under the section 3 cards.

Never cut: the hero and its four numbers, the four work cards, Kind words, and
Contact. That is what a hiring manager came for, and it is the shortest path
from a stranger landing on the page to a stranger emailing you.

Jerry and the no-jargon section are what people remember afterwards, so cut
them late. But cut them before you cut the work.

---

# OPEN PLACEHOLDERS (for you to fill)

- {Current role, company, what you design} in sections 1, 7 and 11
- {Availability line} in sections 1 and 12
- {What Turns / LetsConnect / Gadivan / LearnApp do} in sections 3 and 11, plus
  the case studies
- {Turns: what was broken before, and whether the design system is still in
  use} in the Turns case study
- {LetsConnect: the recurring usability issues, and a real review quote if one
  exists} in the LetsConnect case study
- {Gadivan: who the apps served, plus an honest result} in the Gadivan case
  study
- {Three testimonials} in section 5
- {Two or three DHH artists} in section 10
- {Boost360: the real number, metric and window} in the NDA case study
- {Current book, current game} in section 7
- {What I learned} in the Turns, LetsConnect and Gadivan case studies. Only the
  Wikipedia one is written. These are the hardest lines in the doc and the ones
  a design lead will actually read, so write them last and write them honestly.

Two things to confirm rather than write:

- Whether the Wikimedia study can be named publicly (see the note at the top of
  this doc)
- Whether the phone number stays on the page
