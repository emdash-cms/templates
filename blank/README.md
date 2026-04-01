# EmDash Blank Template

The most minimal EmDash template. A single index page with [EmDash](https://github.com/emdash-cms/emdash) wired up and nothing else. No seed data, no layouts, no components -- start from scratch with full control.

## What's Included

- Single `index.astro` page
- EmDash integration configured
- TypeScript and live config boilerplate

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

## See Also

- [All templates](../)
- [EmDash documentation](https://github.com/emdash-cms/emdash/tree/main/docs)
