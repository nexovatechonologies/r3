# ROYALNEST India — Real Estate Portfolio Prototype

A responsive Indian real-estate discovery website built with React, Vite, Three.js, GSAP, ScrollTrigger and Lenis.

## What is included
- Indian real-estate positioning with prices displayed in Indian rupees (₹)
- State / Union Territory filter covering all 28 states and 8 Union Territories
- Sample listings across apartments, independent houses and villas, including modest and mid-range homes as well as premium homes
- Original generated residential exterior image assets stored locally in `public/images`
- Sticky primary navigation and a secondary quick-navigation bar
- Property-type, state, budget and keyword filters
- Property detail modal, favourites shortlist and validated demo enquiry form
- INR home-loan EMI estimator
- Subtle GSAP section reveals, Lenis smooth scrolling and a lightweight Three.js ambience layer
- Responsive mobile layout and reduced-motion support

## Run locally
1. Install Node.js 20.19+ or 22.12+.
2. Extract the ZIP and open the `royalnest_luxury_real_estate` folder in Cursor or VS Code.
3. Open a terminal in that folder.
4. Run `npm install`.
5. Run `npm run dev` and open the localhost URL printed by Vite.

## Production build
- `npm run build`
- `npm run preview`

The production files are generated in `dist/`. Deploy that folder to a static host such as Netlify, Vercel or Cloudflare Pages.

## Important demo limitations
- This is a front-end portfolio concept. All property names, prices, areas, amenities and listing details are fictional demonstration data, not verified offers or current market valuations.
- The generated house photographs are illustrative architectural visuals, not photographs of the listed properties.
- The enquiry form validates in the browser only; it does not send messages to an agent or CRM. Connect a secure backend before accepting real enquiries.
- The EMI estimator uses an illustrative 8.5% annual interest rate and excludes taxes, insurance, processing fees and lender-specific conditions.
- Replace demo content, legal disclosures, contact details and imagery with verified material before commercial launch.


## GitHub Pages deployment

This project is configured for `https://nexovatechonologies.github.io/royalnest/`.

1. Put the **contents** of this project folder at the root of the `royalnest` GitHub repository. `package.json`, `index.html`, `src/`, `public/` and `vite.config.js` must be at repository root.
2. In GitHub, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
3. Push the project to the `main` branch.
4. Open the repository's **Actions** tab and wait for **Deploy RoyalNest to GitHub Pages** to finish successfully.
5. Visit `https://nexovatechonologies.github.io/royalnest/`.

Do not select “Deploy from a branch” with the repository root. The included workflow builds the Vite app and publishes the generated `dist/` folder.
