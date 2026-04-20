# Student Name: Devin Veasna

## 1. My Assigned Work
* **styles.css** — Created a shared stylesheet for GearHub with custom CSS properties, base typography (Lato/Inter fonts), navbar styling, footer styling, and utility classes applied site-wide.
* **cart.html** — Refactored to use the shared `styles.css` and cleaned up inline styles.
* **index.html** — Refactored to use the shared `styles.css` and cleaned up inline styles.
* **login.html** — Refactored to use the shared `styles.css` and cleaned up inline styles.
* **payment-validation.html** — Refactored to use the shared `styles.css` and cleaned up inline styles.
* **payment.html** — Refactored to use the shared `styles.css` and cleaned up inline styles.
* **products.html** — Refactored to use the shared `styles.css` and cleaned up inline styles.
* **search_browse_listings.html** — Refactored to use the shared `styles.css` and cleaned up inline styles.

## 2. AI / LLM Usage
*Did you use an AI tool to help write or debug your code?*
* **What I asked the AI:** I asked Claude to help me implement a shared `styles.css` file by extracting the ~80 lines of duplicated inline CSS from all 7 HTML pages, consolidate them into one stylesheet with CSS custom properties, fix WCAG AA contrast issues on `.text-secondary` elements, add a consistent footer to all pages that were missing one, add a 6th category card to fill the homepage grid, and standardize spacing across pages.
* **How it helped & What I learned:** Claude helped me implement the `styles.css` file with `:root` custom properties and extracted all shared navbar, card, and footer rules into it. It then updated each HTML file to link the shared sheet and removed the duplicate `<style>` blocks, keeping only page-specific rules inline. I reviewed every edit to confirm the styles matched the originals and that no visual regressions were introduced. Through this I reinforced how CSS custom properties work as a theming layer and how WCAG AA contrast ratios are calculated — the default Bootstrap `.text-secondary` color `#6c757d` only achieves a 4.81:1 ratio on white, so overriding it to `#595c5f` brings it to ~6.75:1, which passes the AA standard for normal text.

## 3. Live Site Link
*Provide the GitHub Pages link to the specific page(s) you built.*
* **Live URL:** https://vcu-257.github.io/iteration-2-build-with-style-group-15/profile.html
