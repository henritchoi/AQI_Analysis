# Main objectives

The project's objective is to analyse AQI around the world and find out trends and correlations.

## Implementation steps

1. Ingestion development

The ingestion from the API provided by https://aqicn.org/api/ will ingestion daily data on incremental runs to load into a local DuckDB database.
This will also be the opportunity to learn about orchestration, possibly with Dagster.

Historical data is only available through CSVs.
