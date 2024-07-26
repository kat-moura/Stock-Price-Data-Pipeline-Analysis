# Stock-Price-Data-Pipeline-Analysis
A data pipeline project that fetches, processes, stores, and analyzes stock price data using Apache Beam, MySQL, Airflow, and Python.

## Project Overview
This project is part of a group effort to create a data pipeline that fetches stock price data from financial APIs, processes it using Apache Beam, stores it in a MySQL database, and performs basic analysis and visualization using Python in Google Colab. The project leverages Apache Airflow for scheduling and automation of tasks.

## Technologies Used
- **Python:** For data fetching, analysis, and visualization.
- **Apache Beam:** For data processing and transformation.
- **MySQL:** For data storage.
- **Apache Airflow:** For scheduling and automating the data pipeline.
- **Google Colab:** For data analysis and visualization.

## Project Structure
- **data_ingestion:** Scripts for fetching data from financial APIs.
- **data_processing:** Apache Beam pipelines for data transformation.
- **database:** SQL scripts for creating and managing MySQL database tables.
- **airflow_dags:** Apache Airflow DAGs for scheduling pipeline tasks.
- **data_analysis:** Jupyter notebooks for analyzing and visualizing data in Google Colab.

## Installation and Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/stock-price-data-pipeline.git
   cd stock-price-data-pipeline

                                                                           _________________________________________________________
## Disclaimers
1. **Google Colab Connection to Local SQL Database:**
   - This project currently does not automate the connection between Google Colab and a local SQL database. However, it can be automated using tools like ngrok or SSH tunneling to securely expose your local database to the internet for access from Google Colab.

2. **Apache Airflow Integration:**
   - The Apache Airflow DAGs included in this project outline the tasks required for the data pipeline, but they are not fully integrated and automated within the project. Due to time constraints, we did not implement a fully automated workflow using Airflow. Future improvements could include more in-depth utilization of Airflow for task scheduling and automation.
                                                                          _________________________________________________________

## Acknowledgments

Feel free to adjust the content to fit your specific project details and team preferences.
