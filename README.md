# Pauze Portfolio

**Website:** [pauzeweb.devs.surf](https://pauzeweb.devs.surf)

A responsive, static developer portfolio for Pauze. Built with a considered dark-matte visual system, charcoal surfaces, restrained blue accents and subtle motion.

## Run locally

No build step or package installation is required. Open `index.html` in a browser, or serve the folder with any static HTTP server.

## Deployment

This site is designed for GitHub Pages.

1. Open **Settings → Pages** in this repository.
2. Select **Deploy from a branch**.
3. Choose `main` and the `/ (root)` folder, then save.
4. Under **Custom domain**, enter `pauzeweb.devs.surf` and save.
5. Configure the DNS records for `pauzeweb.devs.surf` with your domain provider using GitHub Pages' current custom-domain instructions.
6. Once DNS has propagated and GitHub Pages has issued the certificate, enable **Enforce HTTPS**.

The custom domain is documented here as the intended website address. A successful live deployment depends on the GitHub Pages and DNS settings above.

## Structure

- `index.html` — semantic page structure and project content
- `styles.css` — responsive visual system and CSS-built project artwork
- `script.js` — mobile navigation, reveal-on-scroll and footer year
- `favicon.svg` — Pauze monogram favicon

## Personalise

Update project descriptions and repository links in `index.html`. The site uses no JavaScript framework or external component library.

## Accessibility

Includes semantic landmarks, keyboard-operable navigation, visible focus styles, reduced-motion support and responsive layouts.
