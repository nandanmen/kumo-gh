---
"@cloudflare/kumo": patch
---

Fix `kumo` CLI bin resolution in repo checkouts so `pnpm install` doesn't warn when `dist/` hasn't been built yet.
