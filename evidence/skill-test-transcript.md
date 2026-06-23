# Skill Test Transcript

## Skill tested

`skills/assess-ai-use-case/SKILL.md`

## Persona used

`personas/AI-Assessment-Lead.md`

## Trigger phrase used

Assess this AI use case: a business team wants to use Copilot to summarise customer feedback emails, identify recurring themes, and create a weekly insight report for managers.

## Assistant output

I’ve read the AI Assessment Lead persona and the Assess AI Use Case skill, and I’ll use that workflow when you use the trigger phrases.  

## Executive Summary

**Recommended decision: Proceed with conditions.**

This is a strong candidate for a controlled Copilot pilot because it addresses a plausible business need: turning high-volume customer feedback into usable management insight. However, it should not move straight into delivery until the team confirms data sensitivity, ownership, quality controls, and how the weekly report will drive decisions.

## Business Problem

The business team appears to be dealing with customer feedback emails that are difficult to review consistently, compare over time, and convert into actionable themes for managers.

The core problem is not “we need Copilot.” It is:

**Customer feedback is likely being reviewed manually or inconsistently, meaning recurring issues, risks, opportunities, and service themes may be missed or reported too slowly.**

## Expected Benefits

| Benefit type         | Potential benefit                                                                                                                     |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Measurable benefits  | Reduced manual time spent reviewing emails; faster production of weekly insight reports; improved consistency of theme identification |
| Qualitative benefits | Better visibility of customer sentiment, recurring pain points, and emerging issues                                                   |
| Beneficiaries        | Managers, customer experience teams, operational teams, service improvement leads                                                     |
| Evidence needed      | Current time spent reviewing feedback, volume of emails, reporting frequency, examples of missed or delayed insights                  |

## Assessment Summary

| Assessment area     | Finding                                                                                                       | Confidence |
| ------------------- | ------------------------------------------------------------------------------------------------------------- | ---------- |
| Business problem    | Valid problem if feedback volume is high or current reporting is inconsistent                                 | Medium     |
| Expected value      | Potentially useful if insights inform decisions, actions, or service improvements                             | Medium     |
| Feasibility         | Feasible for a Copilot-assisted workflow, provided data is accessible and permissions are appropriate         | Medium     |
| Risk                | Moderate risk due to customer data, privacy, summarisation accuracy, and over-reliance on AI-generated themes | Medium     |
| Adoption complexity | Moderate; managers must trust and use the report, and users need guidance on checking outputs                 | Medium     |
| Strategic alignment | Likely aligned if customer insight, service improvement, or efficiency are priorities                         | Medium     |

## Feasibility Assessment

This looks technically feasible as a Copilot-supported use case, especially if the emails sit within Microsoft 365 and permissions are already well controlled.

Key feasibility considerations:

* **Data access:** Can Copilot access the relevant mailbox, shared mailbox, folder, or exported feedback set?
* **Data quality:** Are the emails structured enough to summarise meaningfully?
* **Volume:** Is there enough feedback to justify a weekly thematic report?
* **Process maturity:** Is there already a reporting process, or would this create a new one?
* **Human review:** Someone must validate themes before managers rely on the output.

## Risk Assessment

| Risk                        | Why it matters                                                           | Suggested mitigation                                                         |
| --------------------------- | ------------------------------------------------------------------------ | ---------------------------------------------------------------------------- |
| Privacy and customer data   | Customer feedback may contain personal or sensitive information          | Confirm data classification, retention rules, and approved handling approach |
| Inaccurate summaries        | Copilot may miss nuance, over-generalise, or misclassify themes          | Require human review before circulation                                      |
| Bias toward frequent topics | High-volume complaints may crowd out important but lower-frequency risks | Include severity and examples, not just frequency                            |
| Weak value realisation      | Weekly reports may be produced but not acted upon                        | Define the management decision or action the report supports                 |
| Adoption risk               | Managers may not trust the insights or may ask for more detail           | Pilot with a small group and gather feedback                                 |

## Dependencies

* Named business owner for the feedback process.
* Clear owner for the weekly insight report.
* Agreement on which emails are in scope.
* Confirmation of data privacy and security requirements.
* Standard report format.
* Quality-check process before publication.
* Success measures, such as time saved, reporting speed, insight quality, or action follow-up.

## Prioritisation Recommendation

**Priority: Medium to High, subject to evidence.**

This should rank well if the team can prove that feedback volume is meaningful, current reporting is time-consuming, and managers will use the insight to make decisions. Without that evidence, it risks becoming a “nice-to-have” reporting automation rather than a high-value AI use case.

## Recommended Decision

**Proceed with conditions.**

### Conditions

1. Confirm the business problem with evidence: email volume, current effort, current reporting gaps.
2. Define the success measure before piloting.
3. Confirm customer data handling, privacy, and access permissions.
4. Keep a human review step before any weekly report is shared.
5. Pilot with a defined group before scaling.

## Next Steps

1. **Business owner:** Confirm the problem, users, report audience, and desired decisions supported by the weekly insight.
2. **Process owner / BA:** Capture current baseline effort and reporting pain points.
3. **Data / governance lead:** Confirm whether customer feedback emails can be safely processed using Copilot.
4. **Pilot team:** Run a four-week pilot using a standard prompt and report template.
5. **Sponsor / managers:** Review whether the report improves decisions, actions, or visibility enough to justify scaling.
