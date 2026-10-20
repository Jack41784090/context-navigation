---
name: context-navigation
description: >-
  Refactor agent context loading into task-specific disclosure without dropping
  applicable obligations. Use when asked to reduce mandatory instruction reads,
  slim AGENTS.md or CLAUDE.md, split large skills, untangle documentation read
  chains, or apply a context-navigation refactor to a repository or writing vault.
  Preserve safety, ownership, recording and acceptance rules while validating
  routes and reporting evidence honestly.
---

# Context navigation

Reduce unnecessary reading, not applicable obligations. Deliver a bounded,
reviewed refactor with an evidence receipt. Smaller files alone are not success.

## 1. Establish scope and baseline

- Read applicable inherited and local instructions. Load the relevant authoring
  workflow when available. Establish whether the request is proposal-only,
  read-only review or an authorized refactor. For no-edit requests, keep baselines,
  ledgers and the receipt in the response, skip file writes and commits, and label
  changes and checks as proposed unless actually performed. This skill does not
  replace project rules or authorize code execution, publication, native mutations
  or policy changes.
- Resolve repository boundaries, symlinks, generated mirrors and canonical files.
  Inspect Git status, index and current revision before editing. For an authorized
  refactor in a dirty tree, save exact pre-edit working copies outside the
  deliverable. User edits are the working baseline, not permission to commit them.
- Identify entrypoints, invoked skills, linked contracts, automatic harness
  context, tool restrictions and recording duties. Follow explicit read gates to
  find hidden mandatory chains. Distinguish a navigation link from a prerequisite.
- Define a narrow change list, representative tasks and a preservation ledger:
  obligation or permission, owner, trigger, conditions, destination and validation.
  Preserve explicit allowances and their constraints as well as prohibitions.
  Before choosing cuts, use [Routing patterns](references/routing-patterns.md).

Done when the baseline, owned edits, relevant obligations and task boundaries are
explicit. Ask only for ambiguity that prevents a safe scope or changes policy.

## 2. Design the routing

Classify each instruction:

1. **Always applicable:** concise authority, safety, ownership and recording
   invariants needed before selecting a task. Keep these reachable at startup.
2. **Task prerequisite:** read before a named action, interpretation or boundary.
   Put an explicit trigger beside its canonical destination.
3. **Reference:** details needed within a selected task. Keep coupled rules and
   caveats together, with relevant section pointers.
4. **Evidence:** historical audits, installation records and experiments. Reach
   them for provenance or verification, not routine execution.

Use a compact `Task boundary | Read before crossing it` table where helpful.
State that overlapping tasks combine all applicable rows. Include interpretation,
review, read-only discovery, planning and handoff when their contracts apply, not
only edits. A read-only label is not an automatic exemption from safety or privacy.

Preserve genuine session-start requirements, automatic recording and author-only
acceptance. Route technical examples through current authorization boundaries.
If existing instructions conflict, preserve the applicable higher-priority rule,
flag unresolved policy choices and avoid silently inventing an exception.

Done when each obligation has an effective trigger and representative tasks can
reach it without unrelated manuals or historical tours.

## 3. Make the bounded change

For a no-edit request, describe these changes without applying them.

- Edit canonical files, preserving aliases and mirrors. Do not edit upstream
  sources through symlinks or rebuild unrelated generated outputs.
- Move cohesive reference bodies with their caveats and provenance. Retain
  inbound heading anchors or explicit compatibility pointers. Correct moved
  relative paths and phrases such as "above" deliberately, recording exceptions
  to byte-for-byte preservation.
- Follow downstream prerequisites. A short entrypoint that loads the same giant
  manual through another document has not reduced the read chain.
- Keep policy changes separate from disclosure changes. Do not alter runtime
  behavior, acceptance states, tracker records, settings, shared model policy or
  authored content merely to prove a documentation refactor.
- Recheck concurrent changes before overwriting or staging. A task-specific todo
  list does not replace recording required by the project.

Done when all scoped edits exist and unrelated work remains intact.

## 4. Validate and review

Read [Validation and evidence](references/validation-and-evidence.md) before
selecting checks or claiming an outcome.

- Check affected files, paths, anchors, frontmatter, aliases and prerequisites.
  Compare moved bodies and the preservation ledger against the frozen baseline.
- Trace at least a routine task, a cross-boundary task and an adversarial case
  involving authority, recording, read-only discovery or dirty-tree ownership.
  Reuse [evaluation cases](evals/evals.json) as patterns, not project policy.
- Use an independent reviewer for consequential instruction changes when an
  authorized worker is available. Verify that the documents may be shared with
  that worker/provider before sending context, and minimize the shared data.
  Follow the host's model/access rules. Repair findings and rerun affected checks. If review is unavailable, report that limit.
- Run existing relevant fixtures only when authorized. Distinguish link checks,
  model proposals and fixture tests from native or runtime acceptance.

Done when every preservation claim has evidence, unresolved findings are bounded
and no applicable obligation has become an optional or unreachable reference.

## 5. Deliver and record

For an authorized refactor, write an evidence receipt in the project's existing
documentation location. For a no-edit request, return it in the response instead:

- Baseline revision and working-copy scope, changed files and preserved rules.
- Checks, observed outcomes, review corrections and remaining limitations.
- Separately labelled file bytes, static task read sets, observed agent reads and
  provider tokens. Include denominators and accounting boundaries for percentages.
- Whether this is a bounded pilot or measured acceptance. Never infer token or
  runtime savings from shorter files, one reused worker or source-grounded prose.

If Git is available and the request or applicable workflow authorizes commits,
stage only owned files or hunks. Inspect the index, commit and verify the final
state. Leave unrelated changes unstaged. Publication requires separate authorization and a verified destination.

Conclude briefly with the delivered change, validation, evidence location and any
real blocker. Do not call a pilot minimal, proven or globally optimal without the
measurements needed to support that claim.
