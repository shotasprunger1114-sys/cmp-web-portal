# CMP Web Portal

**Client intake form + internal project tracker for Create More Productions web services.**

## URLs
- **Client Form:** https://shotasprunger1114-sys.github.io/cmp-web-portal/
- **Dashboard:** https://shotasprunger1114-sys.github.io/cmp-web-portal/dashboard.html

## Setup: Discord Webhook (one-time, 2 min)

1. Open Discord → #web-briefs → Edit Channel → Integrations → Webhooks → New Webhook
2. Name it "CMP Web Intake", copy the webhook URL
3. In `index.html`, find the line: `const WEBHOOK = 'DISCORD_WEBHOOK_PLACEHOLDER';`
4. Replace the placeholder with your webhook URL
5. Push to GitHub

## Managing Projects

- Add a new project: click **+ Add Project** on the dashboard, fill the form, copy the JSON
- Drop the JSON in #web-briefs and tag @Jarvis — Jarvis adds it to `projects.json`
- Dashboard auto-updates on every load

## Files
- `index.html` — client-facing intake form
- `dashboard.html` — internal project tracker
- `projects.json` — project data (Jarvis updates this)
