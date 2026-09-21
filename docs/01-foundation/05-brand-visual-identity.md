# 05 · Brand and Visual Identity

**Status:** SETTLED. Extracted from the approved strategy deck, which is her own identity applied.
**Applies to:** every card, carousel, cheatsheet, banner and document that carries her name.

---

## The one sentence brief for a designer

Quiet, warm, expensive, and confident enough to leave space empty. Serif for the thinking, sans
for the machinery. Terracotta earns attention; it never shouts for it.

---

## Palette

| Token | Hex | Use |
|---|---|---|
| `--ink` | `#0B0B0B` | Headlines, the dark full bleed card |
| `--charcoal` | `#2B2521` | Body text |
| `--ink2` | `#7A6F63` | Secondary text, captions, labels |
| `--terracotta` | `#8C5442` | The single accent. Kickers, emphasis, one element per card |
| `--terracottaSoft` | `#F1E3DA` | Chip fills, quiet highlights |
| `--terracottaWhisper` | `#F8EFE9` | Large tinted areas |
| `--gold` | `#D4A370` | Accent on dark backgrounds only |
| `--paper` | `#F6EFE8` | Page background |
| `--card` | `#FCF9F4` | Card background |
| `--line` | `#E4D6C4` | Hairline borders, 1px |

**Rules.** One accent colour per card. Terracotta on paper, gold on ink, never the reverse. No
gradients. No drop shadows beyond a hairline border. Nothing saturated, nothing neon, nothing that
reads as a template.

---

## Type

| Role | Face | Treatment |
|---|---|---|
| Display and headings | **Instrument Serif**, regular 400 | Never bold. Tight line height, 1.15 at large sizes |
| Emphasis inside a heading | Instrument Serif italic, terracotta | One phrase per card at most |
| Body and UI | **Open Sauce Sans**, fallback Söhne, then Arial | 15px equivalent, line height 1.65 |
| Kicker | Open Sauce Sans, 600, 11.5px, 0.14em tracking, uppercase, terracotta | The only uppercase permitted |

**The serif carries the idea. The sans carries the apparatus.** A card where the sans is doing the
thinking is wrong.

---

## Card grammar

Standard card, used for the Make Me Think and Understand Me image posts.

```
+------------------------------------------+
|                                          |
|  KICKER, optional, terracotta, uppercase |
|                                          |
|  The line, Instrument Serif,             |
|  regular weight, large,                  |
|  two or three lines maximum.             |
|                                          |
|                                          |
|                       nicolebrandes.com  |  <- 10.5px, --ink2
+------------------------------------------+
```

- Square, 1080 x 1080, or 4:5 at 1080 x 1350 for feed height
- Generous margin. Not less than 9 percent of the card width on every side
- Never more than one idea on a card
- No logo lockup on a statement card. The typography is the identification
- No quotation marks unless the line is genuinely a quote from a named public source

**The dark card.** Ink background, gold kicker, paper coloured text. Reserved for the single
hardest line in a set. Never more than one per carousel.

---

## Carousel grammar

Eight to ten slides. The shape is fixed.

| Slide | Job |
|---|---|
| 1 | The hook. One line. No subtitle, no "swipe" prompt |
| 2 | The turn. Why the obvious reading is not the useful one |
| 3 to 7 | One idea per slide. Heading plus two or three sentences maximum |
| 8 | The landing. Shorter than everything before it. Unresolved |
| 9, optional | A quiet identification slide. Her name, the site. Nothing else |

No slide numbers as decoration. No progress bars. No "swipe left" arrows, the platform supplies
that affordance already.

---

## Cheatsheet grammar

The saveable format. Rows, not paragraphs.

- A title that is a scene or a question, never a listicle promise
- Five or six rows, each one a pair or a single honest answer
- Columns labelled in the kicker style
- Hairline rules between rows, 1px `--line`, never a filled table
- Nothing on the card that instructs the reader to save it

---

## What a Nicole asset never looks like

- A stock photograph of a person at a window
- A headshot with a quote overlaid
- Anything with a coloured banner strip reading a category name
- Three icons in a row
- A gradient, a glow, a soft shadow, a rounded card inside a rounded card
- Emoji used as bullet points
- A "before and after" layout of any kind

> "It has to be classy. But of course, it has to sell."
> Nicole

> "We can't just be a content machine, just to put something out there for the sake of it. It has
> to be of substance."
> Nicole

---

## Accessibility floor

Body text against `--card` and `--paper` clears 4.5:1. Terracotta `#8C5442` on paper `#F6EFE8`
clears 4.5:1 for text at body size and above, which is why it is safe as a text accent and not
only as a fill. Gold `#D4A370` does **not** clear it on paper, which is why gold is restricted to
ink backgrounds. Never set body text in `--ink2` below 12px.
