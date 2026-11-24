# THE WellBeing website

A responsive, bilingual (English/Malayalam) static website starter for THE WellBeing.

## Files
- `index.html` — complete one-page site
- `assets/styles.css` — responsive styling and visual identity
- `assets/site.js` — language switch, mobile navigation and enquiry-form placeholder

## Preview locally
Open `index.html` in a browser. For best results, run a local static server from this folder:
`python -m http.server 8000`
Then visit `http://localhost:8000`.

## Before publishing
1. Confirm the logo and brand assets.
2. Replace contact-detail placeholders with verified phone, email, address and social links.
3. Add real professional profiles only after confirming qualifications, registrations and service scope.
4. Connect the enquiry form to a secure form endpoint or backend. The current form is front-end only and does not transmit or store enquiries.
5. Review all English and Malayalam content with the responsible professionals.
6. Add final privacy, terms, cancellation and professional disclaimer pages.
7. Test the website on mobile, tablet and desktop.
8. Configure `wellbeing.thegroupbusiness.com` to point to the selected hosting provider and enable HTTPS.

## Deployment
This is a static website and can be deployed to GitHub Pages or another static host. If deploying to GitHub Pages, upload the contents of this folder to the repository's publishing root (not the parent folder). Configure the custom domain `wellbeing.thegroupbusiness.com` in the host settings and add the corresponding DNS record at your DNS provider.

## Important
The appointment enquiry form is intentionally not connected to a live service. Do not publish it as a working booking system until a secure endpoint, notification recipient, consent wording and privacy process have been configured.
