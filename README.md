# NEXUS — Beyond Human

A responsive cyborg-themed landing page concept with a futuristic HUD, CSS-built cybernetic hero illustration, animated signal details, responsive feature cards, protocol section, mission statement, and CTA.

## Run locally

No build tools are required.

1. Download or clone this folder.
2. Open `index.html` in a modern browser, or run a local server:
   ```bash
   python -m http.server 8000
   ```
3. Visit `http://localhost:8000`.

## Stack

- HTML5 semantic structure
- CSS3 (responsive layouts, custom cybernetic illustration, motion, reduced-motion support)
- Vanilla JavaScript (mobile navigation and scroll reveal)
- Google Fonts: Orbitron and Space Grotesk

## Responsive behavior

- Desktop: two-column hero, three-column feature grid, split content sections.
- Tablet: condensed spacing and two-column feature layout.
- Mobile: collapsible navigation, stacked sections, single-column cards, fluid typography.

## Customization

Edit colors in the `:root` variables at the top of `styles.css`. Replace the placeholder `hello@nexus.example` address in `index.html` before publishing.

## Publish to GitHub Pages

1. Create a public repository named `cybernetic-landing-page` on GitHub.
2. Upload `index.html`, `styles.css`, `script.js`, and this README.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. GitHub will show the published Pages URL in that section after deployment completes.

## Record a short demo

Open the page in Chrome, start a screen recording (Windows: `Win + Alt + R` if Xbox Game Bar is enabled, or use OBS), then scroll through the hero, Technology, Protocol, Mission, and CTA sections. Keep the recording around 30–45 seconds and show the mobile layout using DevTools device emulation if required.
