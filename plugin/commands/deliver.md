---
description: Verify, push, measure, and deliver the current OverClick card.
---

Load the bundled `overclick` skill and read its linked canonical `OVERCLICK.md`.
Find this token's single executing card with `task_list`
using `status: "em_execucao"` and `claimed_by: "me"`; stop if there is none or
more than one. Run its binary confirmation checks, commit with the card prefix,
and push the registered branch. Cite the full Git commit ID in evidence. Run
the claim's `measure.command` (it runs the plugin's local `bin/measure.cjs`; lost
it? `task_get { include: ["usage_recipe"] }` has the full recipe), then call `task_deliver` with a
truthful summary, check results, branch, verification entry point, transcript,
and measured usage. Never mark the card validated.
