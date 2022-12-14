# Data Pipeline with Apache Airflow and PostgreSQL

*Apache Airflow | Python | SQL | PostgreSQL | Docker*

This is a personal project I've been working on. The aim was to build a simple data pipeline, extracting data from diffetent sources (API, CSV file and a Database server), loading to a database (PostgreSQL), using Apache Airflow as a data orchestration workflow tool.

<img src="https://github.com/JKng/Pipeline-de-dados/blob/main/elt-pipeline.png" width="800" height="350">

Steps taken:
- [Docker Compose](https://github.com/JKng/Data_Pipeline_Airflow/blob/main/docker-compose.yaml) (docker-compose.yaml)
- [Create DAG](https://github.com/JKng/Data_Pipeline_Airflow/blob/main/DAGcreate_dag.py) (DAGcreate_dag.py)
- ETL Incremental Data Loading (carga incremental)
