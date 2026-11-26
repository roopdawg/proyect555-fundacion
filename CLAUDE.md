# CLAUDE.md

## GitHub, not machine (NON-NEGOTIABLE)
- This project lives on GitHub. GitHub is the source of truth, never whichever computer a session runs on (iMac, MacBook Air, cloud, phone-driven).
- Never rely on local-only state: files, branches, or commits that exist only on one machine are invisible to other machines, cloud sessions, and collaborators.
- Read the remote (`origin/<branch>`), not a possibly stale local checkout, before describing what exists.
- When work exists only locally (unpushed commits, untracked files), flag it in one line and offer to push. Pushing still needs Roopa's go-ahead.
- Never write instructions that only work on one machine (local paths, localhost links) as if they apply everywhere.
