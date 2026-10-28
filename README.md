# BrowserPair documentation

Official documentation for [BrowserPair](https://browserpair.com/), the browser access layer that connects AI agents to your existing Chrome profile with scoped permissions, approvals, durable tasks and outcome verification.

**Read the published guides at [docs.browserpair.com](https://docs.browserpair.com/).**

## Find a guide

- [Quickstart](https://docs.browserpair.com/quickstart): pair Chrome and run your first bounded task.
- [Connect an AI app](https://docs.browserpair.com/connect-ai-app) and [ChatGPT](https://docs.browserpair.com/chatgpt).
- [Remote MCP](https://docs.browserpair.com/remote-mcp) and [REST API](https://docs.browserpair.com/rest-api).
- [Permissions](https://docs.browserpair.com/permissions), [sensitive access](https://docs.browserpair.com/sensitive-access) and [task semantics](https://docs.browserpair.com/task-semantics).
- [Managed tasks](https://docs.browserpair.com/managed-tasks), [Agent Model + Decision Model](https://docs.browserpair.com/agent-decision-model) and [Skills](https://docs.browserpair.com/skills-guide).

## Public resources

[Product and community hub](https://github.com/BrowserPair/browserpair) · [Examples](https://github.com/BrowserPair/examples) · [Skills](https://github.com/BrowserPair/skills) · [Browser-agent resources](https://github.com/BrowserPair/awesome-browser-agents)

This repository contains public documentation, not the private BrowserPair application source. Mintlify builds and hosts the documentation; the product described here is BrowserPair.

## Edit and preview

Pages are MDX files with frontmatter. Navigation and branding live in docs.json. Keep existing page URLs stable; add redirects when moving a published page.

Install the official [Mintlify CLI](https://www.npmjs.com/package/mint), then run `mint dev` from this directory. Use `mint broken-links` to check internal links. Follow the current [Mintlify documentation](https://www.mintlify.com/docs) for CLI requirements.

Before submitting a change, verify product behavior against the current app or authoritative API reference. Never add invented endpoints, unsupported integrations, credentials or private operational details.

## Publishing

The canonical source repository is [BrowserPair/docs](https://github.com/BrowserPair/docs), on the `main` branch.

The published site is connected to this repository's main branch through Mintlify. Review changes before merging because updates to connected content may publish automatically. The canonical documentation domain is https://docs.browserpair.com/.

## Help

[Support](https://browserpair.com/support) · [Security](https://browserpair.com/security) · [Privacy](https://browserpair.com/privacy) · [Service status](https://status.browserpair.com/)

For a documentation correction, open a pull request. Keep tokens, cookies, personal data and unredacted logs out of public reports.
