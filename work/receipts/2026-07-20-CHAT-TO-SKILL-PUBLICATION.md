# Chat-to-SKILL.md Publication Receipt

## Result

`COMPLETE_CANDIDATE_AWAITING_INDEPENDENT_EVALUATION`

## Published

- Prompt: `prompts/instruction-runtime/CHAT-TO-SKILL-SKILL-EXTRACTION-WARRANT-AND-PACKAGING.md`
- Stable ID: `mp.instruction.chat-to-skill`
- Prompt commit: `23a5e7ca3a558a42474d98b6623b2f8fb78e05bc`
- Registry entry commit: `f1ba59ea53a6c7c312632582453a7db76114f565`
- Registry count commit: `3cb1739a6b4b56bca1cd820c27288200a4cf17f0`
- Work-state reconciliation: `93258e5b699dfb9603a6b3e3abbaf92fff2b5b5a`
- Manifest addendum: `e99f9cb72e9f06e20ae5afd694ca4aed76aa3da5`
- Reconciliation receipt: `d708adb59087e084c4cd32ac9366de1f1f24f7cf`
- Skill-warrant fixtures: `944edcc847a7d92bbd9fc0a80f6ac888c073861c`
- Taxonomy addendum: `35c1b6c6be56cc575afed53c0eec44ccae10af47`
- Suite addendum: `9cc062e1d6be937a5d27a4318f7eaf41f20a05a3`

## Capability boundary

The factory extracts recurring operational capability from conversations and artifacts, applies a skill warrant, produces the smallest valid `SKILL.md` package for the target dialect, tests positive and negative triggers, and routes non-skill value to the better artifact type.

It explicitly distinguishes skills from prompts, instructions, policies, agents, workflows, scripts, tools, documentation and Golden Records. Publication or installation grants no tool permission, repository authority or canonical adoption.

## Validation

- prompt file reread successfully;
- extension registry entry reread successfully;
- authoritative prompt count is 25 through the registry index and manifest addendum;
- eight warrant fixtures cover positive, negative, duplicate, deterministic, restricted and unverifiable-dialect cases;
- taxonomy and suite changes are preserved as additive files because direct consolidation collided with concurrent provider writes and safety blocks.

## Remaining gate

Run the factory against at least one unrelated conversation containing both strong skill candidates and strong non-skill candidates. Test more than one target harness dialect before promoting the prompt from candidate status.

## Exact resumption

Execute the chat-to-skill fixture evaluation as part of `MPL-EVAL-001`, then consolidate the taxonomy, suites and base manifest only after rereading the current remote head and preserving all concurrent extensions.
