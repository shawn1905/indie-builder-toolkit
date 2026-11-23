# Indie Builder Toolkit — Cloudflare Pages Static Micro-Tool (Direction 4)

Zero-backend, zero-cost static web tool built for **Cloudflare Pages** (commercial use allowed, unlimited static bandwidth, zero maintenance):

1. **2026 Indie SaaS & Digital Product MoR Fee Calculator** — compares Stripe, Polar.sh, Paddle, Lemon Squeezy, Gumroad Direct/Discover, and Apify Store PPE.
2. **Remote MCP Server Config Generator** — generates ready-to-paste JSON for Claude Desktop / Cursor / Windsurf / VS Code, preloaded with all 6 of our paid Apify Standby Remote MCP Servers to drive organic SEO traffic directly into our monetization funnel.

## Zero-Cost Deploy to Cloudflare Pages

1. Free Cloudflare account: https://dash.cloudflare.com/sign-up
2. Deploy via CLI:
   ```bash
   npx wrangler login
   npx wrangler pages deploy /data/workspace/projects/mcp-mor-toolkit-web --project-name=indie-builder-toolkit
   ```
   *(Or drag-and-drop `/data/workspace/projects/mcp-mor-toolkit-web` directly in Cloudflare Dashboard → Workers & Pages → Create → Pages → Direct Upload.)*
