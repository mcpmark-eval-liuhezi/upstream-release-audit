# Upstream Release Audit — Next.js (vercel/next.js)

Report #1 in our upstream dependency audit. All findings below are from live GitHub data at the time this report was compiled.

## 1. Latest Release

- **Tag (verbatim): `v16.4.2`**
- **Publish date: 2026-10-15T20:44:37Z** (UTC)
- Release name: v16.4.2 (matches the tag)
- Author: lukesandberg
- Target branch: `canary`
- Not a draft, not a prerelease
- Release notes highlight: backports to the active LTS line, including turbo-tasks snapshot consistency fixes, a Turbopack Pages Router dev module graph chaining backport, `next-code-frame` visible-window char boundary snapping, Turbopack GC dependency-edge repairs, realpath-error tolerance during module resolution, Turbopack lazy dynamic-import chunk-list collision fix, and documentation backports.
- Release URL: https://github.com/vercel/next.js/releases/tag/v16.4.2

## 2. Discussions Area

**Yes — Discussions are enabled on `vercel/next.js`.**

The repository has **10 discussion categories**, named:

1. App Router
2. Feedback
3. Help
4. Ideas
5. Polls
6. RFC
7. Security
8. Show and tell
9. Triage
10. Turbopack Error Report

## 3. CI Status

Build workflow examined: **`build-and-test`** (`.github/workflows/build_and_test.yml`)

Most recent run with a conclusion at time of writing:

- **Run:** run number 134534 (ID 39385935954)
- **Conclusion: `success`**
- Branch: `canary` (push event)
- Display title: "Upgrade React from `99c106c4-20261014` to `ba39b32a-20261019` (#100403)"
- Head SHA: `404d55e1c056b47c136eb920509a24aae4c64c35`
- Run URL: https://github.com/vercel/next.js/actions/runs/39385935954

**Artifacts:** Yes — this run published **140 downloadable artifacts** (e.g., `turbo-run-summary-test-new-tests-deploy-2-5`, and the `test-playwright-snapshots-*` family).

Example artifact download reference:

- Name: `turbo-run-summary-test-new-tests-deploy-2-5`
- Artifact ID: 12249131668 (~183 KB)
- Archive download URL: https://api.github.com/repos/vercel/next.js/actions/artifacts/12249131668/zip

> Note: the artifact download link returned by the API is a short-lived, signed URL that expires quickly; the stable reference above is the artifact's archive download endpoint.

## Summary

| Item | Finding |
| --- | --- |
| Latest release tag | `v16.4.2` |
| Publish date | 2026-10-15T20:44:37Z |
| Discussions enabled | Yes — 10 categories (App Router, Feedback, Help, Ideas, Polls, RFC, Security, Show and tell, Triage, Turbopack Error Report) |
| CI (`build-and-test`) | Most recent run succeeded (`success`) |
| Artifacts published | Yes — 140, e.g. `turbo-run-summary-test-new-tests-deploy-2-5` |

*Prepared as the first report in the upstream release audit.*
