---
title: "Risk monitoring dashboard — from spreadsheet to live view"
date: 2026-04-20
tags: ["analytics", "risk", "operations", "project"]
cover:
  image: "/images/cover.svg"
---

## The problem

The risk team was running end-of-month portfolio reviews off a 47-tab Excel file that took two days to refresh. By the time leadership saw the numbers, they were already 30 days old. Decisions were reactive, not proactive.

## What I built

A live risk monitoring dashboard that replaced the Excel file with a structured data pipeline and a simple, shareable view.

**Architecture:**
- Source: Core banking system exports → PostgreSQL (via daily ETL)
- Transformation: SQL models for the core metrics (bucket-wise DPD, vintage analysis, product-wise NPA, collection efficiency)
- Visualization: Metabase dashboards, auto-refreshed daily

**Key views built:**
1. Portfolio health summary (DPD 0/30/60/90+ trend lines)
2. Vintage curves by product and disbursement month
3. Collection efficiency by region and channel
4. Early warning indicators (Day 1 overdue rate, partial payment frequency)

## What I learned

**The hardest part was alignment, not technology.** Every team had a slightly different definition of "NPA" and "overdue." Getting finance, collections, and credit to agree on a single source of truth took longer than building the dashboard.

**Simple beats sophisticated.** I initially built complex drill-downs and cross-filters. Leadership used two views: the portfolio summary and the vintage curves. Everything else was noise. I removed it.

**Daily refresh changed behavior.** When leadership could see yesterday's collection numbers this morning, conversations shifted from "what happened last month" to "what are we doing today." That's the real product.

## Impact

Reduced reporting preparation time from 2 days to 0 (fully automated). Portfolio reviews moved from monthly to weekly. Two early-warning indicators flagged stress in a geographic cluster 6 weeks before it would have shown in the NPA numbers.

## Status

Live and in use. Maintained by the data team.
