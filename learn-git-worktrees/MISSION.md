# Mission: Git Worktrees for Parallel Agentic Coding

## Why

I use multiple AI coding agents running in parallel on different branches. Right now that means either stashing, cloning a second copy of the repo, or juggling temporary branches in one working directory — all of which are fragile and slow. I want to understand git worktrees deeply enough that I can spin up an isolated working directory per agent, share a single `.git` repository (fast, no re-cloning), and never accidentally step on my own state. This is infrastructure for my daily workflow.

## Success looks like

- Spinning up a new worktree for a parallel coding agent in one command, without thinking
- Knowing exactly what is shared between worktrees and what is isolated — no surprises about state collisions
- Cleaning up stale worktrees confidently when a branch is merged or abandoned
- Reasoning about the internal model well enough to debug when something goes wrong (detached HEAD, rebase conflicts across worktrees, etc.)
- Explaining the worktree mental model to another developer in under two minutes

## Constraints

- Self-paced — quality of mental model over speed
- Terminal-first — lessons should involve running actual git commands in my real repos
- Applied to my actual agentic coding workflow, not abstract scenarios
- MacOS / zsh environment

## Out of scope

- `git bisect` workflows (useful but not my primary use case)
- Bare repository worktree setups (server-side patterns)
- Git internals beyond what's needed for the mental model (no object-database spelunking)
- Submodules in worktrees (tackle separately if needed)
