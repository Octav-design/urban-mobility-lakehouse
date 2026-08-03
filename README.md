# Urban Mobility Lakehouse

An end-to-end data engineering project built with Azure Databricks,
Apache Spark, PySpark, Delta Lake, Unity Catalog, and Databricks Workflows.

## Business problem

The project builds an analytics platform for New York City taxi trips.
It processes raw trip records into reliable datasets that can be used
to analyze demand, revenue, trip duration, popular routes, and data quality.

## Architecture

NYC Taxi Data -> Bronze -> Silver -> Gold -> Databricks SQL Dashboard

## Project goals

- Build an incremental and idempotent data pipeline
- Implement the Medallion Architecture
- Apply data-quality rules and quarantine invalid records
- Orchestrate the pipeline with Databricks Workflows
- Create analytics-ready Delta tables
- Monitor pipeline executions and resource usage
- Document technical decisions and trade-offs

## Status

Project setup in progress.