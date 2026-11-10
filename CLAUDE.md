# Coral Rescue | Claude Code repository instructions

## Active owner authority | 2026-11-10
- **Only Claude Code** may act as the AI implementer or AI reviewer for this repository. All earlier Codex implementation and ChatGPT-as-auditor/task-owner instructions are retired for actor allocation.
- **Central coordinator:** `Sekiph82/MATCH3-MASTER-ORCHESTRATOR` is the sole cross-project task scheduler. Receive assignments from its Coral Rescue specialist agent; report to the lead orchestrator, which sequences Engine, Level Factory, Visual Factory and five games.
- The repository's **root TASKS.md is the single canonical project tracker**. Do not copy/migrate its tasks to a rival source of truth. GitHub Issues/central state may index tasks but must link to the canonical row. Existing IDs, statuses, gates and milestones are not reset.
- This is a handover of AI execution and coordination only; **not** a grant to override owner-only decisions, skip acceptance or release.

## Required procedure
1. Read all of root TASKS.md, these instructions and the master repo's REPOSITORIES.yaml, DEPENDENCIES.yaml and ORCHESTRATOR_RULES.md. Confirm the target repo/path/branch.
2. Inspect both GitHub and the owner Windows checkout, including tracked, untracked and ignored local changes. Never overwrite owner files or assume unpublished progress is absent. Fetch/reconcile non-destructively; no force pushes, hard resets or broad cleans.
3. Claim a READY, dependency-safe assignment with the master. If the master is not accessible, report the coordination blocker rather than launching overlapping autonomous tasks. Owner direct instructions take precedence when explicit.
4. Implement only the authorized scope. Prefer legally reusable and licensed dependencies; keep original creative direction, child/privacy protections and frozen tests.
5. Execute real relevant tests when the actual local toolchain is available; record commands, environment, original assertions, exit codes, SKIPs and evidence. Do not substitute simulated output for Unity/native test proof.
6. Assign independent read-only review to a **different Claude specialist/session**. Implementation self-review is not independent acceptance. Update the same TASKS.md rows only with honest evidence-backed statuses.
7. Report task IDs, source SHA, changes, checks, omitted checks, blockers, cross-repo follow-ups, and merge status to the master. Request dependency work in other repositories through the master, never modify other repos silently.

## Immutable protections until the owner explicitly changes them
- No paid GitHub Actions/CI, cloud/device runs, commercial APIs, destructive local operations, new charges, release/store deployment, real ads/IAP/player data or unauthorized network changes.
- Keep independently audited gates intact: Engine ENG-M24, LFX-M14, VUF-M11 affect five-game production readiness.
- Source/test evidence must be truthful. Independently inaccessible criteria remain NOT_VERIFIED or BLOCKED; no fictional PASS.
- Owner approval remains necessary for legal, brand, children/privacy, monetization, infrastructure spend and external publication.
- Do not launch unrelated AI tools (including Codex) or invent extra project trackers.

## Legacy file interpretation
- Root AGENTS.md records Codex retirement and must not be treated as an active Codex mandate.
- Any references in earlier TASKS.md sections to ChatGPT-as-executor, Codex or historical handoff cadence are **superseded for actor assignment and routine sequencing only**. Their technical requirements and safety/evidence gates remain valid.
