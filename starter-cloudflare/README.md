# EmDash Starter Template (Cloudflare)

A general-purpose starting point for building sites with [EmDash](https://github.com/emdash-cms/emdash) on Cloudflare Workers. Includes posts, pages, categories, and tags with minimal styling -- designed as a base you can build on rather than a finished theme.

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/emdash-cms/templates/tree/main/starter-cloudflare)

## What's Included

- Posts with category and tag archives
- Static pages via slug routing
- Seed data with demo content
- D1 database and R2 storage pre-configured

## Pages

| Page | Route |
|---|---|
| Homepage | `/` |
| All posts | `/posts` |
| Single post | `/posts/:slug` |
| Category archive | `/category/:slug` |
| Tag archive | `/tag/:slug` |
| Static pages | `/:slug` |
| 404 | fallback |

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

Open http://localhost:4321/_emdash/admin and complete the setup wizard. EmDash runs database migrations and applies the starter seed during setup. The site is available at http://localhost:4321.

## Deploying

```bash
pnpm wrangler login
pnpm deploy
```

The first deployment provisions the named D1 database and R2 bucket from `wrangler.jsonc`. See [Deploy to Cloudflare](https://docs.emdashcms.com/deployment/cloudflare/) for production setup, or use the deploy button above.

## See Also

- [Node.js variant](../starter) -- same template using SQLite and local file storage
- [All templates](../)
- [EmDash documentation](https://docs.emdashcms.com/)
