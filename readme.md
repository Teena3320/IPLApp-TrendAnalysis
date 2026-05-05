# Runs Before First Wicket – Trend Analysis
## Overview
This project explores the relationship between runs scored before the fall of the first wicket and match outcomes in limited‑overs cricket.
The analysis focuses on identifying historical trends and patterns that explain how early batting stability influences the likelihood of winning a match.
Note: This is a trend and exploratory analysis, not a predictive model.
The aim is to understand associations, not to forecast match results.
---
## Scope of Analysis
Innings Considered
Only standard batting innings were included:

Innings 1 (team batting first)
Innings 2 (team batting second)

Records labeled as innings 3, 4, 5, or 6 were excluded.
These values typically arise due to:

super overs,
abandoned or restarted matches,
data ingestion artifacts.

Such records do not reflect normal match structure and were removed to maintain conceptual clarity and consistency in the trend analysis.
---
## Methodology Summary

First Wicket Identification

The delivery where the first wicket fell was identified for each team innings.

Runs Before First Wicket

Total runs scored up to (but excluding) the first dismissal were calculated.
This represents the opening partnership contribution, including extras.

Bucketing for Trend Clarity

Runs were grouped into logical ranges:

0–10, 11–20, 21–30, 31–40, 41–60, 60+

Bucketing reduces noise and highlights meaningful patterns.

Outcome Association

Each innings was labeled as a win or loss based on the match result.
Win percentages were computed per bucket to observe trends.
---

## Key Trends Observed

Early wicket losses are common, especially within the first 10–20 runs.
Win percentage increases steadily as more runs are scored before the first wicket.
There is no single threshold that guarantees success; the advantage builds gradually.
Innings with stable opening partnerships (30+ runs) consistently show higher win rates.

These findings quantitatively support a long‑held cricketing insight:
avoiding early wickets materially improves match outcomes.
---
## Visual Analysis Included

Distribution of runs scored before the first wicket
Comparison of first‑innings vs second‑innings distributions
Win percentage across runs‑before‑first‑wicket buckets

All visualizations are designed to explain patterns, not to make predictions.
---
## Interpretation Notes

This analysis demonstrates association, not causation.
Runs before the first wicket are one of many factors influencing match results.
Conditions such as pitch, opposition strength, middle‑order performance, and match context are outside the scope of this study.
---
## Key Takeaway

Teams that score more runs before losing their first wicket consistently show higher match‑winning percentages, highlighting the strategic importance of opening‑partnership stability in limited‑overs cricket.
---
## Intended Use
This repository is suitable for:

Exploratory sports analytics
Cricket performance analysis
Data storytelling and visualization
Academic or portfolio projects

It is not intended for live match prediction or decision automation.