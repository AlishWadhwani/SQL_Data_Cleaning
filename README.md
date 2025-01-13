# SQL_Data_Cleaning
# Layoffs Analysis Project

## Overview

This project analyzes layoff data from 2022 using SQL. It consists of two main components: data cleaning and exploratory data analysis (EDA). The dataset, sourced from Kaggle, contains information about company layoffs, including company names, industries, layoff numbers, and more.

## Project Structure

The project is divided into two main SQL scripts:

1. `Layoffs_Project.sql`: Handles data cleaning and preparation.
2. `EDA.sql`: Performs exploratory data analysis on the cleaned dataset.

## Features

### Data Cleaning (`Layoffs_Project.sql`)

- **Duplicate Removal**: Identifies and eliminates duplicate entries.
- **Data Standardization**: Cleans and standardizes fields like company names, industries, and countries.
- **Date Formatting**: Converts date strings to proper DATE format.
- **Null Value Handling**: Analyzes and manages null or blank values.
- **Data Preparation**: Creates a staging table for raw data and performs necessary transformations.

### Exploratory Data Analysis (`EDA.sql`)

- **Layoff Statistics**: Analyzes maximum layoffs and percentages.
- **Company-specific Analysis**: Identifies companies with 100% layoffs and largest single layoffs.
- **Industry and Country Analysis**: Breaks down layoff data by industry and country.
- **Temporal Analysis**: Examines layoff trends over time, including yearly and monthly breakdowns.
- **Company Rankings**: Ranks companies by total layoffs and analyzes layoff patterns across years.

## Installation and Usage

1. **Clone the Repository**:
git clone https://github.com/yourusername/layoffs-analysis-project.git
cd layoffs-analysis-project
text

2. **Database Setup**:
- Ensure you have a SQL database management system installed (e.g., MySQL, PostgreSQL).
- Create a new database for this project.

3. **Run the Scripts**:
- First, execute `Layoffs_Project.sql` to clean and prepare the data.
- Then, run `EDA.sql` to perform the analysis.

## Key Insights

- The project reveals patterns in layoffs across different industries and countries.
- It provides insights into which companies had the most significant layoffs.
- Temporal analysis shows how layoff trends evolved over the year 2022.

## Data Source

The dataset used in this project is available on Kaggle: [Layoffs 2022 Dataset](https://www.kaggle.com/datasets/swaptr/layoffs-2022)

## Contributing

Contributions to improve the analysis or extend the project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is open-source and available under the MIT License.

## Contact

For any queries or feedback regarding this project, please contact:

Alish Wadhwani

Email: alishwadhwani@gmail.com