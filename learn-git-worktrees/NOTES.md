# Teaching Notes — Git Worktrees

## User Preferences

- **Terminal-first.** Lessons should center on running real git commands in real repos. The user learns by doing.
- **Mental model over recipe.** The goal is to understand the structure well enough to reason from first principles, not to memorize command sequences.
- **Agentic coding context.** Every concept should tie back to the user's actual workflow: multiple AI coding agents running in parallel on different branches.
- **MacOS / zsh.** All terminal examples should use zsh syntax and macOS paths.

## Zone of Proximal Development

- Git competence: strong. Comfortable with branches, rebasing, stashing, reflog, detached HEAD, and the three-tree model (working directory, index, HEAD).
- Worktree knowledge: zero. Has heard of them but never used one.
- Starting point: the mental model — what IS a worktree, in terms of things the user already understands (the `.git` directory, the working tree, branches as pointers).

## Sequencing Principle

The course builds from the mental model outward:

1. **Lesson 0000: The Mental Model** — What a worktree is, the problem it solves, and the architectural intuition. No commands yet (beyond peek-at-it commands like `ls` and `tree`).
2. **Lesson 0001: Creating & Listing Worktrees** — `git worktree add`, `git worktree list`, the directory structure that results, and what gets shared vs. isolated.
3. **Lesson 0002: Working in Parallel** — The actual agentic coding workflow: spin up a worktree per agent branch, work concurrently, merge back. Covers the lifecycle from creation to cleanup.
4. **Lesson 0003: Edge Cases & Debugging** — Detached HEAD in a worktree, rebase conflicts across worktrees, pruning stale worktrees, what happens when a branch is deleted on another worktree.
5. **Lesson 0004: Advanced Patterns** — Using worktrees for hotfixes on main while deep in a feature, bisect worktrees, and organizing worktree directories.

## Glossary Note

Create GLOSSARY.md once the user has demonstrated understanding of at least 5-6 worktree-specific terms. Don't pre-populate it.
