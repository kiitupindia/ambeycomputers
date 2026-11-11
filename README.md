# Ambey Computers website

Responsive static website for Ambey Computers.

## Files
- `index.html` — page content, SEO metadata and LocalBusiness structured data
- `styles.css` — responsive styling for mobile, tablet and desktop
- `script.js` — mobile navigation and current footer year
- `favicon.svg` — browser icon

## Publish to ambeycomputers.in
1. Upload the contents of this folder to the document root (`public_html`) of your web hosting account.
2. Make sure `index.html` is directly inside the document root.
3. In your domain DNS, point the root domain and `www` hostname to the hosting provider's required records. Use the exact A/AAAA/CNAME values supplied by your host; do not guess them.
4. Enable HTTPS/SSL in your hosting control panel.
5. Set a redirect so one preferred hostname is canonical. The page metadata currently uses `https://www.ambeycomputers.in/`.

## Before launch
- The brief contained `wwe.ambeycomputers.in`; this build assumes the intended address is `www.ambeycomputers.in`.
- Confirm with your hosting provider whether the domain is connected and whether the `www` DNS record exists.
- Add actual opening hours, product brands, prices, warranty terms and any additional services only after confirming them.
- Test the call, WhatsApp, email and map links on a phone after publishing.

No hosting account, DNS records or domain settings have been changed by creating these files.


## Official Ambey Computers logo update
The site now uses the navy/orange/white circular and horizontal logo assets in `assets/`.
- Header: `assets/ambey-horizontal.svg`
- About and footer: `assets/ambey-circular-transparent.png`
- Browser icon: `assets/favicon.ico` and PNG touch icons

## Publish on Cloudflare Pages
Upload the contents of this ZIP to the same Cloudflare Pages project using the deployment method you already use. Keep `index.html` at the project root and retain the `assets/` folder. Do not upload the ZIP as a nested folder. After deployment, check the homepage on desktop and mobile, then verify the logo and favicon load.
