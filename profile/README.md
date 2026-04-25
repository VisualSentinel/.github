# Visual Sentinel

> 6-layer website monitoring: uptime, performance, SSL, DNS, visual regression, and content changes.

Visual Sentinel monitors websites across six layers in a single product. It renders pages in a real Chromium browser and compares screenshots pixel-by-pixel to catch what traditional uptime monitors miss: broken CSS, missing images, or layout shifts that still return HTTP 200 OK.

Works equally well for a single personal site, a small SaaS, or an agency with hundreds of client sites.

## Links

- Website: https://visualsentinel.com
- Pricing: https://visualsentinel.com/pricing (Free plan, Solo $6/mo, 7-day trial without card)
- Documentation: https://docs.visualsentinel.com
- Status page: https://status.visualsentinel.com
- Changelog: https://visualsentinel.com/changelog
- Blog: https://visualsentinel.com/blog

## What lives here

This organization hosts the open-source pieces of the Visual Sentinel platform:

- Status page templates and theme starters
- CLI tools and developer SDKs
- Public docs source
- Example monitor configurations and integration recipes
- Claude Code skills for VisualSentinel automation

(Repositories will be published here as they reach a usable state.)

## For developers

- API reference: https://docs.visualsentinel.com
- 11 notification channels: Email, WhatsApp (rare in monitoring), SMS, Slack, Discord, Telegram, Microsoft Teams, PagerDuty, OpsGenie, webhooks, Prometheus
- Public probe user-agent: `VisualSentinelBot/2.0 (+https://visualsentinel.com/bot)` (allowlist this in your WAF if Visual Sentinel is checking your site)
- IP ranges for WAF allowlisting: https://visualsentinel.com/bot/ips
- Server monitoring: CPU, RAM, disk, and network in the same dashboard as website checks, with optional incident correlation between the two

## Contact

- Support: support@visualsentinel.com
- Sales: sales@visualsentinel.com
- Founder: [Rai Ansar](https://x.com/iraiansar) ([@raiansar](https://github.com/raiansar))