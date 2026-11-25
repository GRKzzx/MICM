# MICM

Anonymous repository containing the experimental materials for the manuscript
"When Harmless Words Harm: A New Threat to LLM Safety via Conceptual Triggers"
(double-blind review).

## Contents

### `materials/`

| File | Description |
|---|---|
| `evaluation-prompts.md` | The complete IAS evaluation prompts (verbatim): the neo-Nazi prompt used in the main experiment and the four ideology-specific prompts used in the generalizability experiment, each annotated with its target ideology. |
| `attack-template.md` | The attack prompt template used in the main experiment. The audience-demographics block and the deployed concept-embedded trigger combination are redacted; everything else is reproduced exactly as used. |
| `CET-pool.xlsx` | The candidate pool of 238 concept-embedded triggers (CETs) for the neo-Nazi orientation, from which the deployed combination was assembled. |
| `500-incidents.xlsx` | The 500 real-world political incidents used across all experiments (type, political issue, neutralized description). |
| `baseline-configurations.md` | Exact prompts, configurations, and stopping rules of the four baseline attacks (Evil, Comp, MultiJail, IRIS), documented verbatim from the experimental code. |
