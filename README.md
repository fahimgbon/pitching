# Pitching Workshop Deck

Single-file HTML presentation for UBC Product Sprint 2026 Workshop 4: Pitching.

## Files

- `index.html`: the full interactive slide deck
- `BitmojiRaisedHand.png`: host intro / profile slide
- `BitmojiWave.png`: activity + closing wave moments
- `BitmojiShrug.png`: reaction slide
- `BitmojiLaptop.png`: reflection / story slide
- `BitmojiKoreanHeart.png`: motif / closing sentiment slide
- `BitmojiOther.png`: general fallback bitmoji

## Open The Deck

Open `index.html` in any modern browser.

No build step is required. The only external dependencies are loaded from CDNs at runtime:

- Google Fonts
- Three.js r128

## Controls

- `←` / `→`: previous / next slide
- Click left / right half of the screen: previous / next slide
- Swipe left / right on touch devices: previous / next slide
- `N`: toggle speaker notes drawer
- `?`: open keyboard shortcuts
- Click the slide counter in the bottom-right: open the slide map drawer
- `Esc`: close notes, help, or slide map

## Current Customization Notes

- The generated SVG avatars were replaced with the real bitmoji PNGs currently in this folder.
- The slide map is a left-side drawer, grouped by section.
- Accessibility/readability adjustments were applied to the slides that were flagged in screenshots, especially:
  - `Recommended Pitch Structure`
  - `C: Context`
  - dark section headers / bookend compositions
  - opener text vs particle layout

## Remaining Asset Gap

The `You vs Them` slide was requested to use `bitmojithem`, but no matching file currently exists in this folder.

Right now that slide uses a subdued fallback built from the available bitmoji asset plus a `?` badge.

If you add the intended file, update the image on that slide in `index.html`.

## Editing Notes

- All presentation code, styling, slide content, and interactions live in `index.html`.
- Speaker notes are embedded directly in each slide as `.speaker-note`.
- Timer pills are clickable and run in-browser.
- The two Three.js moments are:
  - opener particle text
  - rotating wireframe object on the "Pitching Is a Game" section header
