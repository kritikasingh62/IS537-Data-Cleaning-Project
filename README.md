# Data Cleaning Project – Hospital Quality & Social Vulnerability

## Overview
This project evaluates how data cleaning affects dataset integration and downstream analysis when combining hospital quality data from CMS with county-level social vulnerability data from the CDC Social Vulnerability Index (SVI).

The project focuses on improving geographic identifier consistency and measuring how cleaning changes integration quality, dataset coverage, and analytical reliability.

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
- The relationship between hospital ratings and social vulnerability remained stable before and after cleaning

## Repository Structure
- `data/raw/` → original datasets
- `data/processed/` → cleaned and merged datasets
- data cleaning pipeline
- `report/` → plan, progress, and final reports

## Reproducibility
Run data_cleaning_pipeline.ipynb to reproduce the full profiling, cleaning, integration, and evaluation workflow.

## Author
Kritika Singh
