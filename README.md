# Lawrence Plugins — Security & Platform Guardrails

A marketplace of **free forever** Cursor plugins that catch the boring, expensive mistakes before they merge: env drift, missing auth, CORS footguns, API contract breaks, secret leaks, and more.

Each plugin ships with a unique logo (`assets/logo.svg`), clear README, and MIT license. No paywall in the plugins.

## Install

1. Open **Cursor → Marketplace**
2. Browse this marketplace or search for a plugin name (e.g. EnvDrift, ApiDiffGate, Missing Auth Ban)
3. Install and enable

Or clone this repo and load a plugin folder locally.

## Free forever

Every plugin in this repo stays **free forever** inside Cursor.

## Pro

Want hard CI gates, SARIF, and team workflows? That’s Pro — outside Cursor:

→ https://plugins.lawrence.dev/pro

## Plugins

100 plugins. Highlights:

- `apidiffgate` — **ApiDiffGate**: OpenAPI/Swagger contract diff gate for PRs. Stop breaking API changes from shipping to pro…
- `adminrouteban` — **Admin Route Ban**: Fail CI when /admin routes lack requireAdmin / isAdmin / role checks.
- `envdrift` — **EnvDrift**: Env drift + secrets auditor. Catch missing/unexpected env keys and high-confidence leaked …
- `errorbudget` — **ErrorBudget**: Error-rate / error-budget brief for a time window from CSV/JSON metrics.
- `gitsecrethistoryban` — **Git Secret History Ban**: Fail CI when secrets appear in working-tree files.
- `hardcodedapikeyban` — **Hardcoded API Key Ban**: Fail CI on hardcoded API keys in string literals (sk_, AKIA, ghp_, xoxb_, JWT).
- `incidentbrief` — **IncidentBrief**: Noisy logs → spike detection, error shapes, owner handoff brief.
- `missingauthban` — **Missing Auth Ban**: Fail CI when sensitive Express/Next/Fastify/Hono routes lack auth.
- `prismaguard` — **PrismaGuard**: Lint Prisma schema & migrations for destructive DROP/delete risks — before they ship.
- `rotatewatch` — **RotateWatch**: Secret age / rotation reminder from a vault-export CSV or a `.env` mtime inventory.
- `sbomdiff` — **SbomDiff**: Compare two CycloneDX or SPDX JSON SBOMs. See added, removed, and upgraded packages. Paste…
- `sqlmigrationguard` — **SqlMigrationGuard**: Review SQL migrations for destructive ops, lock hazards, and unsafe ordering — before they…
- `terraformstatesecretsban` — **Terraform State Secrets Ban**: Fail CI when Terraform risks secret leakage in state.
- `ansiblevaultmissban` — **Ansible Vault Miss Ban**: Fail CI when Ansible secrets aren't vaulted.
- `blametrail` — **BlameTrail**: Git archaeology brief — who touched a path, churn, hot files.

Full list: `.cursor-plugin/marketplace.json` (100 entries).

## License

MIT
