# AGENTS.md — verified-bases

## Shared Fleet Standard

Also read and follow the shared fleet-level agent standard at `../AGENTS.md`. Treat this repository as owned product code: protect production stability, keep changes scoped, verify work, and record durable follow-up tasks when something remains incomplete or blocked.

## Project

- **Stack**: Astro 5 + React 19 (`web/`), Go on Cloudflare Workers (`api/`), D1, KV, R2, Dodo Payments, Resend.
- **Local dev**: see `web/package.json` and `api/` README · `make deploy` for prod path (ask first).
- **Catalogue**: first Base not yet listed — edit `web/src/data/bases.ts` when adding inventory.
- **Do not** rotate payment/webhook secrets or provision Cloudflare resources without explicit approval.
