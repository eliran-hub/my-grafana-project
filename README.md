# 📊 Grafana & SQLite Automated Dashboard

This project provides a fully automated setup for Grafana connected to a SQLite database using Docker Compose. It's designed for quick deployment and easy visualization of local data.

## 🚀 Overview
The goal of this project is to demonstrate Infrastructure as Code (IaC) principles by provisioning a monitoring tool (Grafana) with pre-configured data sources and automated plugin installation.

## 🛠️ Tech Stack
* **Docker & Docker Compose**: Containerization and orchestration.
* **Grafana**: Data visualization and analytics.
* **SQLite**: Lightweight relational database.

## 📁 Project Structure
```text
├── docker-compose.yml       # Docker services configuration
├── provisioning/            # Automatic setup for Grafana
│   └── datasources/
│       └── datasource.yml   # Pre-defined SQLite connection
├── data/                    # Folder for your SQLite .db files
└── README.md
