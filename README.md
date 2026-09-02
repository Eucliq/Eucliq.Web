# Eucliq

The public company landing page for Eucliq s. r. o.

## Hosting

This is a dependency-free static site designed for **Cloudflare Pages**:

- Build command: `exit 0`
- Build output directory: `public`
- Production branch: `main`

Cloudflare Pages is the recommended host for this site: its free plan includes
static hosting, SSL, custom domains, and Cloudflare DNS with no fixed monthly
cost. Vercel is a good option for a future dynamic Next.js application, but is
unnecessary for this static company page.

## Domains and localization

Connect both custom domains to the Pages project:

| Domain | Default language |
| --- | --- |
| `eucliq.com` | English |
| `eucliq.sk` | Slovak |

The page selects the language from the domain on a visitor's first visit.
Visitors may change it using the language control; their choice is saved in
their browser.

## Local preview

Open `public\index.html` directly in a browser, or use any static HTTP server.
Eucliq company website
