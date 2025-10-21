Healthcare Data Engineering & Analytics Pipeline

A cloud-native end-to-end data pipeline designed for healthcare analytics, integrating Python, PySpark, Airflow, AWS, and Snowflake.
Automates ingestion, transformation, and modeling of clinical and claims data, enabling real-time insights and predictive analytics.

TECH STACK

Languages: Python, SQL, PySpark

Cloud: AWS (S3, Redshift, EMR, Kinesis, Athena, DynamoDB)

Data Modeling: DBT, Snowflake

Orchestration: Apache Airflow

Analytics: Tableau, Elasticsearch

ML Integration: TensorFlow, OpenAI GPT API

FEATURES

Automated ETL/ELT pipelines improving refresh time by 40%

Optimized Spark jobs on Databricks & EMR (35% faster processing)

Real-time ingestion via AWS Kinesis & Apache NiFi

Curated DBT data marts for population health dashboards

HIPAA-compliant data governance & CloudWatch monitoring

REPOSITORY STRUCTURE

airflow_dags/       → Airflow DAGs for orchestration
spark_jobs/         → PySpark transformation scripts
scripts/            → Data ingestion & Redshift loading scripts
dbt_models/         → DBT SQL models for Snowflake
infra/terraform/    → Infrastructure-as-code configs
notebooks/          → Analytics and exploration notebooks
