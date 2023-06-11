# World Cup Database

This project was completed as part of the realational database certification from FreeCodeCamp. The project was completed using PostgreSQL and Bash.

This repository contains the necessary files and scripts for managing a PostgreSQL database related to World Cup data. It includes scripts for inserting data from a CSV file, running queries, and the SQL file containing the database schema and initial data.

## Contents

- `insert_data.sh`: This script allows you to insert data into the PostgreSQL database from a CSV file. Make sure to provide the appropriate database connection details and adjust the file path accordingly.
- `queries.sh`: This script runs predefined queries against the database and prints out the responses. You can modify or add additional queries as needed.
- `worldcup.sql`: This SQL file contains the database schema and initial data. You can import this file to create the necessary tables and populate them with the initial data for the World Cup database.

## Prerequisites

- PostgreSQL: Make sure you have PostgreSQL installed and running.
- Database Connection: Ensure that you have the necessary credentials and connection details to connect to the PostgreSQL database.

## Getting Started

1. Clone the repository: `git clone https://github.com/your/repository.git`
2. Import the database schema and initial data: `psql -U <username> -d <database_name> -f worldcup.sql`
3. Run the `insert_data.sh` script to insert additional data from a CSV file into the database: `./insert_data.sh`
4. Execute queries using the `queries.sh` script: `./queries.sh`
