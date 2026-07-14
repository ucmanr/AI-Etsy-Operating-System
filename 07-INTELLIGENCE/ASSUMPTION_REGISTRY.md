# Assumption Registry

## Purpose
To explicitly track which business rules are proven facts vs. active hypotheses, preventing the AI from hallucinating certainty.

## Classification Types
| Type       | Meaning                                  | Action Required                     |
| ---------- | ---------------------------------------- | ----------------------------------- |
| Fact       | Proven by reliable, recent evidence      | Use as baseline rule                |
| Hypothesis | Belief requiring validation              | Design low-cost experiment to test  |
| Estimate   | Approximation based on limited data      | Refine with more data               |
| Prediction | Future expectation                       | Monitor and adjust as data arrives  |
| Experiment | Temporary test of a specific variable    | Run for set duration, then evaluate |

## Registry Template
| Metric / Rule             | Current Value | Classification | Confidence | Evidence Count | Validation Method                          | Status          |
|---------------------------|---------------|----------------|------------|----------------|--------------------------------------------|-----------------|
| Digital Planner CVR       | 2.5%          | Hypothesis     | Medium     | 1 (Industry)   | Analyze top 20 competitors + 30d shop data | Pending         |
| Bundle Price Multiplier   | 1.5x          | Hypothesis     | Low        | 0              | A/B test two bundle price points           | Needs Experiment|
| ADHD Planners need Dark Mode | False     | Fact           | High       | 15 (Reviews)   | Review mining of top 10 competitors        | Validated       |

## AI Execution Rule
When proposing a new strategy, the AI must check this registry. If the underlying assumption is marked "Hypothesis", the AI's first recommended action must be to design a low-cost experiment to validate it.
