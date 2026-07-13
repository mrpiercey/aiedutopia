# Authentic or AI? 🔍
### An Edutopia Media Literacy Detective Game

A projectable, whole-class game where students examine **20 case files** — headlines, short passages, and images — and decide whether each is authentic or AI-generated. The twist: **it's secretly a writing activity.** Guessing isn't enough — students must make a claim, cite specific clues, and name the reliable-source evidence that could prove it.

## Quick start

1. **Open `index.html` in any browser.** That's it — no internet required. Everything (images, fonts, all 20 cards) is embedded in the one file. Project it for the class.
2. **Print the student materials first**: click **🖨 Print Materials** (top right) and print the **Student Evidence Sheet** (scaffolded version for grades 3–6, open version for 6–12). Optionally print the **Detective Checklist Poster** for desks.
3. Pick a **difficulty** (Level 1 = gr. 3–5, Level 2 = gr. 6–8, Level 3 = gr. 9–12, or All Cards) and optional **teams**, then hit **Start Detective Training**.

## Suggested lesson flow (~45–60 min)

| Segment | Time | What happens |
|---|---|---|
| Detective Training | 10 min | 6 short slides done as a class: image clues, text clues, the SIFT verification method, a clickable practice image, and how to write an evidence entry |
| Case files | 25–40 min | 5–8 cards, each through the 4-phase loop: **Examine → Think & Write (students write on evidence sheets; built-in 2/5/8-min timer) → Vote → Reveal** (annotated explanation + real source) |
| Wrap-up | 5–10 min | Final scores + built-in exit-ticket writing prompt |

You don't need to play all 20 cards in one sitting — the card grid tracks what's completed, so it works as a warm-up routine across many days.

**Keyboard:** `→` / `space` advance · `←` back · `C` toggles the Detective Checklist drawer on any screen.

## What's inside the deck

- **8 headlines** — 4 real "weird but true" stories (each verified; the reveal cites the actual outlets) + 4 AI-written fakes with classic tells
- **6 passages** — 3 human-written (Scott's Antarctic diary, *Anne of Green Gables*, Helen Keller's memoir — all public domain) + 3 AI-written, with the tell phrases highlighted on reveal
- **6 images** — 3 real public-domain photographs that look almost fake (NPS, NASA, Library of Congress) + 3 genuinely AI-generated images from Wikimedia Commons

Every reveal includes: the verdict, 3–4 explained clues, a "how you could verify it" SIFT move with the real source, and a class discussion question. The **Teacher Answer Key** printable has all of it on paper.

## Editing / extending the deck

All content lives in one place: open `index.html`, find `CARDS.push(` in the `content-script` block, and edit or add card objects (`type`, `level`, `answer`, `clues`, `verify`, `source`, `discuss`). New cards appear in the grid, dots, and answer key automatically.

## Credits & licensing notes

- Real photos: Jim Peaco/NPS (Grand Prismatic Spring), Bill Anders/NASA (Earthrise), Dorothea Lange/FSA, Library of Congress (Migrant Mother) — all public domain.
- AI images: sourced from Wikimedia Commons AI-media categories (public domain in the US as non-human authorship; the girl-and-cat image is CC BY-SA 4.0 and credited on its card).
- Fonts: Poppins and Zilla Slab (Google Fonts, embedded) per Edutopia's Google-safe substitution guidance for Gotham and Museo Slab. If Museo Slab is installed locally, headlines use it automatically.
- The **"edu" bug in the header is a placeholder SVG** — swap in the official logo asset before publication.
