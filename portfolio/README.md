# EmDash Portfolio Template

A visual portfolio for showcasing creative work, built with [EmDash](https://github.com/emdash-cms/emdash). Runs on any Node.js server with SQLite and local file storage. Project pages with tag filtering, case study layouts, and an RSS feed for new work.

![Portfolio template work page](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/portfolio/latest/work-light-desktop.jpg)

## What's Included

- Project grid with hover effects
- Tag-based filtering on the work page
- Individual project pages with galleries
- About and contact pages
- RSS feed for new projects
- SEO metadata and JSON-LD
- Dark/light mode

## Pages

| Page | Route |
|---|---|
| Homepage | `/` |
| Work listing | `/work` |
| Single project | `/work/:slug` |
| About | `/about` |
| Contact | `/contact` |
| RSS | `/rss.xml` |
| 404 | fallback |

## Screenshots

| | Desktop | Mobile |
|---|---|---|
| Light | ![work light desktop](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/portfolio/latest/work-light-desktop.jpg) | ![work light mobile](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/portfolio/latest/work-light-mobile.jpg) |
| Dark | ![work dark desktop](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/portfolio/latest/work-dark-desktop.jpg) | ![work dark mobile](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/portfolio/latest/work-dark-mobile.jpg) |

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

See the [Cloudflare variant](../portfolio-cloudflare) for a version that deploys to Cloudflare Workers with D1 and R2.

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/emdash-cms/templates/tree/main/portfolio-cloudflare)

## See Also

- [All templates](../)
- [EmDash documentation](https://github.com/emdash-cms/emdash/tree/main/docs)
