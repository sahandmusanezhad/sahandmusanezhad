---
name: finish-with-pr
description: Use at the end of every task in this repository, and whenever the owner says «PR بزن و مرجش کن» (open a PR and merge it). Lands the work as a pull request into main and merges it, so each change counts as a merged pull request on the owner's profile.
---

# Finish with a merged pull request

1. Commit the work on a branch other than `main`; `git status` must be clean.
2. `git fetch origin main` and bring the branch up to date with `origin/main`.
3. Push the branch: `git push -u origin <branch>`.
4. Open a pull request into `main`. Title: the change in one line. Body: what
   changed, why, and how it was checked.
5. Wait for the pull request's checks, if it has any. Never merge a red one.
6. Merge with a **merge commit** — not squash, not rebase.
7. Pushes to `main` run *Profile assets*; confirm that run succeeded.
8. Tell the owner, in Persian, the pull request's link and that it is merged.
