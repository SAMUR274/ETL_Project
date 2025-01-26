```markdown
# ETL Data Pipeline Project - Advanced CS Implementation

## Overview
Academic project exploring ETL (Extract, Transform, Load) pipelines using Apache Airflow and containerization. Built to demonstrate production-grade data engineering principles.

## Project Structure
```
project/
├── dags/                   # DAG Python files
│   └── example_astronauts  # Space station crew ETL pipeline  
├── Dockerfile             # Astro Runtime image config
├── include/              # Additional resources
├── packages.txt          # OS dependencies
├── requirements.txt      # Python dependencies  
├── plugins/             # Custom Airflow plugins
└── airflow_settings.yaml # Local environment config
```

## Core Components
- PostgreSQL: Metadata Database (5432)
- Airflow Webserver: UI/API Interface (8080)
- Airflow Scheduler: Task Orchestration
- Airflow Triggerer: Async Task Execution

## Local Development
```bash
# Start services
astro dev start

# Verify containers
docker ps

# Access Airflow UI
URL: http://localhost:8080
Login: admin/admin

# Access PostgreSQL
localhost:5432/postgres
```

## Deployment
For production deployment instructions, see [Astronomer Docs](https://www.astronomer.io/docs/astro/deploy-code/)

## Support
For issues or feature requests, contact Astronomer support team.
```
