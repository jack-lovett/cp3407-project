# 5) Version Control

## Goals (rubric-aligned)
We use GitHub to make our work **traceable** and **reviewable**:
- **Traceability:** user story → issue → branch → PR → merge → deployed demo
- **Safety:** `main` stays deployable (GitHub Pages output)
- **Evidence for marking:** PRs, issue links, and discussion show our process

## Branching policy (lightweight)
### Default branch
- `main` is the **only long-lived branch**.
- `main` should always be in a **deployable** state.

### Feature branches (one story / one PR)
- Create a branch **when work starts**, not upfront.
- Prefer **one user story / one issue / one PR**.
- Naming:
  - `feature/us-07-track-order-status`
  - `docs/us-01-user-stories-cleanup` (docs-only change)
  - `chore/tooling-setup` (repo/tooling maintenance)

### Small changes (avoid PR fatigue)
We still use PRs, but keep them fast:
- Small docs fixes: PR is fine, but can be **self-reviewed + merged immediately**.
- If a change is truly trivial (typo only), it may be batched with the next related PR.

## Pull request (PR) policy
### When a PR is required
- Any change affecting the deployed site (`/docs`) or source code must go through a PR.

### PR checklist (minimum)
- Title format: `US-07: Track order status` (or `Docs: …` / `Chore: …`)
- Link the issue (e.g. "Closes #123")
- Link the user story file (e.g. `user_stories/user_story_07_track_order_status.md`)
- Screenshots for UI changes (where relevant)

### Merge strategy
- Prefer **Squash merge** into `main` to keep history readable.
- Delete branches after merge.

## Issue policy
- Use GitHub Issues as the unit of work for the iteration boards.
- Each implemented user story should have a corresponding issue.

## Examples / evidence
- Example PR (project hygiene): PR #4 merged `project-setup` into `main` and cleaned up the branch.
- Ongoing evidence: links to PRs and issues will be added to iteration pages and requirements pages.
