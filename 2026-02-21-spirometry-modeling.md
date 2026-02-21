---
title: "Longitudinal spirometry change: choosing a modeling strategy"
date: 2026-02-21
tags: [longitudinal, spirometry, mixed models, GEE]
---

In longitudinal spirometry studies, model choice is not only a technical decision. It affects interpretation and can
change study efficiency when outcomes are used for trial planning.

## A practical starting point
Start with exploratory trajectory plots and missingness summaries. Then fit a linear mixed model with random intercepts
and slopes. Compare with GEE when robustness to misspecification is a priority.

## What I compare across models
I look at stability of covariate effects, sensitivity to visit spacing, and how conclusions change under reasonable
alternatives.
