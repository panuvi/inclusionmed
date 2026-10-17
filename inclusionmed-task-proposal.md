# InclusionMed task / benchmark proposal

An initial idea can be brief: describe the healthcare need or benchmark and
share an example or reference if available. The fields below are prompts for
developing the proposal with collaborators, not a checklist to complete at the
start. Leave unknown details open for discussion.

To offer review or expertise, describe your background, the work you can help with
and your availability.
The organizers fill in the review record.
Do not include identifiable patient information, credentials or restricted source data.
Describe access conditions and use approved sharing arrangements for protected materials.

## 1. Contributor and proposal

- Title:
- Contributor(s), affiliation (optional), and project contact:
- Proposed owner / maintainer:
- Task or benchmark ID and version (if existing):
- Contribution: healthcare task / existing benchmark / review or expertise
- Input, expected output and interaction (for example, choice or free-text answers, with or without tools; describe other formats as needed):
- What can you provide, and what help do you need?
- Availability, if offering review or technical support:

## 2. Real healthcare need

- Who needs help, and in what setting?
- What action should the system support?
- What inputs are available, and what output is expected?
- Shareable input/output example (use a synthetic example if needed):
- What constitutes a useful, successful outcome?
- What is outside the task's scope?

## 3. Classification and scope

- Atlas role: Patients & Families / Healthcare Professionals / Service & Administrative Staff
- Atlas AI capability: Knowledge / Reasoning / Execution
- Languages, regions, populations and resource conditions:
- Why do the Atlas role and AI capability fit the actual task?
- If splitting an existing benchmark: original IDs, proposed subsets, and overlap:

## 4. Medical and professional basis

- Source of cases / task inputs:
- Source and authorship of reference answers and scoring criteria:
- Qualified human reviewers and relevant expertise:
- Task-defined evaluation criteria, supporting evidence and any critical-error rules:
- Relevant safety boundaries and limitations:
- Any AI assistance used in preparing materials; how was it reviewed?

LLM-generated annotations must not serve as reference answers or scoring criteria.

## 5. Materials and use conditions

- Task, reference, scoring code and documentation locations:
- Original licence(s) and reuse / redistribution permissions:
- Public, controlled or restricted access; approval procedure if applicable:
- Format version (`0.1`), stable sample IDs, field dictionary, units and missing values:
- Input / reference separation, upstream field mapping and any agreed format deviations:
- Sample counts, splits, duplicates, exclusions and overlap:
- Known training-data exposure or contamination risks:
- De-identification and required approvals; check metadata and logs too:
- Versioned storage links for large files:
- Missing assets or permissions still to resolve:

## 6. Reproduction package (technical collaborators can help)

Define the evaluation method for your task. Explain the criteria, metrics and result handling; include levels, weights, thresholds or a total score only if your method uses them.

- Versioned data / task set and evaluation code:
- Setup and run instructions, dependencies and environment:
- Hardware, memory, expected runtime, API costs and resource provider:
- Model version, prompts, tools, configuration and scoring method:
- If answers use choices: answer evaluation method, reference evidence and any matching or normalization rules:
- If answers are open-ended: task-defined evaluation method, human-reviewed criteria and disagreement resolution:
- If the task uses tools or an environment: initial state, reset, tools, access limits, step/time budgets, completion checks and tool traces:
- Metric meanings, calculation or decision procedure, aggregation where applicable, and handling of missing or failed runs:
- Run IDs, predictions, per-sample scores, status counts, denominators and retry records:
- Small trial run, expected outputs and scoring / failure-case checks:
- Outputs, logs and trial-run results available for review:
- How can an independent authorised reviewer reproduce the evaluation?

## 7. Added value and representation

- Related tasks / benchmarks and overlap:
- What new evidence does this add?
- Which representation gap, if any, does it address?
- Involvement of relevant people or local professionals:

## 8. Review and release record

- Current proposal status, owner and next step:
- Proposal received on:
- Initial review date and next step (when agreed):
- Initial-review decision, missing materials and assigned collaborators:
- Agreed review package, reproduction scope and resources:
- Next review date, delays or paused work:
- Medical review:
- Evaluation-method review:
- Technical trial:
- Independent review:
- Reviewer conflicts of interest and independent final reviewer:
- Acceptance / revision / deferral / decline decision, date and rationale:
- Review items, contributor responses, updated versions and reviewer resolution:
- Credits, maintenance plan and proposed release version:
- Release link and date (record separately from PR merging):

See the [contribution guide](../../CONTRIBUTING.md) for review and inclusion, and
[Data and code baseline v0.1](task-format.md) for fields, examples and checks.
