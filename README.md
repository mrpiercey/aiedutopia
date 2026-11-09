# Authentic or AI?
### An Edutopia Media Literacy Lesson

A projectable, whole-class lesson that teaches students to spot AI-made pictures, articles, and posts, and to **check before they share** using SIFT.

**Live:** https://mrpiercey.github.io/aiedutopia/

## How to run it

1. Open `index.html` (or the live link) on the classroom screen. Click **Full Screen**.
2. Press **Next** (or `→`, space, or a presentation clicker) to move through the whole lesson. That's it.

The flow is one straight line:

| Part | What happens |
|---|---|
| Learn (3 slides) | SIFT, 3 picture clues, 3 word clues |
| Practice | One AI photo. Students point at what looks off, then numbered rings show the clues |
| Cards 1-4 | Solved together; each teaches one SIFT move |
| Cards 5-10 | Students lead. Each card: **Think, Pair, Vote**, then **Reveal** |
| Finish | Exit ticket |

Every slide fits the screen (text eases down automatically on small projectors). Progress saves on the computer, so **Continue** picks up next class. The numbers in the bottom bar jump to any card.

**Keys:** `→` / space / PageDown next · `←` / PageUp back · `C` clue checklist · `F` full screen · `Esc` close

## Printables (Menu → Printables, or the button on the title slide)

- **Lesson Plan**: one page with timing, the card routine, discussion moves, memory tips, and the research
- **SIFT Poster**: classroom anchor chart
- **SIFT Bookmarks**: 4 per page
- **Student Writing Cards**: one half-sheet per card with sentence starters
- **Exit Tickets**: 4 per page
- **Teacher Answer Key**

## Research basis

SIFT (Caulfield, 2019); lateral reading (Wineburg & McGrew, 2019; Wineburg et al., 2022); students' online reasoning (Stanford History Education Group, 2016, 2019); people can't reliably spot AI faces by eye (Nightingale & Farid, 2022). Because of that last finding, the lesson treats visual clues as a reason to check, not as proof.

## Editing

- **Card content:** in `index.html`, find `CARDS.push(` and edit the card objects (`type`, `answer`, `clues`, `verify`, `discuss`, ...). Slides, printables, and the answer key update automatically.
- **Lesson slides / SIFT wording:** `SIFT_MOVES`, `PIC_CLUES`, `WORD_CLUES` just below the cards.
- **Shared on-page editor:** open the page with `?edit` to change any text or font for everyone (saved to Firestore).

## Credits

Real photos: Jim Peaco/NPS (Grand Prismatic Spring), Bill Anders/NASA (Earthrise), both public domain. AI images from Wikimedia Commons AI-media categories (the girl-and-cat image is CC BY-SA 4.0 and credited on its card). Fonts: Poppins and Zilla Slab, embedded, per Edutopia's Google-safe substitutions for Gotham and Museo Slab.
