# Bot Happens — Combined Website

This static website combines the current published Wix positioning and offer details with the refreshed responsive multi-page design.

## Pages and assets
- `index.html` — Home, 6+ years positioning, platform expertise, service overview, published package summary
- `services.html` — Eight consulting service areas
- `about.html` — Origin story, point of view, and delivery approach
- `pricing.html` — Published packages and prices: Quick Audit $149, Process Refinement $999, Flow Setup $499
- `contact.html` — Contact information and existing Google Calendar booking link
- `styles.css` — Shared responsive design system
- `script.js` — Mobile navigation and safe form behavior

## Existing booking link
https://calendar.app.google/1hdJxSdcdtZKGLPu7

## Contact email
No email address is displayed yet. Add the approved public contact email only after the owner confirms the final choice. The inquiry form is not connected to a submission service and must not be presented as functional until tested end-to-end.

## Preview
Open `index.html` in a browser. All pages use relative links.

## Deploy to Cloudflare Pages
1. Create a GitHub repository named `bot-happens-site`.
2. Upload all files in this folder to the repository root.
3. In Cloudflare, open **Workers & Pages** → **Create application** → **Pages** → **Connect to Git**.
4. Authorize GitHub and select the repository.
5. Use no framework, leave the build command blank, and set the output directory to the repository root.
6. Deploy and test the `pages.dev` preview before connecting the custom domain.

## Domain safety
Keep `bot-happens.com` registered at Wix. Do not change nameservers until current DNS settings are checked and copied. Add the domain to Cloudflare Pages and follow the exact DNS instructions Cloudflare displays.

## Before launch
- Confirm public contact email and connect a working inquiry form.
- Test the Google Calendar booking link.
- Test all pages, navigation, mobile layout, and form behavior.
- Add privacy information if a form starts collecting or transmitting personal data.
- Publish only verified credentials, testimonials, and business claims.
