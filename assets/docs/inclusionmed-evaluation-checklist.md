# InclusionMed evaluation record

Fill this in when an evaluation run is available. Link existing records where they
cover the same details. Mark unmeasured or unavailable items explicitly.
Share only permitted outputs; keep patient identifiers, secrets and restricted data out of this record.

## Task & data

- Benchmark / task ID, submission reference, task version, dataset version and source links:
- Input, output and interaction pattern (including any combination or custom format), format version (`0.1`) and any agreed deviations:
- Included subsets, stable sample IDs, counts, splits, exclusions and overlap:
- Format, field dictionary, units and missing-value conventions:
- Input / reference separation, upstream IDs and adapter mapping:
- Licence, access procedure, de-identification and required approvals:
- Languages, regions, populations, settings and known coverage or contamination limits:

## Model & setup

- Exact model version or checkpoint, provider and run date:
- Code and data versions, runtime and pinned dependencies:
- Prompts, tools, input format and system instructions:
- Setup, small-trial, full-evaluation and scoring commands:
- Hardware, memory, runtime, API costs and resource provider:
- Required environment variable names (no credential values):

## Run conditions

- Sampling settings, random seeds, output limits and repeats:
- Retry rules, timeouts, failures and excluded runs:
- Run IDs, attempt records and the rule for selecting retry results:
- Deviations from the source protocol and their reasons:

## Task-specific checks

Check results against the task's documented evaluation method. Include scales, weights, thresholds and critical-error handling where that method uses them.

- Choice answers, if used: answer evaluation method, reference evidence and examples covering the chosen rules:
- Open-ended answers, if used: task-defined criteria, evaluator expertise, disagreement review and any model-assisted evaluation verification:
- Tools or environment actions, if used: environment version and reset, tool schemas, access limits, step/time budgets, final-state checks and complete tool traces:

## Scoring & review

- Metric meanings, calculation or decision procedure, scale and aggregation where applicable, and missing / failed-run handling:
- Reference sources, answer / rubric authors and qualified medical reviewers:
- Judgment criteria, any task-defined critical errors and adjudication of disagreements:
- Trial sample, expected outputs, checks performed and outcomes:
- AI assistance and human review; LLM-generated annotations cannot be reference answers or scoring criteria:

## Results & uncertainty

- Task-level results in the original metrics and evaluated sample counts:
- Planned sample count, counts by status, scored count, denominators and incomplete runs:
- Variation across runs or other uncertainty estimates, where measured:
- Missing results, known limitations and unmeasured uncertainty:
- Versioned links to permitted per-sample outputs, logs and result summaries:

## Reproduction & credit

- Independent reviewer's name or handle and access conditions:
- Agreed reproduction scope, environment, commands, versions and run date:
- Reproduced results, comparison tolerance, discrepancies and unresolved limits:
- Source attribution, contributor roles, conflicts of interest and maintenance contact:
- Organizer decision, date, release version / link and change log:
- Required revisions, contributor responses, reviewer resolution and remaining action dates:

See the [contribution guide](../../CONTRIBUTING.md) for the contribution and review process,
and [Data and code baseline v0.1](task-format.md) for the expected record formats.
