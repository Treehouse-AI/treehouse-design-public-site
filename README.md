# Treehouse

Landing page for Treehouse, a design & AI studio in Toronto.

- `index.html`: the landing page. One static file, no build step. Open it in a browser or deploy it to any static host (Netlify, Vercel, GitHub Pages).
- `robots.txt`, `sitemap.xml`: for search engines.

## Before launch: replace these

| What | Where |
| --- | --- |
| `example.com` (domain) | `index.html` (canonical, OG, JSON-LD), `robots.txt`, `sitemap.xml` |
| `hello@example.com` | `index.html` (contact section, JSON-LD) |
| `https://cal.com/REPLACE-WITH-BOOKING-LINK` | `index.html` contact button |

## Drafted details to confirm

These were written from the poster and are not yet confirmed:

- 30-minute intro call; reply within 2 business days
- Workshops in person (Toronto area) or remote
- The "For" and "You get" lines on each service card
- Pricing is set after the intro call, with a written quote before work starts (no public prices yet). Add starting prices to the "How we work" cards when you have them.

## Animated hero

- The hero background is a small WebGL animation (no library) in `index.html`. If WebGL isn't available it falls back to a still CSS gradient.
- "hello toronto" intro plays on the first visit per browser session (tap to skip).
- The headline swaps between English and French every few seconds. **Have a fluent French speaker check:** "Nous aidons votre équipe à mieux travailler avec l'IA."
- A "Pause motion" button stops all movement, and people who turn on "reduce motion" on their device see a still version with no intro.

## Founder names

The site shows the founders anonymously ("Two co-founders", with experience but no names or photos). When both founders are cleared by their employers, replace the team card with named bios and photos. A commented-out testimonial block is ready in the team section for a real, approved client quote.
