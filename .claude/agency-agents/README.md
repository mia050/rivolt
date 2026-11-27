# AI agents for the Rivolt demo

Specialist agents that Claude Code uses when it works on this repository. They live in `.claude/agents/`.
Source: [The Agency](https://github.com/msitarzewski/agency-agents) by Mike Sitarzewski, MIT licence (copy in `LICENSE`).

## Updates
`.github/workflows/agency-agents-update.yml` refreshes every agent listed in `agents.txt` from The Agency every
Monday at 03:23 Lusaka time, and on demand (Actions → agency-agents-update → Run workflow). Its commits say
`[skip ci]`, so an update never starts a build or a deploy.

## Add or remove an agent
Add or delete its line in `agents.txt` (the path inside The Agency, e.g. `marketing/marketing-seo-specialist.md`),
then run the workflow by hand. To remove one for good, also delete its file from `.claude/agents/`.

## Installed (11)
| Agent | File | What it does |
|---|---|---|
| Frontend Developer | `engineering-frontend-developer.md` | Expert frontend developer specializing in modern web technologies, React/Vue/Angular frameworks, UI implementation, and performance optimiza… |
| Code Reviewer | `engineering-code-reviewer.md` | Expert code reviewer who provides constructive, actionable feedback focused on correctness, maintainability, security, and performance — not… |
| Minimal Change Engineer | `engineering-minimal-change-engineer.md` | Engineering specialist focused on minimum-viable diffs — fixes only what was asked, refuses scope creep, prefers three similar lines over a … |
| Internationalization Engineer | `engineering-i18n-engineer.md` | Expert i18n engineer for ICU MessageFormat, CLDR plural rules, RTL and bidirectional layouts, locale-aware date/number/currency formatting, … |
| UX Architect | `design-ux-architect.md` | Technical architecture and UX specialist who provides developers with solid foundations, CSS systems, and clear implementation guidance |
| UI Designer | `design-ui-designer.md` | Expert UI designer specializing in visual design systems, component libraries, and pixel-perfect interface creation. Creates beautiful, cons… |
| AI-Generated Code Security Auditor | `security-ai-generated-code-auditor.md` | Security reviewer for AI-generated and vibe-coded apps — hunts the hardcoded secrets, broken row-level security, and prompt-injection sinks … |
| Reality Checker | `testing-reality-checker.md` | Stops fantasy approvals, evidence-based certification - Default to "NEEDS WORK", requires overwhelming proof for production readiness |
| Evidence Collector | `testing-evidence-collector.md` | Screenshot-obsessed, fantasy-allergic QA specialist - Reports reproducible issues with evidence and marks untested scope honestly |
| Accessibility Auditor | `testing-accessibility-auditor.md` | Expert accessibility specialist who audits interfaces against WCAG standards, tests with assistive technologies, and ensures inclusive desig… |
| Sales Engineer | `sales-engineer.md` | Senior pre-sales engineer specializing in technical discovery, demo engineering, POC scoping, competitive battlecards, and bridging product … |
