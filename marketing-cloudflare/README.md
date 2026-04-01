# EmDash Marketing Template (Cloudflare)

A conversion-focused landing page template built with [EmDash](https://github.com/emdash-cms/emdash) and deployed on Cloudflare Workers with D1 and R2. Modular content blocks let you assemble pages from reusable sections without touching code.

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/emdash-cms/templates/tree/main/marketing-cloudflare)

![Marketing template homepage](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/marketing/latest/homepage-light-desktop.jpg)

## What's Included

- Hero section with CTAs
- Feature grid
- Testimonials
- Pricing cards
- FAQ accordion
- Contact form with validation
- SEO metadata and JSON-LD
- Dark/light mode

## Pages

| Page | Route |
|---|---|
| Homepage | `/` |
| Pricing | `/pricing` |
| Contact | `/contact` |
| 404 | fallback |

## Screenshots

| | Desktop | Mobile |
|---|---|---|
| Light | ![homepage light desktop](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/marketing/latest/homepage-light-desktop.jpg) | ![homepage light mobile](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/marketing/latest/homepage-light-mobile.jpg) |
| Dark | ![homepage dark desktop](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/marketing/latest/homepage-dark-desktop.jpg) | ![homepage dark mobile](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/marketing/latest/homepage-dark-mobile.jpg) |

## Infrastructure

- **Runtime:** Cloudflare Workers
- **Database:** D1
- **Storage:** R2
- **Framework:** Astro with `@astrojs/cloudflare`

## Local Development

```bash
pnpm install
pnpm bootstrap
pnpm dev
```

## Deploying

```bash
pnpm deploy
```

Or click the deploy button above to set up the project in your Cloudflare account.

## See Also

- [Node.js variant](../marketing) -- same template using SQLite and local file storage
- [All templates](../)
- [EmDash documentation](https://github.com/emdash-cms/emdash/tree/main/docs)
