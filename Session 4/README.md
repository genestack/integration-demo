# Session 4 — Single-Cell Search Services

**PoC QIAGEN 2025**

This repository contains materials for Session 4 of the QIAGEN PoC training series, focusing on single-cell RNA-seq data retrieval and analysis using ODM Search Services.

## Session Overview

This session demonstrates how the third pillar of ODM, Search Services, enables flexible, programmatic access to single-cell data, extending the bulk multi-omics workflows introduced in earlier sessions.

Participants will work with ODM APIs and SDKs through Jupyter notebooks to retrieve, subset, and analyse single-cell RNA-seq datasets.

## Important: Instance Access

⚠️ **This session uses a different Genestack instance than previous sessions.**

- **Instance URL:** 👉 https://q001-demo.trial.genestack.com

### Why?

- Previous sessions used ODM version 1.61
- Single-cell Search Services require ODM version 1.62
- Version 1.62 is not yet publicly released

This instance is configured with the required version for single-cell APIs.

## SDK Installation

To run the notebooks in this repository, install the required ODM SDK version:
```bash
python -m pip install \
  --index-url https://test.pypi.org/simple/ \
  --extra-index-url https://pypi.org/simple \
  odm-sdk==1.0.0-2610
```

This version enables access to single-cell (SC) Search Services endpoints.

## Learning Objectives

By completing this session, participants will:

- Understand how single-cell RNA-seq data is represented in ODM
- Use Search Services APIs to retrieve cell-level expression data
- Query across:
  - cells
  - clusters
  - cell metadata layers
- Programmatically subset single-cell datasets
- Compare bulk and single-cell data using shared biological definitions
- Work with interactive notebooks for exploratory and analytical workflows

## Key Concept

ODM enables bulk and single-cell data to be queried using the same biological model — differing only in resolution, not structure or logic.

## Contents

- Jupyter notebook(s) demonstrating:
  - single-cell data retrieval
  - search-based subsetting
  - cell-level analysis workflows
- Example code using ODM APIs and SDKs
