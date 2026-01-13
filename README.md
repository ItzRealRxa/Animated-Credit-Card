# Animated Credit Card

Animated Credit Card is a lightweight, responsive front-end demo that shows an animated, interactive credit card UI using HTML, CSS, and JavaScript. As users type card details into the form, the card updates in real time and includes flip/animation effects for a modern UI demonstration.

## Homepage Screenshot
A screenshot of the project's homepage is shown below. To update this image later, replace the file at `assets/homepage.png` (instructions below).

![Homepage Screenshot](./assets/homepage.png)

## Features
- Live-updating card preview while typing (number, name, expiry, CVC)
- Card flip animation (front ↔ back) for CVC entry
- Simple input masking and basic validation
- Responsive layout that works on mobile and desktop
- Pure HTML/CSS/JavaScript — no frameworks required

## Built with
- HTML
- CSS (animations & styling)
- JavaScript (DOM updates & input handling)

## Getting started
1. Clone the repo
   ```bash
   git clone https://github.com/ItzRealRxa/Animated-Credit-Card.git
   ```

2. Open locally
   - Option A: Open `index.html` in your browser
   - Option B: Run a simple static server (recommended for some browsers)
     - Python 3: `python -m http.server 8000`
     - Then open `http://localhost:8000`

## Usage
- Type a card number to see it reflected on the card.
- Enter cardholder name and expiry; the card preview updates.
- Focus the CVC input to flip the card to the back.

## Project structure
- `index.html` — demo page and form
- `css/` or `styles.css` — styling and animations
- `js/` or `script.js` — input handling and UI updates
- `assets/` — images, demo GIFs, icons (place homepage screenshot at `assets/homepage.png`)

## How to update the homepage image (easy)
1. Save your homepage screenshot as `homepage.png`.
2. Add or replace the file at `assets/homepage.png` in this repository.

Quick ways to update the image:
- From your machine (command line):
  ```bash
  cp /path/to/your/homepage.png assets/homepage.png
  git add assets/homepage.png
  git commit -m "Update homepage screenshot"
  git push
  ```
- Using GitHub web UI:
  1. Open the `assets` folder in this repository.
  2. Click "Add file" → "Upload files" and select your `homepage.png`.
  3. Commit the change to `main`.

The README displays `./assets/homepage.png`. If you prefer a different filename or location, update the image path in `README.md`.

## Customization
- Adjust colors and sizes in the CSS file.
- Modify animation timing in the CSS keyframes.
- Extend validation logic in `script.js` (e.g., Luhn check or card brand detection).

## Accessibility & Responsiveness
- Inputs should be labeled for screen readers — consider adding ARIA attributes where needed.
- The layout is responsive; tweak breakpoints in CSS to match your design needs.

## Contributing
- Open an issue to propose changes or report bugs.
- Create a branch for your feature/fix and open a pull request.
- Describe your change and include screenshots or gifs for UI changes.

## License
Specify a license (MIT recommended). If you want MIT, I can add a LICENSE file and badge.

## Authors
- ItzRealRxa — https://github.com/ItzRealRxa

## Contact
- Open issues or contact via GitHub: https://github.com/ItzRealRxa
