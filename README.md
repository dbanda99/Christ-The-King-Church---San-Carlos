# San Carlos Subdomain Package

This is a standalone static site package for the subdomain:

- `sancarlos.christthekinglaredotx.org`

## Included pages
- `index.html`
- `news.html`
- `bulletin.html`
- `contact.html`

These pages were copied from the main site and kept visually/functionally aligned with the current project.
Links to pages that are not included in this subdomain package (like Worship, Sermons, Ministries, Giving, etc.) were redirected back to the main domain:

- `https://christthekinglaredotx.org`

## If you are using GitHub Pages
1. Create a separate repo for this subdomain (recommended).
2. Upload the contents of this folder as the root of that repo.
3. Enable GitHub Pages for that repo.
4. Keep the included `CNAME` file.
5. In your DNS, add a CNAME record:
   - Host/Name: `sancarlos`
   - Target/Points to: `dbanda99.github.io`

## Notes
- The `assets/` folder is included so the pages render the same as the main site.
- The contact form remains the same demo behavior as the current project.
- Language switching (EN/ES) remains enabled.


Updated v2:
- Unified footer on all pages
- Local-only nav links (Home, News, Bulletin, Contact Us, Donate)
- Added local giving pages
- Added Homepage button to the main Laredo church site
