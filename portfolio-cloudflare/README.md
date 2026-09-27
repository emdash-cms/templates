# EmDash Portfolio Template (Cloudflare)

A visual portfolio for showcasing creative work, built with [EmDash](https://github.com/emdash-cms/emdash) and deployed on Cloudflare Workers with D1 and R2. Project pages with tag filtering, case study layouts, and an RSS feed for new work.

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/emdash-cms/templates/tree/main/portfolio-cloudflare)

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

- **Runtime:** Cloudflare Workers
- **Database:** D1
- **Storage:** R2
- **Framework:** Astro with `@astrojs/cloudflare`

## Local Development

```bash
pnpm install
pnpm dev
```

Open http://localhost:4321/_emdash/admin and complete the setup wizard. EmDash runs database migrations and applies the portfolio seed during setup. The site is available at http://localhost:4321.

## Deploying

```bash
pnpm wrangler login
pnpm deploy
```

The first deployment provisions the named D1 database and R2 bucket from `wrangler.jsonc`. See [Deploy to Cloudflare](https://docs.emdashcms.com/deployment/cloudflare/) for production setup, or use the deploy button above.

## See Also

- [Node.js variant](../portfolio) -- same template using SQLite and local file storage
- [All templates](../)
- [EmDash documentation](https://docs.emdashcms.com/)
