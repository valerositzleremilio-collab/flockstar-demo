# FLOCKSTAR — Claude Code Context

## Project
Single-page landing site for FLOCKSTAR, a Gen Z cornflakes startup brand.
File: index.html (single file, no framework, no npm)
Deploy: git push → Vercel auto-deploys

## Assets in this folder
logo.png, box.png, char-headspin.png, 
char-fallen.png, char-footer.html

## Design Tokens
--pink:   #FF2D9B
--yellow: #FFE600
--blue:   #00C2FF
--purple: #9B2DFF
--orange: #FF6B00
--dark:   #1a0028
--white:  #FFFFFF
Font display: Fredoka One
Font body: Nunito

## CDN Stack
GSAP 3.12.5 + ScrollTrigger (cdnjs)
Three.js r128 (cdnjs)
Google Fonts

## Sections (top → bottom)
1. Nav (fixed, logo left, CTA right)
2. Hero (box + character + headline + CTA)
3. Story (headspin→fallen on scroll)
4. Flavor (3D rotating box + spotlights)
5. Reviews (3 cards)
6. Footer (char laying + hearts)

## Rules
- No npm, no frameworks, no build tools
- All CSS in <style>, all JS in <script>
- Every section: /* ══ SECTION NAME ══ */ comment
- CSS vars always, never hardcoded hex
- mix-blend-mode: multiply on char images 
  with white backgrounds
- After every change: show changed lines
- Deploy: git add . && git commit -m "..." && git push
