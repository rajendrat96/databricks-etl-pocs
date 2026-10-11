# Databricks Auto Loader POC

## Objective
A personal hands-on project to learn CSV ingestion using Databricks Auto Loader and PySpark.

## Technologies
- Databricks Free Edition
- PySpark
- Auto Loader
- Delta Lake
- Unity Catalog Volumes

## Implementation
- Read CSV files using `cloudFiles` and `spark.readStream`.
- Configure schema tracking and checkpointing.
- Capture ingestion timestamps and source-file metadata.
- Write records to a Bronze Delta table.
- Use the `availableNow` trigger to process available files.

## Current Scope
The current version demonstrates ingestion of a single CSV file. Incremental ingestion with additional files will be tested as a future enhancement.

## Project Type
Personal learning POC, not a production deployment.
