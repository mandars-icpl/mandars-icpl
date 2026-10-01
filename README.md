# Mandar Sanghavi

Security platform engineer at [Infopercept](https://github.com/Infopercept), Ahmedabad. Work on Invinsense — XDR/SIEM/IAM.

> "Don't explain your philosophy. Embody it."
> — Epictetus

Most of what I build is backend and systems infra: Go services behind Cloudflare Workers/D1/Queues, identity and four-eyes approval systems, security telemetry pipelines. It lives in private company repos, so public contribution graphs undercount the work — this page leans on side-projects instead.

Primary stack: Go, C#/.NET, TypeScript (Next.js/React), Rust, Python, PostgreSQL.

## Identity & access

Deep, hands-on work across the identity stack of a multi-tenant security platform:

- **SCIM 2.0 provisioning** — built the multi-tenant middleware translating identity operations between enterprise IdPs (Keycloak, Google Workspace, Microsoft Entra ID) and downstream apps; primary contributor to its core API, provisioning engine, and connector set
- **OIDC identity federation** — IDP-agnostic broker acting as both OIDC client (upstream IdPs) and OIDC provider (downstream SPs), with backchannel logout and OCSF-compliant audit logging
- **Multi-tenant architecture** — authored the platform-wide tenant-isolation standard: PostgreSQL schema-based isolation, tenant resolution/routing, DB access conventions
- **Tenant-aware frontends** — per-tenant OIDC sign-in, tenant provisioning and routing in Next.js/React admin and launcher consoles
- **Security tool integrations** — connectors tying the identity/case-management layer into SIEM, EDR, and vulnerability-management tooling (Wazuh, OpenSearch, Keycloak, SOAR workflows)

Also the primary contributor to the platform's Go-based security data layer: storage, background workers, and vendor connectors (EDR/threat-intel feeds) behind its tenant-scoped query API.

## Public work

| Project | What it is |
|---|---|
| [krabs-trace-windows-poc](https://github.com/mandars-icpl/krabs-trace-windows-poc) | Windows ETW event tracing PoC, C# |
| [opensearch-dotnet-integration](https://github.com/mandars-icpl/opensearch-dotnet-integration) | OpenSearch + .NET integration samples |
| [serilog-tracing-examples](https://github.com/mandars-icpl/serilog-tracing-examples) | Structured logging/tracing setups with Serilog |
| [vault-example](https://github.com/mandars-icpl/vault-example) | Secrets management with HashiCorp Vault |
| [Gitlab-Manager](https://github.com/mandars-icpl/Gitlab-Manager) | Tooling around the GitLab API |
| [rust-by-examples](https://github.com/mandars-icpl/rust-by-examples) / [rust-learn](https://github.com/mandars-icpl/rust-learn) | Rust fundamentals and patterns |

Also read, not written: forks of [Wazuh](https://github.com/mandars-icpl/wazuh), [sealed-secrets](https://github.com/mandars-icpl/sealed-secrets), [uWebSockets](https://github.com/mandars-icpl/uWebSockets), [PerfView](https://github.com/mandars-icpl/perfview), [SilkETW](https://github.com/mandars-icpl/SilkETW) — kept around to study.

<img height="160" src="https://github-readme-stats.vercel.app/api?username=mandars-icpl&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />

[GitHub](https://github.com/mandars-icpl)
