
# PSVS Lab - Defect Log

**Project:** Polar Seed Vault System  
**Activity:** Requirements Verification  
**Branch:** defect-analysis

## 1. Defect Log Table

| Defect ID | Req ID | Category | Description | Evidence | Severity | Suggested Fix | Status |
|---|---|---|---|---|---|---|---|
| D01 | S2 | Vagueness | The phrase "large number" is not clear. | S2 does not mention an exact capacity. | Medium | Specify the capacity of each chamber. | Open |
| D02 | S6 | Vagueness | The term "safe temperature" is unclear. | S6 does not give a temperature range. | High | Define the safe temperature range. | Open |
| D03 | S9 | Vagueness | The word "promptly" does not tell us how much time is allowed. | S9 gives no time limit. | Medium | Set a clear time limit for flagging samples. | Open |
| D04 | S12 | Vagueness | The phrase "good audit trail" is not specific. | S12 does not explain what makes the audit trail complete. | Medium | List the information that must be recorded. | Open |
| D05 | S1 | Incompleteness | The steps for registering a depositor are missing. | S1 only says that depositors must be registered. | Medium | Add the registration and approval process. | Open |
| D06 | S3 | Incompleteness | The system's action when a chamber becomes full is not mentioned. | S3 only gives the maximum number of boxes. | Medium | Explain what happens when the limit is reached. | Open |
| D07 | S4 | Incompleteness | The method for checking a depositor's identity is not given. | S4 restricts withdrawals but does not explain identity checking. | High | Define an identity verification method. | Open |
| D08 | S5 | Ambiguity | The meaning of an emergency is not explained. | S5 does not list the conditions considered emergencies. | High | Define the emergency conditions. | Open |
| D09 | S5 | Ambiguity | The term "requesting party" is unclear. | S5 does not explain who can request a box. | High | Clearly define who is allowed to make a request. | Open |
| D10 | S7, S8 | Contradiction | The normal temperature limit and maintenance exception are not clearly connected. | S7 sets a maximum of -18°C, while S8 allows warming to 0°C. | High | Clearly state when the maintenance exception is allowed. | Open |
| D11 | S4, S5 | Contradiction | Normal withdrawal is limited to the depositor, but emergency release may be made to any requesting party. | S4 and S5 give different rules for releasing boxes. | Critical | Define the emergency approval process and its priority over the normal rule. | Open |
| D12 | S10 | Incompleteness | The method for calculating the 20% withdrawal limit is missing. | S10 does not explain rounding or how withdrawals are counted. | Medium | Define the calculation method. | Open |
| D13 | S10 | Ambiguity | "Per year" could mean a calendar year or any 12-month period. | S10 does not define the yearly period. | Medium | Specify the period used for calculation. | Open |
| D14 | S11 | Incompleteness | The requirements do not explain what must be checked during re-inspection. | S11 requires re-inspection but gives no criteria. | Medium | Define the inspection checks before redeposit. | Open |
| D15 | S12 | Non-verifiability | It is difficult to test whether the audit trail is "good" without clear criteria. | S12 does not give measurable audit requirements. | High | Define required records and how completeness will be checked. | Open |
| D16 | S2, S3 | Redundancy / overlap | S2 and S3 both discuss chamber capacity, but at different levels of detail. | S2 says "large number" while S3 gives exact limits. | Low | Make S2 refer to the capacity limits defined in S3. | Open |
| D17 | S1, S4 | Incompleteness | The process for linking each box to its depositor is not described. | S1 covers registration and S4 covers ownership, but the link between them is not explained. | Medium | Define how each box is linked to its depositor's record. | Open |
| D18 | S9 | Non-verifiability | The system cannot reliably decide which samples have low viability without a defined threshold. | S9 does not state a viability limit. | High | Set a measurable viability threshold. | Open |


These findings are initial observations and should be checked during peer review.

