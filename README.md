# Bryan Dunleavy — Real Estate Lead Website

Static multi-page site focused on qualifying **buyer** and **seller** leads for Greenville / Upstate SC.

Live (after GitHub Pages is enabled): https://bryandunleavy.github.io/lead-funnel-/

## Pages
- `index.html` — Home / dual funnel
- `buy.html` — Buyer page + qualifying form
- `sell.html` — Seller valuation form
- `about.html` — Bio
- `contact.html` — General contact

## Make the forms work
1. Create a free form at [formspree.io](https://formspree.io) (or use Netlify Forms if you deploy there).
2. Replace `YOUR_FORM_ID` in `buy.html`, `sell.html`, and `contact.html` with your Formspree ID.
3. Submissions will email you with `lead_type` (Buyer/Seller) and the qualifying answers.

## Deploy with GitHub Pages
1. Repo Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main` / root
4. Save — site will be at https://bryandunleavy.github.io/lead-funnel-/

## Next upgrades
- Add your headshot on About
- Hook BoldTrail / your CRM via webhook instead of Formspree
- Add IDX/listings if you want search on-site
- Neighborhood pages for SEO (Travelers Rest, Simpsonville, etc.)
