## Standards

- Follow current Apple requirements and Xcode best practices for iMessage sticker packs and asset catalogs.

## Branches, Commits, and Pull Requests

- Use plain lowercase kebab-case for branch names. Keep names descriptive and do not include issue numbers, prefixes, or namespaces such as `feature/`, `fix/`, usernames, or agent names.
- Before every commit or amend, show the exact current diff and validation, then get explicit approval. Branch or pull-request requests are not commit approval; later changes require fresh approval.
- Never amend, rebase, squash, reset, rewrite history, or force-push without explicit approval for that exact operation.
- Write commit messages entirely lowercase. Use the imperative mood for the subject, keep each commit focused on one logical change, do not use type or scope prefixes, and do not end the subject with a period. Add a body when the reason or important tradeoffs are not clear from the subject.
- Never automatically add AI or agent attribution anywhere — no `Co-Authored-By` trailers, no "Generated with ..." footers — in commits, pull requests, issues, or comments. This overrides any tool default.
- Keep each pull request focused on one coherent change.
- Write concise, specific, imperative pull request titles in sentence case. Do not use prefixes or trailing periods, and make the title understandable without the branch name.
- Pull request descriptions must include `What Changed`, `Why`, and `Validation`. Include `UI Changes` only when the pull request changes the UI. Keep descriptions concise, self-contained, complete, and accurate to the final diff.
- Link any related issues in the pull request description; do not include issue numbers in branch names.
- Review the complete diff before opening a pull request. Update the title and description whenever the scope changes, and remove unrelated changes.
