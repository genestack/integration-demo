# Session 3 — API Training: General & Multi-Omics Data Analysis

This notebook is the main hands-on resource for **Session 3** of the ODM Training Series.  
It demonstrates how to use the ODM API to retrieve, explore, and process **bulk RNA-seq (transcriptomics)** data in a Jupyter notebook, and prepares the ground for multi-omics integration.

> **Note:** In the current version, the notebook focuses on transcriptomics.  
> The proteomics and full multi-omics integration part will be added once the corresponding expression groups and parameters are finalised with the bioinformatics team.

---

## Goals of Session 3

**Session 3 – API Training: General & Multi-Omics Data Analysis**  

**Goal:**  
Introduce participants to programmatic data access and analysis workflows using the ODM API, focusing on bulk RNA-seq datasets and preparing for multi-omics integration.

### Learning Outcomes

By the end of this session, participants will be able to:

- Use API endpoints to retrieve and query omics data  
- Work with bulk RNA-seq expression datasets in a notebook  
- Perform basic filtering and exploration of transcriptomics data  
- Prepare gene-level expression matrices ready for multi-omics integration  
- Understand how this workflow can extend to mutation or other omics data

---

## What This Notebook Covers

This notebook (Session 3) is organised around transcriptomics and general API-driven analysis:

### 1. Data Model Refresher (Transcriptomics Focus)
- Recap of relevant ODM entities for bulk RNA-seq
- How expression data is exposed through the API

### 2. Authentication & API Usage
- Connecting to the ODM instance using the Python SDK
- Using tokens and configuration safely in a notebook

### 3. Querying and Retrieving Expression Data
- Choosing appropriate endpoints for bulk RNA-seq
- Building and submitting queries for expression features
- Retrieving expression data in a tabular (matrix-like) format

### 4. Working with Bulk RNA-seq Data
- Loading response data into `pandas` DataFrames
- Inspecting samples, features, and basic QC
- Mapping identifiers to gene symbols where applicable
- Preparing a gene-level expression matrix

### 5. Preparing for Multi-Omics Integration
- Producing cleaned, analysis-ready transcriptomics data
- Structuring outputs in a way that can be combined later with proteomics or mutation data


## Setup

To run this notebook, you need:

- A working Python environment (recommended: virtual environment)
- Access to an ODM instance and a valid API token
- The ODM SDK and a set of scientific Python packages

If you already followed the setup for the SDK training (Session 2), you mainly need to ensure the notebook-specific packages are installed.

At minimum, install:

```bash
pip install odm-sdk numpy pandas matplotlib seaborn scipy ipywidgets ipykernel requests
