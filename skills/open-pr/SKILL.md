---
description: Open a pull request for the current branch.
---

# Open PR

- Follow Conventional Commits for the PR title (`type(scope): subject`).
- Keep the wording terse: short, direct sentences, no filler words, drop unnecessary subjects where the meaning stays clear.
- Prefer bullet points in the PR body. Bullets may be grouped into sections; use `###` for section headers.
- Do not include a "Test plan" section.
- Avoid em-dashes (—) in the title and body. Use a comma, colon, parentheses, or a separate sentence instead.
- Base branch is `main`.
- If the current branch is `main`, create a new branch first (Conventional Commits style name, e.g. `feat/short-description`), move any commits ahead of `origin/main` onto it, and reset local `main` to `origin/main`. Then push the branch and open the PR.
