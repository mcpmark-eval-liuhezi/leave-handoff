# HANDOFF — GitHub work before leave

Prepared 2026-10-25 for the teammate covering GitHub work during leave. Everything below was pulled live from the GitHub API on that date.

## Profile

Who owns this account:

- **Login:** `HeziLiu`
- **Display name:** Hezi Liu
- **Bio (verbatim, exactly as it stands on the profile right now):** "treat me like a tree"

Profile: https://github.com/HeziLiu — also on the profile: company BUPT/GZU, location Beijing/Guiyang, 4 public repos, 5 followers, 5 following. The bio above is quoted word for word from the live profile lookup.

## Notifications

**This section could not be populated — the notifications API is not accessible with the current access token.** Both attempts to list the account's notifications (default filter and read-included filter) failed with the same error:

```
403 Resource not accessible by personal access token
```

The token lacks the scope needed to read the notifications inbox, so the inbox contents are **unknown — not confirmed empty**. The first thing the covering teammate should do is open https://github.com/notifications while signed in as the account owner and sweep it manually. Nothing else in this handoff was sourced from the notifications API, so no other section is affected by this gap.

## Open pull requests

**Scope.** A search for open pull requests authored by @HeziLiu anywhere on GitHub returns roughly **1,276 open pull requests** (the count moved from 1,275 to 1,276 *during* this sweep — the org is actively receiving new PRs). Every open PR found lives in the shared org `mcpmark-eval-liuhezi`; **no open PRs were found under the personal account or in any other organization.** All PRs updated since 2026-10-24 — the active work — are enumerated individually below, newest activity first. The remainder are older, dormant demo/drill PRs in the same shared org (created before 2026-10-24 and untouched since). To reproduce the complete list at any time, run the search: `is:pr is:open author:HeziLiu`.

**State.** All listed PRs are **open** (none merged); three are still **drafts** and are marked as such. 

**Reviews / checks / artifacts — how this was determined.** Per-PR review and check status was pulled individually for the active PRs. Every PR status check returned **zero pending check runs** — no CI is waiting anywhere. The only reviews found are self-authored `COMMENTED` reviews by the account owner (none are approvals, none are blocking). One PR — `log4shell-audit-4#6` — has an **unsubmitted (pending) review** sitting on it. Downloadable workflow artifacts exist for exactly two of the open PRs' repositories:

| Repository | PR | Downloadable artifact |
|---|---|---|
| `github-presence-audit-2` | #1 | **`audit-report`** (2,329 bytes; from the PR-triggered run 40181354595) |
| `release-readiness-audit-3` | #3 | **`audit-evidence`** (299 bytes; from the repo's workflow run 40185449607 on `main`) |

Other CI runs referenced by open PRs (release-readiness-drill-9 run 40185790560, flaky-rerun-demo run 40176593110, audit-hub run 40199408897) were checked and produced **no downloadable artifacts**.

### The active open pull requests

| Repository | PR | Title | State |
|---|---|---|---|
| audit-hub | #5 | Add CI usage notes | Open |
| winter-line-audit | #1 | Winter line store sync audit | Open |
| team-onboarding-playbook | #3 | Refresh onboarding docs: first week, rituals, and tooling | Open |
| llm-reading-digest | #1 | Add cycle 1 reading digest | Open |
| base-image-refresh | #1 | Training stack refresh — Debian cadence and upstream PR load | Open |
| journal-club-fall-2026 | #1 | Add verified journal club shortlist | Open |
| oncall-runbook | #10 | Add rollback procedure guide | Open |
| launchpad-ops | #5 | Add contributing guide | Open |
| mega-cap-tech-brief | #1 | Add SUMMARY.md for quarterly mega-cap tech committee brief (AAPL, MSFT, NVDA, AMZN) | Open |
| hezi-review-workflow-smoke-test | #1 | Add smoke-test note for review-workflow demo | Open |
| review-walkthrough-sandbox | #2 | Add demo review checklist for walkthrough | Open |
| release-readiness-drill | #46 | Audit drill: release readiness checklist | Open |
| security-audit-2026 | #13 | Add SECURITY_AUDIT.md: 2026 account security audit | Open |
| ci-rehearsal-lab-3 | #2 | Drill: trigger CI from a pull request | Open |
| github-presence-audit-3 | #1 | Add GitHub presence audit report | Open |
| onboarding-sandbox | #2 | Onboarding docs refresh and legacy cleanup | Open |
| backoff-cookbook | #2 | Add Python examples appendix | Open |
| agent-ops-demo | #4 | Add the deployment hardening checklist doc | Open |
| release-notes-demo-x9k4 | #1 | Add changelog for v1.0.1 | Open |
| release-readiness-drill-9 | #1 | Release readiness review: axios | Open |
| release-checklist-pilot | #4 | Add release checklist v2 | Open |
| log4shell-audit-4 | #6 | Add SECURITY-NOTES.md — Log4Shell research facts for quarterly briefing | Open |
| release-readiness-audit-3 | #3 | Add release readiness note | Open |
| ownership-snapshots | #1 | Add institutional holders snapshot for AAPL, MSFT, NVDA | Open |
| sec-audit-2026 | #4 | docs: lodash security advisory audit | Open |
| genai-observability-audit | #1 | Add Weave audit summary | Open |
| art-onchain-digest | #1 | Draft: Value Across Centuries | Open |
| home-ops-tracker | #5 | Add maintenance checklist | Open |
| github-presence-audit-2 | #1 | Add GitHub presence audit report | Open |
| lazy-brunch-cookalong | #1 | Saturday brunch cook-along | Open |
| local-first-reading-list | #1 | Add initial local-first reading list | Open |
| review-rehearsal | #6 | Review workflow rehearsal | **Draft** |
| sqli-brownbag-demo | #1 | Add vulnerable login demo | Open |
| dep-triage-drill | #2 | Bump lodash to 4.17.21 | Open |
| flaky-rerun-demo | #1 | Flaky workflow: capture rerun evidence | Open |
| mcp-tech-brief | #1 | MCP tech brief draft v0 for fact-check | Open |
| pr-hygiene-demo | #1 | Hygiene walkthrough: README touch-up (verified) | **Draft** |
| release-notes-drill | #1 | Sprint 42 release notes draft | Open |
| release-checklist-demo-3 | #1 | Add release checklist page | Open |
| platform-fire-drill | #1 | Add CI fire-drill workflow | Open |
| release-flow-demo | #4 | Add demo checklist | Open |
| tree-notes | #6 | Add contributing guide | Open |
| e2e-pipeline-check | #1 | Update runbook with audit notes | Open |
| ci-logbook-demo | #1 | Brighten the greeting message | Open |
| shanghai-trip-brief | #2 | Add Shanghai offsite trip briefing (outbound G9, return G32) | Open |
| repo-hygiene-drill | #2 | Docs: add SUPPORT.md | **Draft** |
| maintenance-backlog | #9 | Add repository audit notes | Open |
| mcp-onboarding-brief | #1 | Add onboarding brief for github-mcp-server | Open |
| bert-lineage-brief | #1 | Add BERT lineage brief (REPORT.md) | Open |
| model-platform-briefings | #1 | Add weekly platform briefing | Open |
| handover-prep-3 | #1 | Add handover notes for the October release | Open |
| q3-reliability-review-2026 | #5 | Add Q3 review agenda | Open |
| github-workshop-demo | #1 | Add contributor FAQ from GitHub Discussions research | Open |
| ci-rerun-drill-3 | #1 | Drill: flaky CI retry rehearsal | Open |
| example-domain-snapshot | #1 | Add example.com snapshot | Open |
| mcp-onboarding | #4 | Add MCP onboarding briefing (docs/mcp-onboarding.md) | Open |
| rag-reading-list | #2 | Weekly literature scan: six recent arXiv preprints on retrieval-augmented generation | Open |
| lijiang-train-research | #1 | Beijing → Lijiang train research: recommended itinerary (G979 + C446 out, C396 + D940 back) | Open |
| friday-nostalgia | #1 | Friday Nostalgia: Never Gonna Give You Up (1987) | Open |
| advisory-brief-2026-10 | #1 | Dependency advisory brief | Open |
| review-workshop-demo | #1 | Add greeting module | Open |
| workflow-dryrun | #4 | Add onboarding dry-run notes file | Open |

All of the above are in the `mcpmark-eval-liuhezi` organization. The remaining ~1,2xx open PRs from the same author are older, dormant entries in that same org; see the scope note above for how to list them.

### Flags for the cover

- **mega-cap-tech-brief #1** — the PR asks for review comments **before the committee meeting on Monday morning**. Most time-sensitive item on the list.
- **log4shell-audit-4 #6** — has a pending, unsubmitted review sitting on it (started by the account owner). Decide whether to submit or discard it.
- **sqli-brownbag-demo #1** — contains *intentionally* vulnerable code (SQL injection, hardcoded DB password) for a security brownbag. **Do not merge or deploy.**
- **dep-triage-drill #2** — lodash security bump, described as safe to merge once a human review passes.
- **shanghai-trip-brief #2** and **lijiang-train-research #1** — travel logistics with a departure window starting Friday 2026-10-30; both await confirmation/review before anything is booked.
- **oncall-runbook #10** — rollback guide for the quarterly on-call prep ahead of the new rotation.
- The notifications inbox could not be read programmatically (see the Notifications section) — sweep it manually first.
