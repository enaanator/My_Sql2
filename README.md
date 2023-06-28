# Human Resource Data Analytics Project

This repository contains the code and documentation for a data analytics project focused on Human Resource data for a brand. The project involves loading the data from a CSV file into a MySQL database, performing data cleaning and exploratory data analysis (EDA) using SQL, and visualizing the results using PowerBI.

## Project Overview

The objective of this project is to analyze the Human Resource data for a brand and derive valuable insights to support decision-making and improve HR strategies. The workflow involves the following steps:

1. Data Loading: The HR data, stored in a CSV file, is loaded into a MySQL database. This step ensures structured and efficient data storage for further analysis.

2. Data Cleaning: SQL queries are employed to clean the data, removing any inconsistencies, duplicates, or irrelevant information. This ensures data integrity and accuracy.

3. Exploratory Data Analysis (EDA): SQL queries are utilized to perform EDA on the HR data. This includes analyzing key metrics, identifying trends, patterns, and relationships within the data.

4. Data Visualization: The result sets obtained from SQL queries are visualized using PowerBI. This allows for interactive and visually appealing dashboards and reports to communicate the findings effectively.

## Repository Structure

The repository is organized as follows:

- `data/`: This directory contains the HR data file in CSV format.

- `sql/`: This directory contains the SQL scripts used for data loading, cleaning, and EDA.

- `powerbi/`: This directory contains the PowerBI files for visualizing the SQL query results.

- `README.md`: This file provides an overview of the project, its objectives, and instructions for running the code.

## Requirements

To run the code and replicate the project, the following dependencies are required:

- MySQL: Install and configure a MySQL database server.

- PowerBI: Install PowerBI Desktop to visualize the SQL query results.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/hr-data-analytics.git
   ```

2. Load the HR data into MySQL:

   - Create a new MySQL database.
   - Import the HR data CSV file into the database using MySQL's import feature.

3. Run the SQL scripts:

   - Execute the SQL scripts in the `sql/` directory in the following order: data loading script, data cleaning script, EDA scripts.

4. Visualize the results using PowerBI:

   - Open PowerBI Desktop.
   - Connect to the MySQL database.
   - Import the required tables/views generated from the SQL scripts.
   - Design interactive dashboards and reports to visualize the HR data.

## Conclusion

This data analytics project showcases the use of MySQL and PowerBI to analyze and visualize Human Resource data for a brand. By following the instructions provided, you can replicate the project and gain valuable insights to support HR decision-making processes.

Please feel free to reach out if you have any questions or need further assistance.

Happy analyzing!
