# Taxi Data ETL Pipeline

## 📌 Project Overview
This project builds an **ETL (Extract, Transform, Load) pipeline** for NYC taxi trip data. The pipeline automates:
- Data ingestion from public sources
- Data cleaning and transformation
- Storage in a PostgreSQL/SQLite database
- Exploratory data analysis with SQL and Python
- Deployment with Docker and Apache Airflow (optional)

## 📂 Project Structure
nyc-taxi-data-pipeline/
│── data/                   # Directory for datasets
│   ├── raw/                # Raw data files (downloaded)
│   ├── processed/          # Cleaned and transformed data
│
│── scripts/                # Python scripts for ETL process
│   ├── download_data.py    # Script to download NYC taxi data
│   ├── clean_data.py       # Script to clean and preprocess data
│   ├── load_data.py        # Script to load data into database
│
│── notebooks/              # Jupyter notebooks for analysis
│   ├── data_exploration.ipynb  # Initial data exploration
│
│── README.md               # Project documentation
│── requirements.txt        # Python dependencies
│── .gitignore              # Files and folders to ignore in Git


## 🚀 Getting Started

### 1️⃣ **Clone the Repository**
```sh
git clone https://github.com/your-username/taxi-data-pipeline.git
cd taxi-data-pipeline

### 2️⃣ **Set Up a Virtual Environment (Optional but Recommended)**
python -m venv venv
source venv/bin/activate  # On Mac/Linux
venv\Scripts\activate     # On Windows

### 3️⃣ Install Dependencies
pip install -r requirements.txt

### 4️⃣ Run the Data Pipeline
python scripts/download_data.py  # Download raw data
python scripts/clean_data.py     # Process data
python scripts/load_data.py      # Load data into the database

