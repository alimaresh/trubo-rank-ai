# One Page Scan

One Page Scan is a focused Trubo Rank AI diagnostic for reviewing one exact public URL. It helps website owners and developers understand whether a page is clear, accessible, structured, and ready for its intended job without running a whole-site audit.

Open the public tool page:

https://truborankai.com/one-page-scan

## How It Works

After signing in, add the exact public page URL and choose the page type that best describes it. Supported profiles include:

- Home pages
- Blog posts and articles
- Store home pages
- Product and collection pages
- Service and landing pages
- Intent and comparison pages
- Documentation and help pages
- About, entity, and local business pages

The selected type determines the evidence-based checks used for the report. If the visible page signals appear inconsistent with that choice, the report can warn about a possible mismatch without silently changing the selected rules.

## What The Report Includes

One Page Scan organizes the saved result into clear report tabs:

- **Overview:** page readiness, verified checks, issues, page-type fit, and the best next step.
- **Issues:** failed and warning checks with measured evidence, a recommended fix, and verification guidance.
- **Passed:** positively verified page signals worth preserving.
- **AI insights:** a separate lightweight clarity review that does not change Page Readiness.
- **Report details:** the scan scope, page type, report version, date, and evidence limitations.

Page Readiness is based on measured checks for the submitted URL. Optional AI observations remain separate and cannot change the score.

## Prompt Ready MCP

Each saved report provides a **Prompt Ready MCP** action in the report hero. It copies a structured coding-agent prompt containing:

- The exact target URL and declared page type
- The available Page Readiness result
- Failed and warning checks
- Bounded evidence from the report
- Recommended fixes and verification steps
- Verified checks that should be preserved
- Safety rules and report limitations

The prompt can be pasted directly into coding agents such as Codex, Claude Code, Cursor, Windsurf, or similar tools. Its inline JSON is MCP-ready, but it does not assume that the coding agent has access to a Trubo Rank AI account or MCP server.

## Privacy And Scope

- The scanner reads one public URL and does not sign in to the submitted website.
- Saved reports belong to the signed-in account.
- The report does not contain raw page HTML.
- It is a page-level snapshot, not a whole-site crawl.
- It does not prove indexing, rankings, traffic, conversions, crawler visits, or AI citations.
- AI-readable signals can support clarity and discoverability, but they do not guarantee search or answer-engine outcomes.

## Best For

- Developers improving a specific production page
- SaaS founders reviewing a homepage or landing page
- Stores checking products, collections, and storefront pages
- Writers reviewing an article before or after publication
- Agencies preparing evidence-backed implementation tasks
- Teams that want a safe coding-agent prompt instead of a generic SEO checklist

## Related Tools

- [AI Readiness Checker](ai-readiness-checker.md)
- [AI Discoverability Checker](ai-discoverability-checker.md)
- [AI Agent Prompts for SEO](ai-agent-prompts-for-seo.md)
- [AI-Ready Content Structure](ai-ready-content-structure.md)
- [GEO Checker](geo-checker.md)

## Scan One Public Page

Open One Page Scan:

https://truborankai.com/one-page-scan
