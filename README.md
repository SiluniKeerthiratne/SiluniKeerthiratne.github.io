# SiluniKeerthiratne.github.io

Personal academic homepage. Plain HTML and CSS, no build step.

## Files
- `index.html`: all content
- `style.css`: styling (colours are CSS variables at the top; light/dark follows the OS)
- `assets/`: photo, CV, thesis

## Swap assets
Drop these into `assets/` (keep the names):
- `profile.jpg`: square photo, ~400×400 px. Until it exists, `profile-placeholder.svg` is shown.
- `cv.pdf`: CV
- `thesis.pdf`: thesis

## Edit content
- Each section is a `<section id="...">` in `index.html`. Edit the text in place.
- Links with an empty `href=""` are hidden automatically. Fill in the **Dataset** and **Code** buttons in the Research card to show them.
- The "Seeking a PhD in ..." sentence in About is hidden. Fill in the area and intake, then delete its `hidden` attribute.
- Accent colour: change `--accent` in `style.css`.

## Preview locally
    python3 -m http.server 8000

Then open http://localhost:8000.
