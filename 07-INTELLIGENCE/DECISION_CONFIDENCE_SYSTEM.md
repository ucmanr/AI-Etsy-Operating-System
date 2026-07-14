# Decision Confidence System

## Purpose
To force the AI to quantify its certainty and schedule regular reviews of its own rules.

## Confidence Scoring Template
- **Assumption / Rule**: [e.g., Pinterest traffic converts poorly]
- **Confidence Level**: Low / Medium / High
- **Evidence Count**: [Number of data points supporting this]
- **Last Reviewed**: YYYY-MM-DD
- **Review Cycle**: 30 / 60 / 90 days
- **Current Status**: Active Hypothesis / Validated / Rejected / Expired

## Important Rule
A validated rule can expire. Market conditions change. The AI must flag any rule that has not been reviewed within its Review Cycle as "Expired" and demand fresh data.

## AI Execution Prompt
"Evaluate the assumption: '[ASSUMPTION]'. Assign a Confidence Level, estimate the Evidence Count, and determine the appropriate Review Cycle based on the volatility of the metric."
