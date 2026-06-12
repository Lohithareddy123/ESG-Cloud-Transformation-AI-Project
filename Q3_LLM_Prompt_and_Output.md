# Q3 - LLM Prompt and Output

## Prompt Template

An employee has submitted an ESG-related operational message.
Extract the relevant issue details and return JSON only.

Return:
- issue_category
- urgency
- sentiment
- followup_required
- recommended_team
- escalation_reason
- data_sensitivity_risk
- brief_summary

## Example Input
"There is a water leak in Building C that has been running all morning."

## Example JSON Output

{
  "issue_category": "water",
  "urgency": "HIGH",
  "sentiment": "NEGATIVE",
  "followup_required": "Y",
  "recommended_team": "Facilities Maintenance Team",
  "escalation_reason": "Ongoing water leak may lead to waste and damage.",
  "data_sensitivity_risk": "LOW",
  "brief_summary": "Water leak in Building C requiring attention."
}
