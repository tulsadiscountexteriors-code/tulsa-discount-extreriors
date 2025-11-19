### Add static site scaffold

This PR adds a clean static site scaffold for Tulsa Discount Exteriors:
- Completed pages: index, services, gallery (hotlinked placeholders), testimonials, about, contact, 404
- Styles: css/styles.css (responsive, accessible-first minimal styles)
- Scripts: js/main.js (small navigation + year helper)
- Placeholder logo: assets/logo-placeholder.svg (use until you upload the real logo)
- sitemap.xml and robots.txt
- GitHub Actions workflow for GitHub Pages deployment

### Notes:
- Images: gallery images are currently hotlinked or use the placeholder. Upload images to /assets/ (or a zip to assets/raw/) and I will replace hotlinks with local images and add responsive srcset.
- Forms: GitHub Pages does not provide a server-side form endpoint. The contact form in contact.html is set up to work with Formspree (replace the action URL with your Formspree endpoint).