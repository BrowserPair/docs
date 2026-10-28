# BrowserPair documentation instructions

This repository publishes BrowserPair's public documentation at https://docs.browserpair.com/ through Mintlify. It does not contain the private application source.

## Product terminology

- BrowserPair connects AI agents to the user's existing Chrome profile.
- A browser device credential is separate from an external agent key.
- Managed tasks use a user-configured Agent Model; external MCP agents supply their own Agent Model.
- Decision Model selects bounded actions; BrowserPair executes them.
- Skills are workflow knowledge, never authorization.
- An uncertain effect must be verified before a retry.

## Authoring

Use concise English, active voice and second person. Use sentence case headings and real UI labels. Write MDX with valid frontmatter; navigation and branding live in docs.json.

Verify every API path, field, capability and UI route against current product behavior. Do not infer released features from plans or old project tasks. State limitations and avoid blanket privacy, security or automation guarantees.

## Publication boundaries

Keep secrets, device credentials, private dashboards, customer data and internal infrastructure details out of public files. Use obvious placeholders in examples. Public product documentation belongs here; internal operations belong in the private application repository.

Preserve published page URLs or add redirects. Check links and preview changed pages before merging. Changes to connected content on main may publish automatically through Mintlify.

## Related public resources

- Product hub: https://github.com/BrowserPair/browserpair
- Examples: https://github.com/BrowserPair/examples
- Skills: https://github.com/BrowserPair/skills
- Ecosystem guide: https://github.com/BrowserPair/awesome-browser-agents
