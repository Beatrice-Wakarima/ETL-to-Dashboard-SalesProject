# DataTrain Pipeline

An end-to-end data analytics system built to demonstrate a full production-style workflow — from **data ingestion** to **interactive visualization**.

## Project Highlights

- **Fully automated ETL pipeline** using Apache Airflow  
- **Data version control** with DVC for reproducibility  
- **PostgreSQL database** for structured data storage  
- **Streamlit dashboard** for real-time visualization and insights  
- **Automated testing** and **CI/CD** via GitHub Actions  
- **Docker Compose** setup for seamless local deployment  
- **End-to-end reproducibility** — one command to spin up the entire system  

## Architecture

- **Version Control:** Git + DVC  
- **Orchestration:** Apache Airflow  
- **Database:** PostgreSQL  
- **Dashboard:** Streamlit  
- **Containerization:** Docker Compose  
- **Automation:** GitHub Actions CI/CD  

## Workflow

1. **Data Ingestion & Versioning** — DVC + Airflow  
2. **Data Transformation & Loading** — Pandas + PostgreSQL  
3. **Dashboard Visualization** — Streamlit + Plotly  
4. **Testing & Automation** — pytest + GitHub Actions  

## Setup

```bash
git clone https://github.com/<your-username>/data-train-pipeline.git
cd data-train-pipeline
cp .env.example .env
docker-compose up --build
```
## Access Points

Once all containers are running:

| Service | URL | Description |
|----------|-----|-------------|
| **Airflow UI** | [http://localhost:8080](http://localhost:8080) | Workflow orchestration |
| **Streamlit Dashboard** | [http://localhost:8501](http://localhost:8501) | Interactive analytics dashboard |
| **PostgreSQL Database** | `localhost:5432` | Stores cleaned and transformed data 

## License
MIT License © 2025 **Beatrice W. Wanjiru**

