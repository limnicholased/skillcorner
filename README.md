# skillcorner-etl

Local, zero-cost ETL & analytics for open football tracking data.
- Transforms in SQL (dbt)
- Notebooks for EDA, validation, and viz
- Shared output: player-level CSV

## Quickstart (local)
1) Create venv, install deps
2) Put raw files under data/raw/
3) set DBT_PROFILES_DIR=.\dbt (PowerShell: $env:DBT_PROFILES_DIR = (Join-Path (Get-Location) "dbt"))
4) dbt build
5) Export CSV (see Makefile or notebooks)

## S3  Glue  Athena mapping
See README appendix for DDL and IaC sketch (coming).

