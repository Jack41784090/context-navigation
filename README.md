# Context navigation

An agent skill for replacing blanket instruction loading with task-specific
routes while preserving applicable safety, ownership, recording and acceptance
obligations.

## Use

Install this directory as `context-navigation` in your agent's skill directory.
For hosts that discover `~/.agents/skills`, use
`~/.agents/skills/context-navigation`. Otherwise use your host's documented global
skill directory and refresh its skill registry.

Invoke `/context-navigation` with a repository or documentation folder, for example:

> Refactor this project's mandatory instruction reads into task-specific routes.
> Preserve all applicable obligations, leave unrelated work untouched, and report
> the validation evidence without claiming unmeasured token savings.

The skill establishes a baseline, maps prerequisite chains, designs explicit
triggers, makes scoped documentation changes, checks preservation and records a
bounded evidence receipt. It handles overlapping tasks, imported references,
symlinks, dirty working trees and session-start obligations.

## Contents

- [SKILL.md](SKILL.md): the execution workflow.
- [Routing patterns](references/routing-patterns.md): examples and failure modes.
- [Validation and evidence](references/validation-and-evidence.md): checks,
  accounting boundaries and a receipt template.
- [Synthetic evaluation cases](evals/evals.json): maintenance routing, read-only
  safety boundaries, and dirty-tree/evidence discipline.

## Boundaries

This is a documentation refactor, not permission to change project policy,
execute restricted tools, install software, accept creative work, mutate runtime
state or publish project data. Existing host and project instructions still apply.

Examples are synthetic and intentionally exclude private project material.
Evaluation prompts are reusable checks, not a published benchmark. No token,
latency or reliability improvement is claimed merely because a file is shorter.

## Validation

Check frontmatter and local links, then exercise the synthetic cases with an
independent reviewer or isolated workers. Label static checks, proposal reviews,
paired trials and runtime tests separately. Keep private test outputs outside this
skill directory. See the evidence reference for stronger measurement criteria.
