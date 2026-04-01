# EmDash Blog Template

A clean, minimal blog built with [EmDash](https://github.com/emdash-cms/emdash). Runs on any Node.js server with SQLite and local file storage.

![Blog template homepage](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/blog/latest/homepage-light-desktop.jpg)

## What's Included

- Featured post hero on the homepage
- Post archive with reading time estimates
- Category and tag archives
- Full-text search
- RSS feed
- SEO metadata and JSON-LD
- Dark/light mode
- Audit log plugin

## Pages

| Page | Route |
|---|---|
| Homepage | `/` |
| All posts | `/posts` |
| Single post | `/posts/:slug` |
| Category archive | `/category/:slug` |
| Tag archive | `/tag/:slug` |
| Search | `/search` |
| Static pages | `/pages/:slug` |
| 404 | fallback |

## Screenshots

| | Desktop | Mobile |
|---|---|---|
| Light | ![homepage light desktop](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/blog/latest/homepage-light-desktop.jpg) | ![homepage light mobile](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/blog/latest/homepage-light-mobile.jpg) |
| Dark | ![homepage dark desktop](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/blog/latest/homepage-dark-desktop.jpg) | ![homepage dark mobile](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/blog/latest/homepage-dark-mobile.jpg) |

## Infrastructure

- **Runtime:** Node.js
- **Database:** SQLite (local file)
- **Storage:** Local filesystem
- **Framework:** Astro with `@astrojs/node`

## Getting Started

```bash
pnpm install
pnpm bootstrap
pnpm dev
```

Open http://localhost:4321 for the site and http://localhost:4321/_emdash/admin for the CMS.

## Want Cloudflare Instead?

See the [Cloudflare variant](../blog-cloudflare) for a version that deploys to Cloudflare Workers with D1 and R2.

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/emdash-cms/templates/tree/main/blog-cloudflare)

## See Also

- [All templates](../)
- [EmDash documentation](https://github.com/emdash-cms/emdash/tree/main/docs)
