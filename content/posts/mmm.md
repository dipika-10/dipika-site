---
title: MMM
date: 2026-09-12T13:22:00.000-04:00
draft: true
tags: []
---
# What MMM is?

1. What MMM is
Marketing Mix Modeling: a statistical (econometric) method that models aggregate outcomes(sales, enrollments, conversions) as a function of aggregate marketing spend across channels,plus external factors, to (a) estimate each channel's contribution and (b) allocate budget.
Top-down, aggregate, spend-focused.Built for channels you often CAN'T cleanly experiment on (TV, brand, broad media).
2. When MMM FITS (its sweet spot)
Allocating significant paid-media budget across multiple channels.Upper-funnel / brand / awareness media (Paze & Zelle acquisition media).Channels you can't A/B test (TV, radio, OOH, sponsorships).Decomposing aggregate outcomes into media vs external factors (seasonality, competition, pricing).Portfolio-level budget allocation across products/channels.
3. When MMM does NOT fit (use something else)
Lifecycle / CRM (email/SMS/push to known users) -> incrementality / holdouts."Would they have converted/returned anyway?" (winback) -> holdouts.Individual / segment-level targeting -> experimentation.Anything you CAN cleanly A/B test -> experiment (more rigorous than MMM's modeled estimate).Churn forecasting -> predictive / time-series models (drivers as inputs), NOT MMM.Retention budget to reduce churn -> incrementality on targeted programs.
4. MMM as an optimization problem
MMM estimates the RESPONSE CURVES (contribution + diminishing returns per channel).Budget allocation is the OPTIMIZATION on top:maximize outcome (ROI/revenue) SUBJECT TO constraints (total budget, channel min/max, rules).At the optimum: marginal return on the last dollar is EQUAL across channels.This is a classic constrained optimization -> connects to my Operations Research background.
5. Diminishing returns (how it's modeled)
Fit a CONCAVE saturation curve: spend on x, response on y; rises fast then flattens.Common forms: logarithmic, power/root (spend^a, a<1), S-shaped (Hill/sigmoid), negative-exponential.SLOPE of the curve = marginal return (return on the next dollar); it FALLS as spend rises.Where it flattens = SATURATION.Optimize by shifting budget from near-saturated channels to steeper-marginal-return channels.
6. MY ROLE with MMM (per the JD: translate needs -> requirements; connect to outcomes)
Data science builds the econometrics. I own:
Define the business question MMM should answer. Set requirements/inputs (channels, outcome, external factors, period).Interpret results -> actionable budget decisions for leadership. Integrate MMM with incrementality + experimentation into ONE coherent measurement framework. Drive the budget-allocation decision (with Finance/marketing).Validate/govern credibility; reconcile with experiments where possible.
7. Honest framing (defensible)
"MMM is a top-of-funnel, paid-media allocation tool; I understand it as feeding a constrained budget-optimization, which aligns with my OR background. My deepest hands-on strength isincrementality and experimentation, the modern complement to MMM. When data science models MMM,I own the business framing, interpretation, integration, and the investment decision.I'd ramp on the specific econometrics or partner with specialists."
8. Method-selection one-liner (shows senior judgment)
Aggregate paid-media allocation / diminishing returns -> MMMCausal "is it net-new / would they have anyway" -> incrementality / holdoutsTesting what works (message/offer/audience) -> experimentation (A/B, champion/challenger)Touch-level path to conversion -> attribution (incl. MTA)Forecasting churn/demand -> predictive / time-series models"Match the method to the question."


