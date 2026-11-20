# Techfest 30: Landing Page Concept

A landing page concept for Techfest, IIT Bombay (techfest.org), built for the "Ideate Landing Page" task. It uses no 3D assets.

## Idea
Techfest’s 30th edition is the hook. The page opens with an oversized "30", a live countdown to 16 December 2026 and a pointer-following spotlight, then explains what visitors can do and how the festival has grown.

## Sections
1. **Hero:** headline, live countdown and call to action.
2. **Marquee:** scrolling ticker of the four event types.
3. **Four ways in:** Compete, Learn, Listen and Explore, as expandable rows.
4. **Thirty years of showing up:** key numbers (1998 start, 1.65 lakh record footfall, ₹3.8 lakh Probability Challenge prize pool, 3 days).
5. **The road to December:** a timeline that marks past and upcoming dates automatically from today’s date.
6. **Closing call to action** linking to techfest.org.

## Design choices
- Palette: ultramarine blue, deep indigo, signal yellow and pale lavender paper.
- Type: Anybody (wide, heavy display) and Instrument Sans (body), with system fallbacks.
- Motion is limited to the countdown, the pointer spotlight, the marquee and the expanding rows. `prefers-reduced-motion` is respected.
- Fully responsive, with keyboard focus styles.

## Facts used
Taken from public sources: Techfest began in 1998, record footfall was 1.65 lakh in 2015–16, the 2026 edition runs 16–18 December 2026, the Probability Challenge (with Jane Street) has a ₹3.8 lakh prize pool, and Techfest holds a Guinness record for most LED lights lit simultaneously (2018).

## Run it
Open `index.html` in a browser. No build step. Fonts load from Google Fonts, with fallbacks offline.

## Files
- `index.html`: the whole page (HTML, CSS and JavaScript)
- `README.md`: this file

This is a concept and is not the official Techfest website.
