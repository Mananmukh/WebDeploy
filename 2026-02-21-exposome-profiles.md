---
title: "Exposome profiles: from features to interpretable clusters"
date: 2026-02-21
tags: [exposome, clustering, latent factors]
---

Exposome features are often correlated across domains. A useful workflow separates representation learning from
clustering.

## A common pipeline
1. Harmonize exposures and handle missingness
2. Learn low dimensional representations that capture correlation structure
3. Cluster participants into profiles
4. Associate profiles with outcomes using adjusted models and sensitivity checks
