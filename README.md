<div id="header" align="center">
  <h1>
   Salary Analysis of Data & Software Professionals
</div>

## Overview
This project aims to analyze the salaries of data and software professionals across different countries and job titles using data collected from Glassdoor. The analysis focuses on identifying which countries offer the highest salaries for various data-related roles such as Data Scientist, Data Engineer, Data Analyst, Machine Learning Engineer, Business Analyst, and Software Engineer.

<div id="header" align="center">
   <h1>
  <img src="https://github.com/ayomibamm/MySQL-Professionals-Analysis/assets/125594462/03703df1-1a5f-4d41-8098-ce815572cbe2" width="450px"/>
</h1>
</div>

## Table of Contents
- [Database Schema](#database-schema)
- [Stored Procedures and Functions](#stored-procedures-and-functions)
- [Views](#views)
- [Queries](#queries)
- [Triggers](#triggers)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)

## Database Schema
The database schema consists of five main tables:
- `participant_info`: Contains information about participants, including their job title, salary, company, and country.
- `company_info`: Stores details about companies, including company name, industry type, and size.
- `country_info`: Contains data about countries, including country code, country name, and currency code.
- `currency_info`: Stores information about currencies, including currency code, name, and conversion rate to GBP.
- `job_info`: Stores information about job titles and their corresponding job levels.

## Stored Procedures and Functions
- `first_ten_rows`: Returns the first ten rows of any specified table.
- `total_rows`: Calculates the total number of rows in a specified table.
- `convert_to_gbp`: Function to convert salaries from various currencies to GBP.

## Views
- `combined_info`: Combines participant, company, country, currency, and job information into a single view.
- `most_company`: Selects companies present in more than one country and converts salaries to GBP.

## Queries
- Analyzes salaries across different countries and job titles.
- Identifies companies present in more than one country.
- Reviews the countries and job titles with the highest salary.

## Triggers
- `calculate_gbp_salary`: Trigger to automatically update salaries to GBP whenever a salary is updated in the `participant_salaries` table (specifically created to test the SQL trigger).

## Setup Instructions
1. Clone this repository to your local machine.
2. Ensure you have a MySQL database server set up.
3. Run the SQL script to create the necessary database, tables, procedures, functions, views, and triggers.
4. Populate the tables with your data.
5. Adjust any configuration parameters in the script to match your environment if necessary.

**Note:** If you require the data used in this project, please reach out to me via my LinkedIn [www.linkedin.com/in/ayomide-bammeke] profile, and I will provide the CSV files.

## Usage
- Execute the provided SQL queries to analyze salary data across different dimensions.
- Modify the queries or create new ones to suit your specific analysis requirements.

## Contributing
Contributions to improve this project are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.
