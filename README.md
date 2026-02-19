# Jon Blog (Static HTML + GitHub Pages)

This project is a simple static blog structure where every page is directly accessible as:

- `https://jonathanisonline.com/index.html`
- `https://jonathanisonline.com/contact.html`
- `https://jonathanisonline.com/tournament.html`

## Files

- `index.html`: home page
- `contact.html`: contact page
- `tournament.html`: first post
- `styles.css`: shared stylesheet
- `robots.txt`: crawl rules
- `sitemap.xml`: URL discovery for search engines

## Before Publishing

1. Replace placeholder copy in all HTML files with your raw content.
2. If your domain changes in the future, update these files:
- `index.html`
- `contact.html`
- `tournament.html`
- `robots.txt`
- `sitemap.xml`
3. Update email address and publish date details as needed.
4. Keep one `<h1>` per page and use clear `<h2>` sections.

## GitHub Pages Setup

1. Push this project to a GitHub repository.
2. In GitHub: `Settings` -> `Pages`.
3. Source: deploy from `main` branch, `/ (root)` folder.
4. Wait for the Pages URL to become active.
5. If using a custom domain, add it in GitHub Pages settings and update DNS records.

## SEO Checklist (Practical)

1. Unique page titles and meta descriptions for every page/post.
2. Canonical URL set per page.
3. Internal links between posts, home, and contact.
4. `sitemap.xml` and `robots.txt` present and valid.
5. Add alt text to every content image.
6. Keep pages fast: compress images and avoid heavy scripts.
7. Submit your sitemap in Google Search Console:
- `https://jonathanisonline.com/sitemap.xml`
8. Publish consistently and update old posts when needed.

## Add New Posts

1. Create a new file like `my-new-post.html`.
2. Add it to navigation and/or home page list.
3. Add its URL entry to `sitemap.xml`.
4. Update metadata (`title`, `description`, `canonical`, structured data).
