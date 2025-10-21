Agaciro Motors - Static Netlify-ready Website

This package contains a static, single-page version of the Agaciro Motors site, ready for Netlify.
It includes a demo admin UI that stores vehicle data in the browser (localStorage), multilingual label toggle, and placeholders for Stripe and mobile-money payments.

Deploy to Netlify:
1. Unzip the package.
2. At Netlify, you can drag & drop the folder contents to Sites -> New site from Git -> 'Deploy site' (drop folder).
3. Or push to GitHub and connect the repository to Netlify.
4. The package includes netlify.toml and _redirects to support SPA routing (index.html fallback).

Notes:
- Admin image upload in the demo is local-only. To enable server uploads, replace the adminForm submit handler with a POST to your backend's /api/vehicles endpoint.
- Payment buttons call placeholders: connect Stripe (checkout/elements) or Flutterwave on the frontend and call backend endpoints defined earlier in the backend ZIP.

