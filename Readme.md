# CSS - Laundry Services Responsive Issue

A responsive laundry services landing page built with plain HTML and CSS (no Bootstrap).

## What was fixed
- **Navbar**: uses `display: flex` (no inline), nav link text, logo and username shrink on tablet, and links are hidden on mobile (only Logo + Username remain).
- **Hero Section**: heading/paragraph text and the image get smaller on tablet, and on mobile the layout switches to `flex-direction: column` with the image stacked below the text.

## Files
- `index.html` – page markup
- `style.css` – styles + media queries (tablet `max-width: 1024px`, mobile `max-width: 600px`)
- `washing-machine.png` – add your washing machine image here (or update the `src` in `index.html`)

## Run
Open `index.html` in a browser, or use the Live Server extension in VS Code.
