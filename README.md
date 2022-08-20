This is a minimal reproducible repo for cloudflare/wrangler2 issue [#1704](https://github.com/cloudflare/wrangler2/issues/1704).
created using `pnpm create next-app` from [Next.js Getting Started page](https://nextjs.org/docs/getting-started), basically it's an empty Next.js project.
using [pnpm](https://pnpm.io/installation) as package manager.
using node v16.17.0.
run with `pnpm wrangler pages dev -- pnpm dev` or `wrangler pages dev -- pnpm dev`
tried with several versions of wrangler:
- wrangler@2.0.26 (`pnpm add -g wrangler@2.0.26`)
- pre-release wrangler from [#1628](https://github.com/cloudflare/wrangler2/pull/1628)
- wrangler@0.0.0-61e3f00b (`pnpm add -g wrangler@0.0.0-61e3f00b`)
