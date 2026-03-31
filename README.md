# Data Cleaning Project – Hospital Quality & Social Vulnerability

## Overview
This project analyzes how data cleaning impacts integration between hospital quality data (CMS) and community-level social vulnerability (CDC SVI).

The goal is to evaluate how inconsistencies in geographic identifiers affect dataset linkage and downstream analysis.

## Datasets
- CMS Hospital General Information (2026)
- CDC Social Vulnerability Index (2022)
- U.S. Census County FIPS Reference

## Workflow
1. Data loading and profiling
2. Naive join using county + state
3. Identification of data quality issues
4. Standardization of geographic identifiers
5. Mapping to FIPS using Census reference
6. Integration with SVI dataset
7. Evaluation of join improvement

## Key Results
- Naive join match rate: ~93%
- FIPS mapping rate: ~99.9%
- Final integration join rate: ~98%

## Repository Structure
- `data/raw/` → original datasets
- `data/processed/` → cleaned and merged datasets
- data cleaning pipeline
- Progress report

## How to Run
Open `data_cleaning_pipeline.ipynb` and run all cells.

## Author
Kritika Singh
