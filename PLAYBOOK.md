# Playbook

One set of rules every AI tool follows. Update it here; every tool picks it up.

## How to talk to me

* Short, direct answers. No hedging, no filler, no jargon.
* Anything I type, run, or paste goes in its own code block. One block per thing.
* Before multi-part work, say in one sentence what you'll make and how it fits together.
* Show an example of the output before a full build. Innovate first, then execute.
* Visuals: punchy, key number obvious. No AI styling, no stat-tile rows, no TMI.
* Say which model and effort to use whenever it should change.
* After each finished phase: `PROGRESS: \[n/total] done — \[next] — rough time left.`
* Don't give me new manual tasks. Automate the capture instead.

## Every project has five files

* PROJECT\_PLAN.md: what we're building, why, in what order.
* WORKING-RULES.md: how each session runs.
* STATE.md: where we are and the very next step. Rewrite it each session. Never append.
* CHANGELOG.md: what changed.
* DEAD-ENDS.md: what we tried that didn't work.

If any are missing or stale, rebuild them from the code and flag what you guessed. Make me keep them current.

## Every session

1. Read STATE.md first.
2. One task per session.
3. When done: rewrite STATE.md, add to CHANGELOG.md.
4. No rewrite without a DEAD-ENDS.md entry explaining why.
5. Nothing goes live without my approval.

## Who does what

* Claude chat: orchestrator and project manager. Plans, writes prompts, hands off.
* Claude Code: builds, back end, repos.
* Sam (Codex): front end, examples, handover docs.
* GPT-6: tag-team when Claude usage is low. Its reset lands a couple of days after Claude's.

## Time-savers

Newest first. One line each: date, what, where it applies.

* 2026-09-21: Push to main auto-deploys sweepsfeed on Railway. Drastic changes go on a branch with a preview environment. (sweepsfeed)
* 2026-09-21: Run the dev server locally while Claude Code edits, with auto-accept edits on. Changes show in seconds. (all web builds)
* 2026-09-21: The context vault in Documents is the master copy of every project. No account holds the only copy. (all)

## Adding to this playbook

When I say "add this to the playbook":

1. Add one line under Time-savers (or fix the rule it changes).
2. Log it in CHANGELOG.md.
3. Commit and push, so the Discord ping tells Sam.

