## Austin Hall

Senior IT Systems Administrator in San Diego. I spend most of my time on
identity infrastructure. Okta, endpoint management, and the automation
around them.

Lately I've been working through what it takes to point AI tooling at real
identity infrastructure without handing it more access than it needs.

### Projects

**[svc-okta-log-triage](https://github.com/austinhalldev/svc-okta-log-triage)**

Pulls Okta System Log events, filters out the noise, pseudonymizes
identities, and sends what's left to an LLM for classification. The
governance question there was what data may cross a boundary.

**[svc-okta-identity-mcp](https://github.com/austinhalldev/svc-okta-identity-mcp)**

An MCP server that exposes read-only Okta identity lookups to an AI client.
A per tool field allowlist controls exactly what reaches the model. The
governance question there was what an agent is permitted to do.

Both repos have a `docs/decisions.md` journal with the decisions I made,
what I turned down, and what I got wrong. That's the part I'd read first.

Reachable at austin@austinhall.dev.
