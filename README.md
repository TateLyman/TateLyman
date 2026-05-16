# Tate Lyman

I build practical developer tools and small launch systems: release checks, MCP servers, browser utilities, security-focused reviews, and fast public-facing sites.

- **Tate Programs:** [tateprograms.com](https://tateprograms.com)
- **Contact:** [hello@tateprograms.com](mailto:hello@tateprograms.com)
- **X:** [@tateprograms](https://x.com/tateprograms)

## Current Focus

- MCP server packaging, registry metadata, npm releases, Glama readiness, and directory submissions.
- Public MCP registry research and launch-readiness signals.
- Agent commerce, x402/MPP/Pay.sh launch controls, spend caps, receipts, payment metadata filtering, and no-payment public-surface checks.
- AgentCore-style payment session policies, approval gates, payee allowlists, and audit trails.
- Agent security, prompt-injection drills, policy checks, audit evidence, and human-review launch gates.
- Release-readiness tooling for JavaScript and TypeScript projects.
- Fixed-scope launch cleanup for builders who need a repo, package, or site tightened quickly.
- Security-minded review work where the output is concrete: findings, patches, repro steps, and follow-up notes.

## Public Work

| Project | What it is | Links |
| --- | --- | --- |
| Shipcheck CLI | Release-readiness scanner for JavaScript and TypeScript repos. Checks scripts, docs, lockfiles, CI signals, TypeScript config, dependency hygiene, and risky release paths. | [GitHub](https://github.com/TateLyman/shipcheck-cli) / [npm](https://www.npmjs.com/package/shipcheck-cli) |
| Shipcheck MCP | Local MCP server for authorized repo scans through Shipcheck. Published on npm with registry metadata and public directory proof. | [GitHub](https://github.com/TateLyman/shipcheck-mcp) / [npm](https://www.npmjs.com/package/shipcheck-mcp) / [Glama](https://glama.ai/mcp/servers/TateLyman/shipcheck-mcp) |
| Tate Programs | Terminal-style services site for fixed-scope website, automation, launch review, and MCP directory work. | [Site](https://tateprograms.com) / [Case files](https://tateprograms.com/case-studies.html) |
| Agent Security Drill Kit | Browser-only readiness checker for prompt injection, exfiltration, tool boundaries, policy actions, audit trails, rate limits, safe demos, and human review gates. | [GitHub](https://github.com/TateLyman/agent-security-drill-kit) / [Tool](https://tateprograms.com/agent-security-drill.html) |
| Agent Commerce Gate | Browser-only readiness checker for x402, Pay.sh, API-payment, and payment-agent prototypes: quoted prices, enforceable caps, receipts, provider validation, and metadata filtering. | [Gate](https://tateprograms.com/agent-commerce-gate.html) / [Sample report](https://tateprograms.com/agent-commerce-sample-report.html) |
| x402 Surface Check | Browser checker and npm CLI for x402 manifests, `endpoints[]` docs, OpenAPI specs, direct paid endpoints, MPP headers, and no-payment 402 challenges. | [GitHub](https://github.com/TateLyman/x402-surface-check) / [npm](https://www.npmjs.com/package/x402-surface-check) / [Tool](https://tateprograms.com/x402-surface-check.html) |
| x402 Surface Check Action | GitHub Marketplace Action for CI payment-surface checks before x402, MPP, Pay.sh, and payment-agent launches ship. | [Marketplace](https://github.com/marketplace/actions/x402-surface-check) / [GitHub](https://github.com/TateLyman/x402-surface-check-action) / [Launch review](https://tateprograms.com/agent-payment-launch-review.html) |
| x402 Attack Map 2026 | Field note mapping current x402/MPP attack classes to practical controls: finality, facilitator binding, replay protection, cache hygiene, metadata boundaries, and discovery steering. | [Field note](https://tateprograms.com/x402-attack-map-2026.html) |
| Pay.sh Catalog Pulse | Live catalog snapshot for agent-paid API provider counts, pricing surfaces, free-tier coverage, and launch-control review priorities. | [Pulse](https://tateprograms.com/pay-sh-catalog-pulse.html) / [JSON](https://tateprograms.com/pay-sh-catalog-pulse.json) |
| x402 Metadata Filter | Browser-only filter for x402/Pay.sh payment metadata: prompts, user identifiers, resource URLs, query tokens, wallet context, and secret-like receipt fields. | [Tool](https://tateprograms.com/x402-metadata-filter.html) |
| AgentCore Payment Policy | Browser-only policy builder for AgentCore Payments, x402, MPP, and Pay.sh demos: session caps, per-call limits, payee allowlists, approval rules, receipts, replay protection, and audit evidence. | [Tool](https://tateprograms.com/agentcore-payment-policy.html) |
| MCP Registry Pulse | Aggregate snapshot of MCP Registry launch-readiness signals across metadata, package paths, README proof, safety notes, and smoke-test language. | [Pulse](https://tateprograms.com/mcp-registry-pulse.html) |
| MCP Directory Launch Checklist | Public checklist for preparing MCP servers for npm, `server.json`, install docs, tool behavior notes, registry proof, Glama, PulseMCP, and curated directory PRs. | [Checklist](https://tateprograms.com/mcp-directory-checklist.html) |
| LaunchQuest | Torque incentive demo with custom event tracking, launch documentation, and public demo trail. | [GitHub](https://github.com/TateLyman/launchquest-torque) |

## Current Proof Trail

- Agent Trust Bench: builder confirmed eight clean-check items matched the live deployment after repeated no-payment review loops. [Builder confirmation](https://github.com/solana-foundation/pay-skills/pull/23#issuecomment-4467453947)
- paysh-send: private-transfer x402 pass isolated browser preflight, no-store, resource-binding, and smallest-units docs gaps without sending payment headers or touching funds. [Surface note](https://github.com/solana-foundation/pay-skills/pull/20#issuecomment-4467457050)
- Boundary Guard: follow-up verification cleared resource binding, sidecar scope, and health-probe boundary notes on a live x402 scanner. [Fix verification](https://github.com/solana-foundation/pay-skills/pull/52#issuecomment-4464739109)
- x402watch: provider added browser-readable CORS directly on 402 responses after review isolated the actual challenge path. [Fix note](https://github.com/solana-foundation/pay-skills/pull/36#issuecomment-4467183605)

## Services

I take small, well-scoped implementation work where the finish line is clear.

- MCP directory launch pass: package metadata, `server.json`, README install path, Glama readiness, and directory submission notes.
- Agent security launch review: prompt-injection drills, policy rules, tool boundaries, audit trails, rate limits, and human-review gates.
- Agent commerce readiness review: x402/Pay.sh/AgentCore spend caps, quoted-price previews, session policies, receipts, retry/refund paths, provider validation, and PII-safe payment metadata.
- x402 public-surface pass: no-payment manifest/challenge review, resource canonicalization, browser path checks, and private patch order.
- Agent payment launch review: private x402/MPP/Pay.sh/AgentCore review with no-payment endpoint probes, spend-map notes, cache policy checks, CORS/payment-header checks, and patch sequencing.
- Launch risk pass: quick technical review before a repo, package, or web app gets promoted.
- Fix sprint: production blocker repair, broken deploys, broken forms, auth flow issues, payment path checks, or release cleanup.
- Website repair: mobile layout, contact path, page speed basics, metadata, links, and obvious conversion blockers.

Start here: [tateprograms.com](https://tateprograms.com)

## Stack

TypeScript, Node.js, Python, React, Next.js, Vite, GitHub Actions, npm publishing, MCP, Solana, HTML/CSS, browser automation, security review, and launch operations.

## Support

If a public tool saves time:

**SOL:** `NaTTUfDDQ8U1RBqb9q5rz6vJ22cWrrT5UAsXuxnb2Wr`
