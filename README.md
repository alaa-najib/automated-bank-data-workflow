# automated-bank-data-workflow
💼 Automated Data Workflow for Swedish Bank Transactions

A collaborative student project simulating a real-world banking data system. This system handles ~1 million daily transactions, implements automated workflows for data validation, and ensures high data quality through structured pipelines and error handling mechanisms.

📚 Project Overview

Case Study: A Swedish bank receives large volumes of transaction data via CSV files. These include domestic and international transfers, with potential fraud or data errors.

Our goal is to build an automated workflow to:

Ingest and validate CSV transaction data

Clean and store the data into a PostgreSQL database

Handle transactions with rollback support

Automate the full workflow pipeline

Track and report data quality issues

🛠 Tech Stack

Python

PostgreSQL

Jupyter Notebooks

Git / GitHub

Trello (SCRUM)

Workflow Tool (e.g., Airflow / Prefect / Cron)

Alembic / Flask-Migrate (for DB migrations)

pytest (for testing)

🚀 Getting Started

1. Clone the repo

git clone <https://github.com/YOUR_TEAM/automated-bank-data-workflow.git>
cd automated-bank-data-workflow
