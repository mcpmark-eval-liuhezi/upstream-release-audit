# Working Notes — Upstream Release Audit (Scratch)

> Scratch file for draft notes while the report is being written.
> **This file is deleted before the pull request is opened** — the PR must show only `upstream.md`.

## Audit target
- Upstream project: Next.js (`vercel/next.js`)
- Audited: live data pulled from the GitHub API at report time

## Data collected so far

### 1. Latest release (DRAFT)
- Tag: v16.4.2
- Published: 2026-10-15T20:44:37Z
- Release author: lukesandberg
- Target branch: canary
- Notes: changelog lists [lts-active] backports incl. turbo-tasks snapshot consistency fixes, Turbopack Pages Router dev module graph chaining backport, next-code-frame char boundary snapping, Turbopack GC dependency edge fixes, realpath error handling in module resolution, docs backports, lazy dynamic-import chunk-list collision fix.
- TODO: verify tag string verbatim in the report.

### 2. Discussions (DRAFT)
- Repository has Discussions enabled.
- 10 categories found (need to list verbatim): App Router, Feedback, Help, Ideas, Polls, RFC, Security, Show and tell, Triage, Turbopack Error Report.
- TODO: re-count and copy names exactly.

### 3. CI status (DRAFT)
- Workflow picked: `build-and-test` (`.github/workflows/build_and_test.yml`)
- Most recent run at time of check: run 134536 (id 39388224097) was still IN PROGRESS → fell back to most recent run with a conclusion: run 134534 (id 39385935954), branch `canary`, event push, title "Upgrade React from `99c106c4-20261014` to `ba39b32a-20261019` (#100403)".
- Conclusion: success
- Artifacts: 140 published; example: `turbo-run-summary-test-new-tests-deploy-2-5` (id 12249131668, ~183 KB), plus `test-playwright-snapshots-*` families.
- TODO: include one artifact download reference in the report.

## Open questions / follow-ups
- Confirm whether the report should link the temp artifact URL (expires quickly) — note the expiry.
- Confirm report file name: upstream.md (branch audit/report).
- Confirm PR title: "Add upstream release audit report".
- Review pass needed: teammate-style comment anchored to upstream.md, submitted as COMMENT (not approve / not request changes).

## Status
- [x] Live data gathered
- [ ] upstream.md written
- [ ] NOTES.md removed from branch
- [ ] PR opened
- [ ] Review comment submitted
- [ ] PR files re-checked
- [ ] Hand-off gist created
