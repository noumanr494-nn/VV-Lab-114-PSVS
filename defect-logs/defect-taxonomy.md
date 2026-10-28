
# PSVS Lab - Defect Taxonomy

**Project:** Polar Seed Vault System

## Purpose

This taxonomy explains the common types of defects that can occur in system requirements. It helps us classify the problems found during requirements verification.

## Defect Categories

| No. | Category | Definition | Example from PSVS Requirements |
|---|---|---|---|
| 1 | Ambiguity | A requirement has more than one possible meaning. | S5 uses "requesting party" without defining who it means. |
| 2 | Vagueness | A requirement uses unclear words without exact limits. | S6 uses the phrase "safe temperature". |
| 3 | Incompleteness | Important information is missing from a requirement. | S1 does not explain how a depositor is registered. |
| 4 | Contradiction | Two requirements give conflicting instructions. | S4 restricts withdrawal to the owner, while S5 allows emergency release to another party. |
| 5 | Non-verifiability | A requirement cannot be checked clearly because measurable criteria are missing. | S9 does not define the viability level for flagging a sample. |
| 6 | Redundancy | Two requirements repeat the same information unnecessarily. | S2 and S3 both discuss chamber capacity, although S3 provides the exact limits. |
| 7 | Infeasibility | A requirement cannot realistically be achieved with available resources or technology. | No clear example can be confirmed from S1-S12 without more information about the system's resources. |
| 8 | Untraceability | A requirement cannot be linked clearly to its source, purpose, or related requirement. | The requirements do not identify the source or reason behind the 20% withdrawal limit in S10. |

