# Visual Sentinel

> 6-layer website monitoring: uptime, performance, SSL, DNS, visual regression, and content changes.

Visual Sentinel monitors websites across six layers in a single product. It renders pages in a real Chromium browser and compares screenshots pixel-by-pixel to catch what traditional uptime monitors miss: broken CSS, missing images, or layout shifts that still return HTTP 200 OK.

Use it for one important site, a SaaS product, or an agency portfolio with dozens of client sites.

## Links

- Website: https://visualsentinel.com
- Pricing: https://visualsentinel.com/pricing (Free plan, Solo $6/mo, 7-day trial without card)
- Documentation: https://docs.visualsentinel.com
- Status page: https://status.visualsentinel.com
- Changelog: https://visualsentinel.com/changelog
- Blog: https://visualsentinel.com/blog

## What lives here

This organization hosts the public developer surfaces for Visual Sentinel:

- [`mcp-server`](https://github.com/VisualSentinel/mcp-server): the official Model Context Protocol server with 16 monitor, incident, status-page, and diagnostic tools
- [`claude-plugins`](https://github.com/VisualSentinel/claude-plugins): three Claude Code monitoring skills, three slash commands, and the Visual Sentinel marketplace
- [`openapi`](https://github.com/VisualSentinel/openapi): the public OpenAPI 3.1 specification for the Visual Sentinel REST API
- [`.github`](https://github.com/VisualSentinel/.github): this organization profile and shared community files

## For developers

- API reference: https://docs.visualsentinel.com
- 10 notification channels: Email, WhatsApp, Slack, Discord, Telegram, Microsoft Teams, PagerDuty, OpsGenie, webhooks, and Prometheus
- Public probe user-agent: `VisualSentinelBot/2.0 (+https://visualsentinel.com/bot)` (allowlist this in your WAF if Visual Sentinel is checking your site)
- Bot reference and current probe details: https://visualsentinel.com/bot
- Server monitoring: CPU, RAM, disk, and network in the same dashboard as website checks, with optional incident correlation between the two

## Contact

- Support: support@visualsentinel.com
- Sales: sales@visualsentinel.com
- Founder: [Rai Ansar](https://x.com/iraiansar) ([@raiansar](https://github.com/raiansar))
