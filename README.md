# mini-financial-data-pipeline
Mini end-to-end finance data pipeline: ingest → validate → transform → export, with logging and data quality checks.

## MVP (Python ETL)
- Ingest: load market data (yfinance or CSV)
- Validate: schema + quality checks
- Transform: create features (returns, SMA, volatility)
- Export: write clean + features datasets and a quality report
- Logging: file + console logs

## Outputs
- data/processed/clean.parquet
- data/processed/features.parquet
- data/output/quality_report.json
- logs/run.log

## Next Steps (post-MVP)
- SQL storage
- AWS S3 artifacts
- FastAPI service
- CI/tests
