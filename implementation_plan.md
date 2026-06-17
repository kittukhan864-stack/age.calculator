# Implementation Plan - Redesign to Luxury Pastel Flowery Theme

We will transform the Age Calculator into an expensive-looking, whimsical light-themed website with:
- A "Fisheye" font style using the bulging display font **Oi** for numbers and headings, paired with the rounded premium font **Fredoka** for readable text.
- Tapping buttons styled as "expensive" pastel-colored pills with custom gradients, micro-glows, and interactive transitions.
- A dynamic, organic background showing elegant, hand-drawn white flowery doodles floating, swaying, and drifting.

## User Review Required

> [!NOTE]
> The background will shift from the dark glassmorphic neon aesthetic to a luxurious, high-end light pastel cream/lavender style.
> Flowery doodles will be rendered dynamically as white line-art SVGs that float across the screen.

## Proposed Changes

### [Age Calculator Redesign]

#### [MODIFY] [index.html](file:///C:/Users/kittu/.gemini/antigravity-ide/scratch/age-calculator/index.html)
- Replace Google Fonts link to import `Oi` and `Fredoka`.
- Update standard structural classes if necessary.
- Add a container (`#doodles-container`) in the background to hold the floating flowers.

#### [MODIFY] [styles.css](file:///C:/Users/kittu/.gemini/antigravity-ide/scratch/age-calculator/styles.css)
- Change variables for the new premium light-pastel theme:
  - Background: Cream/lilac gradient.
  - Text: Deep warm charcoal.
  - Buttons: Pastel lavender (`#d1c6ff`) and pastel mint (`#aef0da`).
- Update typography: apply `Oi` to the title and results numbers, and `Fredoka` as the body font.
- Redesign buttons as expensive-looking pastel pills with inner highlights, custom glows, and hover lifts.
- Add CSS animations for floating, swaying, and drifting flower SVGs.

#### [MODIFY] [script.js](file:///C:/Users/kittu/.gemini/antigravity-ide/scratch/age-calculator/script.js)
- Add a doodle generation script that programmatically injects random flower outline SVGs into the background.
- Apply random sizes, float speeds, rotation offsets, and horizontal sways to make the doodles feel natural and hand-crafted.

## Verification Plan

### Automated / Browser Verification
- Start the background server and run a `browser_subagent` to verify page rendering.
- Test the button animations and hover states.
- Capture screenshots to inspect the new pastel theme, doodle layouts, and chunky font style.
