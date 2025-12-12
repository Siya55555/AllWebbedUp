Landing page scaffold for AllWebbedUp

Files:
- `index.html` — single-page landing template with AllWebbedUp copy and contact
- `styles.css` — minimal, responsive styles using a CSS variable `--brand-color`

Quick setup
1. Phone & email: I updated the Call button to use `tel:1800714148` and the contact copy uses `admin@allwebbedup.com.au`. If you prefer an international `+61` format, tell me and I’ll change it.
2. Reviews link: update the `href` on `#reviews-button` to your actual Google review URL (e.g. `https://g.page/...`).
3. Brand colour: currently set in `styles.css` as `--brand-color: #00D449` (approximate match from your branding). Provide an exact hex if you want a precise match.

Form submission
- The form currently has demo client behaviour (shows an alert on submit). To make it live, either:
  - Set the `action` on the form to your backend endpoint and method, or
  - I can wire it to Formspree (or Netlify/Formbucket) and add user-friendly success/error UI.

Accessibility & best-practices
- Semantic markup, focus styles and strong colour contrast are present. Please confirm the review link and brand hex.

Next steps I can take for you
- Replace the reviews URL and switch `tel:` to `+61` format.
- Wire the form to Formspree and add serverless handling + success screen.
- Tweak spacing or move form to a right-column layout to match the original page exactly.

Tell me which of the above you want me to do next (I can patch files right away).
