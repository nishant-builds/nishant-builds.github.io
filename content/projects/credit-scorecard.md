---
title: "Building a behavioral credit scorecard from first principles"
date: 2026-05-15
tags: ["credit-risk", "analytics", "project"]
cover:
  image: "/images/cover.svg"
---

## Context

At EXL Services, I was tasked with redesigning the credit scoring model for a mid-size NBFC's personal loan book. The existing scorecard was five years old, built on bureau data alone, and had a Gini coefficient that had degraded significantly since launch.

The brief: build something better, explain it to a non-technical credit committee, and operationalize it within the existing LOS.

## What I built

A two-stage scorecard:

**Stage 1 — Bureau + demographic score**
Traditional logistic regression on bureau tradeline data, DPD history, enquiry velocity, and demographic proxies. Nothing novel here — but cleaned up, re-weighted for the current portfolio, and validated on a fresh holdout sample.

**Stage 2 — Behavioral overlay**
For existing customers (those with 3+ months of repayment history), a second scorecard built on internal behavioral signals: repayment timing patterns, partial payment frequency, inbound contact behavior, and channel of repayment.

The behavioral overlay moved Gini from ~38 to ~51 for the existing-customer segment — a material improvement that justified the operational cost of the two-stage approach.

## What I learned

1. **Data quality is 80% of the work.** The behavioral signals existed in the LOS but were inconsistently captured. We spent 6 weeks just cleaning and standardizing before any modelling happened.

2. **Explainability matters more than accuracy in credit.** A model that credit committee trusts and uses consistently beats a black-box that gets overridden by gut feel. I chose variables that were explainable — and the adoption was smoother for it.

3. **Monitoring is underrated.** We built a monthly PSI/CSI dashboard that flagged score drift automatically. This is what made the model last — not the initial build.

## Status

Deployed and in production. Performance review scheduled at 12-month mark.
