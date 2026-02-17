# Best List Bay

Static affiliate website featuring curated coffee gear and audiobook recommendations.

## Stack

- HTML, CSS, vanilla JavaScript
- Static assets in `/images`
- `live-server` for local development

## Local Development

```bash
npm install
npm run dev
```

The site starts on `http://localhost:3000`.

## Build

```bash
npm run build
```

Build output is written to `/public`:

- `index.html`
- `images/`
- `robots.txt`
- `sitemap.xml`

## Project Structure

- `/index.html`: Entire site UI, styles, behavior, and structured data
- `/images`: Product imagery
- `/robots.txt`: Crawler directives
- `/sitemap.xml`: Search engine sitemap
- `/vercel.json`: Vercel static hosting config

## Content Updates

1. Update product copy, pricing, and links in `/index.html`.
2. Keep affiliate disclosures visible and accurate.
3. When updating image filenames with spaces, URL-encode them in `/sitemap.xml` and structured data.
4. Update `lastmod` in `/sitemap.xml` when major content changes are published.

## Deployment

This repository is ready for static hosting (Vercel, GitHub Pages, Netlify, or similar).

For Vercel:

1. Import the repo.
2. Deploy as a static project.
3. Configure your domain (for example, `bestlistbay.com`).

## Compliance Note

The site contains affiliate links. Keep FTC-compliant disclosure language and Amazon Associates language current for your region and program terms.
