Customer Data Pipeline – Databricks Project

This project demonstrates a full data pipeline in Databricks, transforming raw customer JSON data into curated and aggregated datasets.
Project Overview

    Bronze table: Raw JSON data (customers_lab_bronze)

    Silver table: Cleaned and enriched data with sign_up_date, email_domain, and full state_name (customer_lab_silver)

    Gold materialized view: Aggregated customer counts per state (customers_per_state_gold), refreshed daily

Key Features

    Data ingestion, cleaning, and transformation

    Delta tables and materialized views

    SQL functions: from_unixtime, date_format, substring_index

    Validation of curated data against solution tables

Usage

    Clone the repo to Databricks

    Run notebooks in order: Bronze → Silver → Gold

    Verify outputs and check aggregated results

Technology Stack

    Platform: Databricks

    Languages: SQL, PySpark

    Storage: Delta Lake
