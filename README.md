# rocket-launch-pipeline-airflow-rocket-tracker
Airflow DAG to fetch upcoming rocket launch data and extract rocket images,Collects rocket launch data from Launch Library API and extracts images automatically
# 🚀 Rocket Launch Tracker

A data engineering project that collects and processes rocket launch information from multiple online sources using **Apache Airflow**. This project demonstrates ETL (Extract, Transform, Load) pipelines, API integrations, and data storage using Python.

---

## 🌟 Features

- Automatically fetch rocket launch data from public APIs.
- Process and clean the data for analysis.
- Schedule and manage workflows using **Airflow DAGs**.
- Handle exceptions and API errors gracefully.
- Store processed data locally (or in a database if extended).

---

## 🎯 Problem Statement

Rocket enthusiasts and space agencies need timely information about upcoming and past rocket launches. This project automates the collection, processing, and storage of rocket launch data, making it ready for analysis and visualization.

---

## 🛠 Tech Stack

- **Python** – scripting and data processing
- **Apache Airflow** – workflow orchestration
- **Requests** – for interacting with APIs
- **BashOperator & PythonOperator** – for Airflow task execution
- **JSON / CSV** – storing API responses and processed data

---

## 📁 Project Structure

