# Sawyer Counseling Static Website

This folder is upload-ready for a static host such as GitHub Pages, Netlify, Vercel, or a simple web server. No WordPress or database is required.

## What changed

- Added crawlable static service pages for Florida telehealth SEO and conversion.
- Added a static `/resources/` library as the blog workaround. Each resource is a normal HTML page that can rank, support service pages with internal links, and stay visually consistent with the site.
- Added `robots.txt` and `sitemap.xml`.
- Added canonical, Open Graph, Service, FAQ, Article, and ProfessionalService schema where appropriate.
- Updated homepage navigation/footer to point to hub pages without turning the homepage into a giant blog directory.

## Upload instructions

Upload the contents of this folder to the repository root for `www.sawyercounseling.com`. Keep folder names and `index.html` files intact so clean URLs like `/couples-therapy-florida/` work.

## No-WordPress resource workflow

To add a new article, duplicate one folder inside `/resources/`, update its `index.html`, then add the new URL to `/resources/index.html` and `sitemap.xml`.

## Important live checks after upload

1. Visit `/robots.txt` and `/sitemap.xml` and confirm both load.
2. Test the free consultation button.
3. Submit `https://www.sawyercounseling.com/sitemap.xml` in Google Search Console.
4. Confirm insurance/rates are still accurate before sending traffic.
