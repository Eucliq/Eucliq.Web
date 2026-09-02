# Eucliq

The public company landing page for Eucliq s. r. o.

## Hosting

This is a dependency-free static site deployed as a **Cloudflare Worker with
static assets**:

- Build command: none
- Deploy command: `npx wrangler deploy`
- Production branch: `main`

`wrangler.jsonc` limits the deploy to `public`, so repository metadata and
source files are never exposed as static assets. Cloudflare's free Worker plan
is sufficient for this company website and includes SSL and custom domains.
Vercel is a good option for a future dynamic Next.js application, but is
unnecessary for this static company page.

## Domains and localization

Connect both custom domains to the Pages project:

| Domain | Default language |
| --- | --- |
| [`eucliq.com`](https://eucliq.com) | English |
| [`eucliq.sk`](https://eucliq.sk) | Slovak |
| [`eucliq.eu`](https://eucliq.eu) | English |

The page selects the language from the domain on a visitor's first visit.
Visitors may change it using the language control; their choice is saved in
their browser.

## Local preview

Open `public\index.html` directly in a browser, or use any static HTTP server.
Eucliq company website
