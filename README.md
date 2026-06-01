# Greenwood Social — MCP SDK

Public SDK for Greenwood Social's hosted MCP server. Connect Claude, Claude Code, or Cursor to 9 social platforms via OAuth.

> **Open SDK, hosted platform.** This repository (the SDK and integration docs) is open source. The platform integrations it talks to — OAuth, publishing, scheduling, and analytics across every supported network — are hosted by Greenwood Social. You don't run or maintain the servers; you connect to them.

This is **not** an open-source MCP server. It's a public SDK for a closed, hosted service — the same model Stripe, Anthropic, AWS, and Vercel use to publish substantial SDKs for hosted products.

## Quick start

1. **Get access.** Sign up and create an API key / OAuth connection at [greenwoodapps.com](https://greenwoodapps.com).
2. **Install:** `npx skills add greenwoodapps/social-skill` (the vercel-labs `skills` installer works across many agent platforms, not just Anthropic's).
3. **Connect.** Authorize the social accounts you want to manage, and start driving them from Claude, Claude Code, or Cursor.

## What you can do

Once connected, your agent can draft, schedule, and publish posts, pull analytics, and manage content across all supported platforms — through a single OAuth-backed MCP connection. Built by a Cowork user for Cowork users: a non-technical creator can live inside it, while it stays fully agent-callable.

## Platform support

| Platform   | Publish | Schedule | Analytics |
|------------|---------|----------|-----------|
| LinkedIn   | yes     | yes      | yes       |
| Instagram  | yes     | yes      | yes       |
| X          | yes     | yes      | yes       |
| TikTok     | yes     | yes      | yes       |
| Facebook   | yes     | yes      | yes       |
| Pinterest  | yes     | yes      | yes       |
| Threads    | yes     | yes      | yes       |
| Bluesky    | yes     | yes      | yes       |
| YouTube    | yes     | yes      | yes       |

## Learn more

- Cowork integration: [greenwoodapps.com/cowork](https://greenwoodapps.com/cowork)
- Website and sign-up: [greenwoodapps.com](https://greenwoodapps.com)

---

_Skeleton README — work in progress. The public MCP server release is tracked separately._
