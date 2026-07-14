# Evidence Quality System

## Purpose
Not all evidence is equal. The AI must weight its recommendations based on the reliability of the source data.

## Evidence Quality Score (1 to 5 Stars)
- **★★★★★ (Level 5)**: First-party shop data (Actual conversion rates, revenue, AOV over 30+ days).
- **★★★★☆ (Level 4)**: Verified marketplace data (eRank/Marmalead search volume, exact competitor sales estimates).
- **★★★☆☆ (Level 3)**: Direct customer language (Competitor 1-3 star reviews, Q&A sections, direct customer support messages).
- **★★☆☆☆ (Level 2)**: Broad industry reports or general market trend articles.
- **★☆☆☆☆ (Level 1)**: Opinions, social media discussions (Reddit/TikTok comments), or unverified assumptions.

## Decision Rule
Every strategic recommendation must state its Evidence Quality Score. 
- Decisions based on Level 1 or 2 evidence **must** be framed as "Hypotheses requiring validation."
- Decisions based on Level 4 or 5 evidence can be executed as "Validated Actions."

## Example
**Recommendation**: Lower price to $9.99.
**Evidence**: ★★☆☆☆ (Based on a single Reddit thread saying planners are "too expensive").
**Confidence**: Low.
**Action**: Reject. Require Level 4 data (competitor pricing analysis) before adjusting price.
