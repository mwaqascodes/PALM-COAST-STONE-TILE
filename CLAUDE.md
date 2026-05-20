# Palm Coast Stone & Tile — Landing Page

## Project Overview

Glassmorphism landing page for **Palm Coast Stone & Tile**, owned by Jeff & Gina Herbert in Palm Coast, Florida.

## Business Details

| Field | Value |
|-------|-------|
| Business | Palm Coast Stone & Tile |
| Owners | Jeff & Gina Herbert |
| Phone | (386) 393-1166 |
| Email | palmcoasttile@outlook.com |
| Website | https://www.coaststonetile.net/ |
| Location | Palm Coast, FL 32164 |
| Est. | 2006 (19+ years) |
| Projects | 200+ completed |

## Files

- `index.html` — Single-file landing page (HTML + CSS + JS inline)

## Design System

**Aesthetic:** Luxury glassmorphism — dark stone-inspired background with frosted glass cards and warm gold accents.

**Fonts:**
- Display: `Cormorant Garamond` (serif, italic for accents)
- Body: `Jost` (clean geometric sans)

**Color Palette (CSS variables):**
```
--bg:         #07090f     (deep dark background)
--gold:       #c9a96e     (primary accent — travertine gold)
--gold-light: #e0c48c     (hover state gold)
--glass:      rgba(255,255,255,0.045)  (card backgrounds)
```

**Glass Effect:**
- `backdrop-filter: blur(24px) saturate(1.3)`
- `border: 1px solid rgba(255,255,255,0.09)`
- `box-shadow: 0 8px 32px rgba(0,0,0,0.45)`

## Page Sections

1. **Navigation** — Sticky glassmorphism nav, scrolled state changes
2. **Hero** — Full-viewport, animated hero badge, floating stats card
3. **Trust Bar** — 5 trust signals (guarantee, years, projects, etc.)
4. **Services** — 4 glass cards (Kitchen, Bathroom, Stone, Design)
5. **Design Styles** — Contemporary / Rustic / Timeless
6. **Process** — 4-step connected track (Conceptualize → Craft → Personalize → Care)
7. **Why Us** — Points list + large glass stats panel
8. **Testimonials** — 3 glass review cards
9. **Contact** — Info panel + glassmorphism contact form
10. **Footer** — Three-column with phone and email

## Skills Used

- `frontend-design` — Glassmorphism UI with Cormorant Garamond + Jost
- `superpowers:brainstorming` — Pre-implementation design exploration
- Research via `Explore` subagent on coaststonetile.net

## Design Decisions

- **Background:** Dark gradient base + SVG marble veins (thin diagonal lines) + grain noise overlay
- **Cards:** Glass effect strongest on hero float card and contact form panel
- **Animations:** IntersectionObserver scroll reveals with staggered delay on grid children
- **Nav:** Semi-transparent base, darkens + gold border on scroll
- **No images required** — Pure CSS background effects simulate stone/marble texture

## Future Improvements (if needed)

- Add real photography from completed projects (hero background, gallery section)
- Wire contact form to email service (EmailJS, Formspree, etc.)
- Add Google Maps embed for location
- Add Google Reviews widget for live testimonials
- SEO: Add structured data (LocalBusiness schema)
