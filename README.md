# Ambey Computers — Cloudflare Pages Website

This is a complete static website rebuild using the approved **Premium Circuit Edition** visual identity.

## Deploy to Cloudflare Pages

1. Download and extract this ZIP.
2. In Cloudflare Dashboard, open **Workers & Pages → Pages → ambey-computers**.
3. Choose **Create deployment** / **Upload assets** (Direct Upload).
4. Upload the extracted folder contents (the folder containing `index.html`, `_headers`, `assets/`, etc.).
5. Deploy. Do not upload the ZIP as a single website file.
6. Test `https://ambeycomputers.in` and `https://www.ambeycomputers.in`.

## Project structure

- `index.html` — responsive single-page business website
- `styles.css` — local CSS, no external framework or font dependency
- `script.js` — tiny local navigation script
- `assets/` — current circular master, horizontal logo, favicon and social image
- `_headers` — security headers and long-lived asset caching
- `robots.txt`, `sitemap.xml`, `site.webmanifest` — search and install metadata
- `404.html` — branded not-found page

## Performance and security choices

- No third-party JavaScript, analytics, trackers, frameworks or remote font requests.
- WebP is used for primary logo placement with PNG fallback where appropriate.
- Responsive layout, reduced-motion support, lazy loading for below-the-fold logo.
- Cloudflare `_headers` adds CSP, HSTS, anti-framing, MIME sniffing and referrer protections.
- Immutable caching for `/assets/*`; HTML revalidates.

## Important DNS note

Keep existing email MX, SPF, DKIM and DMARC DNS records when configuring the website domain. Do not change mail records to deploy this static site.

## Contact details carried forward from the previous site

Phone / WhatsApp: +91 91613 56994  
Email: care@ambeycomputers.in  
Address: Near Ambey Library, Belwa, Ranipur Rajmo, Mohammadpur, Azamgarh, Uttar Pradesh 276205, India.

If any business detail changes, update `index.html` and the JSON-LD block together.
