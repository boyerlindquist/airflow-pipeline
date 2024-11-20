# ETL webserver log to PostgreSQL

This repository demonstrates an **ETL (Extract, Transform, Load)** pipeline using **Apache Airflow**. The pipeline processes web server log data, extracts relevant information, transforms the data, and loads it into a **PostgreSQL database**. This project aims to showcase how to orchestrate and automate data workflows using Airflow.

## Project Overview

- **Extract**: Downloads the web server access log from a remote URL.
- **Transform**: Processes the log data by extracting relevant fields and converting the text to uppercase while replacing delimiters with commas.
- **Load**: Loads the transformed data into a PostgreSQL database for further analysis.

## File Structure


## Requirements

- **Apache Airflow** 2.x
- **PostgreSQL**
- **Python** 3.x
- **Python libraries**:
  - `requests`
  - `psycopg2`
  - `python-dotenv`
  - `airflow`
