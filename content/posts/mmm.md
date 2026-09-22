---
title: MMM
date: 2026-09-12T13:22:00.000-04:00
draft: false
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

6. Method-selection one-liner 

Aggregate paid-media allocation / diminishing returns -> MMMCausal "is it net-new / would they have anyway" -> incrementality / holdoutsTesting what works (message/offer/audience) -> experimentation (A/B, champion/challenger)Touch-level path to conversion -> attribution (incl. MTA)Forecasting churn/demand -> predictive / time-series models"Match the method to the question."


