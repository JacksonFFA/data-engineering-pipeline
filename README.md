# Data Engineering Pipeline

End-to-end **Data Engineering pipeline** demonstrating modern architecture: ingestion → processing → storage → analytics.

## Goals
- Build a resilient pipeline with **Bronze/Silver/Gold** layers
- Apply **data quality checks**
- Enable reproducible runs with **Docker**
- Orchestrate tasks with **Airflow** (later stage)

## Tech Stack
- Python
- SQL / PostgreSQL
- Pandas / PySpark (optional)
- Docker
- Airflow (roadmap)

## Architecture
**Source (API/Files) → Bronze (raw) → Silver (clean) → Gold (analytics-ready)**

## Project Structure (planned)


src/
data/
bronze/
silver/
gold/
tests/
docker/


## How to Run (soon)
🚧 In development

## Roadmap
- [ ] Ingestion from public API
- [ ] Bronze/Silver/Gold with Parquet
- [ ] Data quality validations
- [ ] Airflow DAG
- [ ] Docker compose

## Author
Jackson Oliveira
