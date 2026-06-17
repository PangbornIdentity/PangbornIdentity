# Richard Pangborn

Software Development Manager at [Method:CRM](https://www.method.me) in Toronto, leading CRM and runtime product engineering teams on the leading CRM platform for QuickBooks.

I care about scaling team performance and engineering process, and about getting AI into the dev loop without watering down what makes engineers good at their jobs. Most of my work lives in private repos; the public projects here are how I stay hands-on and judge the tools my teams ship with from real code, not demos.

## Currently shipping

🚀 [TaskPilot](https://github.com/PangbornIdentity/TaskPilot): a task manager with a native MCP server, a REST API for LLM clients, and an htmx-rendered UI. Live at [taskpilot.azurewebsites.net](https://taskpilot.azurewebsites.net).

.NET 10 / ASP.NET Core Razor Pages, EF Core, Azure SQL, HMAC-SHA256 API-key auth, audit logging, and 250+ tests (unit, integration, and a Playwright E2E suite). Built solo, alongside Claude Code and Codex, to find out what shipping a real MCP server and an AI-friendly app actually feels like past the demo stage.

## What I spend my time on

Most of it is private, but the themes are:

- **Instrumenting delivery, not just reporting on it.** Tooling that makes cycle time, SLA misses, and review/QA flow visible to the teams doing the work — with light gamification designed so the winning move is improving outcomes, not gaming the number.
- **Raising the floor for every team.** Deployment-observability standards so every service reports what's running where, AI-assisted review in the pipeline, cleaner code-ownership and review routing, and a docs uplift across the platform. Work that improves every repo at once instead of one feature.
- **Making quality repeatable.** Requirements-as-data with automated accessibility gating, so verifiable, accessible UI is the default path rather than a heroic effort.

## How I think about the work

- Teams learn from *patterns* across hundreds of bugs and incidents, not one at a time: regression tracking, bug archaeology, and retros that drive structural change instead of action-item theater.
- AI belongs in review, triage, and grooming, as long as you stay clear-eyed about where it helps and where it quietly doesn't.
- Server-rendered web apps still hold up in 2026. htmx and friends quietly make it possible to skip the SPA tax and ship faster.
