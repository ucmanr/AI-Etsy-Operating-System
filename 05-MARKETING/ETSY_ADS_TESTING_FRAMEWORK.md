# Etsy Ads Testing Framework

## Purpose
To safely and profitably scale winning products using Etsy Ads, without burning budget on unproven listings.

## The Golden Rule of Etsy Ads
**NEVER run ads on a listing with an organic Conversion Rate (CVR) of < 1.5% or < 500 views.** Ads amplify what is already working; they do not fix broken listings or bad SEO.

## The Testing Protocol
1. **Select the Candidate**: Choose a listing with > 1.5% organic CVR and > 10 favorites.
2. **Set the Budget**: Start at $1.00 - $2.00 per day. Do not exceed this until the listing proves profitable.
3. **Run Time**: Let the ad run for exactly 14 days. Do not touch, pause, or tweak it during this period (Etsy's algorithm needs time to learn).
4. **Evaluate (Day 15)**: 
   - If ROAS (Return on Ad Spend) > 3.0: Increase budget by 20%.
   - If ROAS is 1.5 - 3.0: Maintain budget, monitor for another 14 days.
   - If ROAS < 1.5: Turn off ads. The listing is not ready for paid traffic. Return to `08-DATA/OPTIMIZATION_ENGINE.md`.

## AI Execution Prompt
"Analyze this 14-day Etsy Ads data for '[PRODUCT NAME]': [PASTE DATA]. Calculate the ROAS and CPA (Cost Per Acquisition). Based on the Etsy Ads Testing Framework, recommend whether to scale, maintain, or kill the ad campaign, and explain why."
