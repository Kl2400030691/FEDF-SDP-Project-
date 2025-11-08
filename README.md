# Certification Tracking Dashboard

This is a small static project that shows a table of certifications and highlights whether each certification is valid, expiring soon, or expired.

What's included
- `index.html` — the main page (improved semantics and JS for dynamic status badges)
- `styles.css` — clean, responsive CSS with accessible badges and a modern look

How to use
1. Open `index.html` in your browser (double-click or use `open index.html` on macOS).
2. The table will automatically evaluate rows that include a `data-expiration-date="YYYY-MM-DD"` attribute and add status badges.
3. To add more certificates, add rows to the table body in `index.html` using the same structure.

Notes
- Certificate links are placeholders — replace the `href` with your actual certificate URLs or files.
- The script calculates days left based on local dates. Dates should be in `YYYY-MM-DD` format.

If you'd like, I can add a small form to add new certificates from the UI, export/import CSV, or add sorting and filtering.
# FEDF-SDP-Project-