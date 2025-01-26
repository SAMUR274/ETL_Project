# Advanced ETL Pipeline with Apache Airflow

[![Airflow](https://img.shields.io/badge/Airflow-2.x-green)](https://airflow.apache.org/)
[![Docker](https://img.shields.io/badge/Docker-Ready-blue)](https://www.docker.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🚀 Overview

Advanced ETL implementation showcasing distributed data processing using Apache Airflow. Features dynamic task mapping, containerization, and real-time API integration.

## 🏗️ Project Structure

```
.
├── dags/
│   └── example_astronauts/    # Space station crew ETL
├── Dockerfile                 # Runtime config
├── include/                   # Resources
├── packages.txt              # OS dependencies
├── requirements.txt          # Python packages
├── plugins/                  # Airflow plugins
└── airflow_settings.yaml     # Environment config
```

## 🔧 Core Components

- 🗄️ **PostgreSQL** (5432): Metadata storage
- 🌐 **Airflow UI** (8080): Web interface
- ⚙️ **Scheduler**: Task orchestration
- 🔄 **Triggerer**: Async execution

## 🚦 Quick Start

```bash
# Launch services
astro dev start

# Verify deployment
docker ps

# Access UI
open http://localhost:8080
credentials: admin/admin

# Database
postgresql://localhost:5432/postgres
```

## 📚 Documentation

For deployment details, visit [Astronomer Docs](https://www.astronomer.io/docs/astro/deploy-code/)

## 🤝 Support

Need help? Reach out to our support team for assistance.

---
Built with ❤️ using Astronomer
