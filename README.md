# 🕵️‍♂️ Indian Crime Analysis (2001–2013)
This repository contains a data analysis project focused on crimes in India from 2001 to 2013. The project involves data preprocessing, exploratory data analysis (EDA), visualization through Power BI, SQL-based data insights, and insight generation to support policy-making and public safety awareness.

# 📚 Table of Contents
Introduction

Project Structure

Technologies Used

Dataset Information

Installation

Usage

SQL Insights

Results

Contributing

License

# 🔍 Introduction
The Indian Crime Analysis project aims to provide deep insights into the crime trends across various Indian states and union territories over a span of 13 years (2001–2013). The project helps understand how different crime categories evolved, identify high-crime regions, and examine socio-political patterns related to law and order.

# 📁 Project Structure
bash
Copy
Edit
Indian-Crime-Analysis/
├── data/                     # Contains the raw CSV dataset
├── dashboard/                # Power BI (.pbix) file for interactive visuals
├── notebooks/                # (Optional) Python notebooks for data preprocessing/EDA
├── sql_queries/              # SQL scripts for querying crime data
├── images/                   # Screenshots of visualizations
├── README.md                 # Project documentation
└── crime_analysis_dashboard.pbix  # Power BI dashboard
🛠️ Technologies Used
Python: Pandas, NumPy, Matplotlib, Seaborn

Power BI: Data visualization

SQL: Querying and data exploration

Database: PostgreSQL / MySQL / SQLite (any relational DB)

# 📊 Dataset Information
File: Crimes_in_india_2001-2013(in)(in).csv

Fields:
STATE/UT
CRIME HEAD
YEAR
VALUE

# ⚙️ Installation
If you're using Power BI only, skip to the Usage section.

bash
Copy
Edit
git clone https://github.com/your-username/Indian-Crime-Analysis.git
cd Indian-Crime-Analysis
Set up a virtual environment:

bash
Copy
Edit
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Load the dataset into SQLite/PostgreSQL using a script or DB tool.

# ▶️ Usage
🔵 Power BI
Open the .pbix file.

Use filters for year, state, and crime type to analyze trends.

🐍 Python
Use notebooks for preprocessing or advanced analytics.

🧮 SQL
Use the sql_queries/ folder to execute SQL queries like those below.

📌 SQL Insights
Assuming the dataset is loaded into a table named crime_data with columns:


# 📈 Results
Top States: Uttar Pradesh, Maharashtra, Madhya Pradesh

High Increase: Cybercrimes and crimes against women

Tools Used: Power BI and SQL for deriving actionable insights
