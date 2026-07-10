# Lumiq - Full Case Study

**Brand Identity · Framer Development · Content & Copy**

By [Himanshu Dhara](https://www.upwork.com/freelancers/himdhara2002?mp_source=share)

---

## The Tldr

AI photo enhancement brand. Built from zero.

Brand voice, color system, landing page, blog, CMS - no Figma handoff, no template, no "supercharge your workflow" copy anywhere.

The brief: make an AI tool that sounds like it was built by someone who actually knows what a RAW file is.

[Lumiq - Live Site](https://lumiq.framer.ai/)

---

## The Problem With Most AI Photo Tools

Waaait... have you noticed how every AI photo tool sounds exactly the same??

"Supercharge your workflow."
"Next-gen AI-powered enhancement."
"Seamlessly transform your images."

EVERY single one.

And the websites look the same too - dark gradients, glowing orbs, stock photos of people looking impressed at screens.

None of it says anything about photography. About light. About the actual craft.

The photographers who need these tools - the ones shooting 400 wedding selects on a Saturday and editing until Monday morning - they don't want hype. They want to know what the tool actually does. Precisely. Without the noise.

Lumiq was built to be that tool.

Precise but not cold.
Cinematic but not pretentious.
Technical but not a science paper.

---

## The Brand System

Three accents. One gradient that actually means something for a photo brand.

| Role | Token | Hex | Opacity |
|------|-------|-----|---------|
| Accent - Cobalt | Ascent / Blue | `#1A3AE8` | 100% |
| Accent - Flame | Ascent / Red | `#ED3F27` | 100% |
| Accent - Amber | Ascent / Yellow | `#FEB21A` | 100% |
| Background | Background | `#FDFCFC` | 100% |
| Card | Card BG | `#F5F3F1` | 100% |
| Card Transparent | Card BG - Trans | `#F5F3F1` | 30% |
| Border | Border | `#EDEBE8` | 100% |
| Heading Text | Text | `#1A1917` | 100% |
| Body Text | Body Text | `#616161` | 100% |

The flame-to-cobalt gradient comes directly from the brand reference image - a dual-tone thermal photograph that became the visual anchor for the entire system. Warm left. Electric right. The amber sits between them as the tension point.

The warm stone backgrounds (`#FDFCFC` and `#F5F3F1`) create a film-like base that makes the gradient pop without screaming. It feels editorial. Not SaaS.

**Typography:**

| Style | Font | Size | Letter | Line |
|-------|------|------|--------|------|
| H1 | `Instrument Serif` Regular | 48px | -0.02em | 1.1em |
| H2 | `Instrument Serif` Regular | 40px | -0.02em | 1.2em |
| H3 | `Instrument Serif` Regular | 33px | -0.02em | 1.2em |
| H4 | `Instrument Serif` Regular | 28px | -0.02em | 1.2em |
| H5 | `Instrument Serif` Regular | 23px | -0.01em | 1.2em |
| H6 | `Instrument Serif` Regular | 19px | 0.01em | 1.3em |
| Body | `Geist` Regular | 16px | -0.01em | 1.4em |
| Small | `Geist` Regular | 13px | 0.01em | 1.2em |
| Button | `Geist` Regular | 16px | -0.01em | 1.4em |
| Button Small | `Geist` Regular | 13px | 0.01em | 1.2em |

Instrument Serif at display sizes gives Lumiq its photographic, cinematic feel - the contrast between a warm editorial serif and a precise technical product is exactly the tension the brand lives in.

Geist for body and UI keeps everything readable and clean. No personality fights. Each font knows its job.

**Icons:** Phosphor Icons - duotone weight throughout.

Duotone felt right for a brand that lives between two things - the warmth of photography and the precision of AI.

---

## The Sections

Here's exactly what was built - desktop, tablet, and mobile responsive across all of it.

```
Desktop
├── Navigation
├── Main
│   ├── Hero Section
│   ├── About Section
│   ├── Features Section
│   ├── Process Section
│   ├── Pricing Section
│   ├── Blogs Section
│   ├── Testimonials Section
│   └── FAQs Section
├── Footer Section
Tablet
Phone

/blogs
├── Featured Blogs Section
└── All Blogs Section

Blog Detail Page
└── Body Section
```

---

### Hero Section

> *"Photos that think for themselves."*

Split layout. Text left, three-image grid right - one large image top, two equal images bottom row.

Trust badge (`4.9 ... Trusted by Thousands`) sits above the headline so it lands before the pitch. Primary CTA uses the flame-to-amber gradient with hover reversal. Secondary CTA is a ghost link - no visual competition.

The three image slots use brand-palette gradient compositions so the hero reads as a photo AI product even before real photography loads in.

---

### About Section

> *"Not a filter. Not a preset. An eye."*

Full bleed background image with a floating UI card center. Four tabs inside the card: Enhancement, Accuracy, Speed, Modes. Each tab shows a different performance angle of the product.

The UI card teaches the product while building trust - not just describing it. The tab switcher means one section does the work of four.

---

### Features Section

> *"Six engines. Running at once."*

Dashboard layout - three cards top row, two cards bottom row.

Top row: donut accuracy chart by mode, monthly enhancement bar chart with 40% spike callout, speed comparison bars versus manual editing.
Bottom row: multi-line trend chart with live tooltip, mode performance list with individual progress bars.

Subhead does the heavy lifting: "No queue. No waiting. All six modes run in parallel the moment you upload."

---

### Process Section

> *"From raw file to client-ready in 2.4 seconds."*

Left nav links (Upload - Enhance - Review - Export), right side four cards stacked. Each card: step tag, headline, two-line description, UI mockup.

Four UI mockups: drag-drop upload zone with file queue and status pills, live progress bars per mode while running, before/after split comparison with accuracy score, export destinations with Framer CMS connected state.

---

### Pricing Section

> *"Start free. Pay when you're sure."*

Three cards. Free, Pro, Team. Pro is featured - dark background (`#1A1917`), gradient CTA button.

Feature lists use cobalt blue accent on key differentiators (`RAW file support`, `CMS push`) to make the upgrade reasons scannable without a comparison table.

Fine print: "Annual billing saves 30% - Cancel anytime - All data deleted on request."

---

### Blogs Section

> *"What we're thinking about photography."*

3x2 grid. Featured post spans 2 columns - larger image, longer title. Five posts covering: AI resistance in photography, what relighting actually does, batch processing 400 wedding selects, how Portrait AI reads skin, and the tools photographers cancelled after switching.

Every post written in Lumiq's voice. Not SEO filler. Actual takes.

CMS-bound in Framer - title, excerpt, category, author, read time, date, cover image all in the collection.

---

### Testimonials Section

> *"The results speak for themselves."*

9-card grid. 3x3. Top 6 full opacity, bottom 3 faded - creates depth and implies more behind the visible set.

Every quote is specific. "The relighting alone saves me two hours per shoot." "I cancelled my Photoshop subscription the same week." "Portrait AI reads the face - it doesn't just blur it."

CMS-bound. Each card: avatar, name, role, star rating, quote.

---

### FAQs Section

> *"Straight answers."*

Accordion layout. First item open by default with gradient active state (flame-to-cobalt background). Seven questions - RAW support, data privacy, commercial use, Lightroom comparison, API access, free plan mechanics. Every answer one paragraph. Direct. No hedging.

---

### Footer Section

Dark background (`#1A1917`). Four columns: brand + email input with gradient send button, contact + location, navigation, product + legal.

Bottom bar: copyright left, social links center, tagline right.

---

### Blog Page (/blogs)

Two sections: Featured Blogs (hero post, large format) and All Blogs (filterable grid by category).

Blog detail page has a clean Body Section - just the post content, author block, related posts. No sidebar. No clutter.

---

## The Copy

Yeppp - every single word on this site was written from scratch. 🙃

Not "placeholder text replaced with real words."

Actually written. With a brand voice. With intention.

The voice rule for Lumiq was specific:

Precise but not cold.
Cinematic but not pretentious.
Anti-hype. Always.

That meant banning specific words entirely - "supercharge," "revolutionize," "next-gen," "seamlessly." If a word sounded like a pitch deck, it got cut.

Writing from the photographer's perspective, not the product's. "The AI reads your light" instead of "our advanced algorithms analyze image data." Same information. Different relationship with the reader.

Five full blog posts written from scratch - each with a distinct angle, a specific audience, and Lumiq's voice throughout.

---

## The Images

Gradient blob compositions and dual-tone color treatments used throughout - no generic stock photography.

The visual direction came from a reference image: a thermal photograph with flame red bleeding into electric cobalt. That treatment became the hero image system, the about section background, and the card thumbnails across the gallery and blog.

Image prompts written per section and per brand aesthetic - specific color values (`#ED3F27`, `#1A3AE8`, `#FEB21A`), temperature, grain, and mood direction for each slot.

---

## What This Proves

A photo AI brand doesn't have to sound like every other photo AI brand.

Stripping the hype out completely - no "revolutionary," no "next-gen," no gradient orbs - and replacing it with precision takes confidence. The result is a brand that respects the person reading it.

And honestly?? That's the only kind of website worth building. 🙃

---

## Links

[Live Site](https://lumiq.framer.ai/)

[Upwork Project](https://www.upwork.com/freelancers/himdhara2002?p=2075262751384870912)

[Upwork Profile](https://www.upwork.com/freelancers/himdhara2002?mp_source=share)

---

<img src="./Profile Image.png" width="60" height="60" />

*Designed & built by Himanshu Dhara - Framer Developer & Brand Designer - 2026*
