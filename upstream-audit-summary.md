# Upstream watch — cli/cli
One-page summary of the quarterly upstream release &amp; security audit for the GitHub CLI project (repository cli/cli, organization cli).

## 1. Latest release
- **Tag:** v2.103.0
- **Release name:** GitHub CLI 2.103.0
- Target commitish: 7948e8056e45ac3c729b829e0eafe2d0797a95c6
- Headline changes: expiring, auto-refreshing OAuth tokens (preview) — `gh auth login --expiring`, `gh config set expiring_credentials enabled`; the `gh issue artifact` command stack (private preview) for managing issue artifacts.

## 2. Organization-level security advisory listing for org "cli"
- **Outcome:** access error — the call to `GET https://api.github.com/orgs/cli/security-advisories` returned **404 Not Found**. No advisory IDs or titles were returned. (An empty list or a refused call is a legitimate, recordable outcome for this lookup.)

## 3. CI artifacts — most recent completed run of the main CI workflow
- **Workflow:** "Unit and Integration Tests" (`.github/workflows/go.yml`) — the workflow that builds and tests on pushes to trunk.
- **Run:** #22990 (run id 39623013081), branch `trunk`, event `push`, conclusion `success`, head SHA 7948e8056e45ac3c729b829e0eafe2d0797a95c6, display title: "Merge pull request #14782 from cli/babakks/skill-gh-expiring-tokens".
- **Artifacts:** no artifacts — the run published nothing (`total_count: 0`), so there is no artifact download URL to record.

## Tracking
- Tracking repository: mcpmark-eval-liuhezi/upstream-release-audit (default branch: main)
- Tracking issue: #2 "Upstream release audit: cli/cli" — findings posted as a comment (first line: FINDINGS); closed as completed with the label `audit-done`.
- This summary is also published as a secret gist.
