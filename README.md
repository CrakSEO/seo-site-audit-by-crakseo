# SEO Site Audit: Technical SEO Checker & Page Speed by CrakSEO

SEO site audit and technical SEO checker: on-page SEO checks, page speed, Lighthouse and Core Web Vitals scores for up to 5 URLs per call.

Audit pages for technical SEO and on-page SEO problems. The SEO site audit runs on-page and technical SEO checks on up to 5 URLs per call, and runs Lighthouse for page speed and Core Web Vitals scores. Use it as an SEO checker before a launch, after a deploy, or to find why a page underperforms on Google, then re-run it to confirm your fixes.

| | |
| --- | --- |
| Endpoint | `https://crakseo.com/mcp/site-audit` |
| Transport | Streamable HTTP |
| Sign-in | OAuth (a CrakSEO account is created on first sign-in) |
| Price | Free to connect, and `get_api_credit_balance` is free. Data calls use prepaid API credits; each tool states its cost. Pricing: https://docs.crakseo.com/pricing/api-credits |
| Docs | https://docs.crakseo.com/mcp-servers/site-audit |

## Tools

| Tool | What it does | Price |
| --- | --- | --- |
| `run_seo_site_audit` | SEO site audit for pages | API credits |
| `get_page_speed_scores` | Lighthouse and Core Web Vitals | API credits |
| `get_api_credit_balance` | API credit balance | Free |

## Questions it answers

- How do I check a page for SEO issues?
- How do I compare technical SEO issues on up to five pages?
- How do I check page speed and Core Web Vitals?

## Install

Install from the Cursor Marketplace, or add the server to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "crakseo-site-audit": {
      "url": "https://crakseo.com/mcp/site-audit"
    }
  }
}
```

Other clients: https://docs.crakseo.com/mcp-servers/site-audit

## Privacy and support

- Privacy: https://crakseo.com/privacy
- Terms: https://crakseo.com/terms
- Support: support@crakseo.com

The files in this folder are MIT-licensed. That does not license the hosted CrakSEO service.
