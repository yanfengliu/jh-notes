# AGENTS.md

## Headless-first execution

Always work headlessly by default. This is a mandatory execution rule, not an adaptable default. Use a visible browser window, desktop application, GUI automation, or another non-headless interaction only when it is absolutely necessary to complete or adequately verify the task and no headless alternative is sufficient. State the reason before launching the non-headless path.

## Git and review hygiene

During substantial multi-step work, treat each minimal coherent unit as a delivery boundary: once it passes the applicable gates, review it immediately (self-review for trivial changes; adversarial review for behavior or public-contract changes), resolve substantive findings, stage only its scoped files, and commit it promptly before unrelated completed units accumulate in the worktree or diff. Never commit failing, in-flight, or partial work merely as a checkpoint.
