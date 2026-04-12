# EmDash Templates

> **This repo is auto-synced from [emdash-cms/emdash](https://github.com/emdash-cms/emdash).** Please open issues and PRs on the main repo, not here. PRs from external contributors will be closed automatically.

Starter templates for [EmDash](https://github.com/emdash-cms/emdash), a full-stack TypeScript CMS built on Astro. Each template ships with seed data so you can see a working site immediately.

## Quick Start

The fastest way to get started is the CLI:

```bash
npm create emdash@latest
```

Or pick a Cloudflare template below and deploy it in one click.

## Templates

### Blog

A clean blog with posts, categories, tags, full-text search, and RSS. Includes reading time estimates, a featured post hero, and dark/light mode.

[![Blog template homepage](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/blog/latest/homepage-light-desktop.jpg)](./blog-cloudflare)

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/emdash-cms/templates/tree/main/blog-cloudflare)

[Cloudflare variant](./blog-cloudflare) | [Node.js variant](./blog)

---

### Marketing

A landing page template with modular content blocks: hero, features, testimonials, pricing cards, FAQ accordion, and a contact form.

[![Marketing template homepage](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/marketing/latest/homepage-light-desktop.jpg)](./marketing-cloudflare)

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/emdash-cms/templates/tree/main/marketing-cloudflare)

[Cloudflare variant](./marketing-cloudflare) | [Node.js variant](./marketing)

---

### Portfolio

A visual portfolio for showcasing creative work. Project grid with tag filtering, individual case study pages, RSS feed, and dark/light mode.

[![Portfolio template homepage](https://raw.githubusercontent.com/emdash-cms/emdash/main/assets/templates/portfolio/latest/work-light-desktop.jpg)](./portfolio-cloudflare)

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/emdash-cms/templates/tree/main/portfolio-cloudflare)

[Cloudflare variant](./portfolio-cloudflare) | [Node.js variant](./portfolio)

---

### Starter

A general-purpose starting point with posts, pages, categories, and tags. Less opinionated than the themed templates -- a good base if you want to build your own design.

[Cloudflare variant](./starter-cloudflare) | [Node.js variant](./starter)

---

### Blank

The most minimal template. A single index page with EmDash wired up and nothing else. Start here if you want full control from the beginning.

[View template](./blank)

## Variants

Each template (except blank) comes in two variants:

| Variant | Database | Storage | Adapter |
|---|---|---|---|
| **Node.js** | SQLite (local file) | Local filesystem | `@astrojs/node` |
| **Cloudflare** | D1 | R2 | `@astrojs/cloudflare` |

The Cloudflare variants include a `wrangler.jsonc` and can be deployed with the button above or via `wrangler deploy`. The Node.js variants run anywhere you can run a Node process.

## Local Development

```bash
# Copy a template
cp -r blog my-site
cd my-site

# Install dependencies
pnpm install

# Initialise the database and seed demo content
pnpm bootstrap

# Start the dev server
pnpm dev
```

Open http://localhost:4321 to see your site and http://localhost:4321/_emdash/admin for the CMS.

## Learn More

- [EmDash documentation](https://github.com/emdash-cms/emdash/tree/main/docs)
- [EmDash repository](https://github.com/emdash-cms/emdash)
