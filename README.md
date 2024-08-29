# Analyzing American baby names using SQL

Hi! Welcome to my project on analyzing American baby names using SQL. In this project, I explored trends in baby names across different years using SQL queries executed through SQLAlchemy within a Jupyter Notebook. This approach allowed me to seamlessly document the process and analyze the data interactively.

## Project Overview

This project leverages SQL for data analysis on a dataset of American baby names, containing fields such as year, first name, sex, and the number of occurrences. My goal was to uncover trends, identify popular names over time, and compare naming patterns between male and female babies.

## Key Features

- **SQL Analysis**: All analysis is done using SQL queries, making it easy to understand and replicate the steps.
- **Popularity Trends**: I identified the most popular names each year and tracked how their popularity changed over time.
- **Gender-Based Comparisons**: The project compares naming trends between male and female babies, providing insights into gender-specific preferences.
- **Interactive Documentation**: By using Jupyter Notebook, I combined code, results, and explanations in one place.

## Dataset

The dataset used in this project includes the following fields:
- `year`: The year when the name was recorded.
- `first_name`: The given first name of the baby.
- `sex`: The sex of the baby (`'M'` for male, `'F'` for female).
- `num`: The count of babies given that name in that year.

## Highlights

- Analyzed a dataset of 12,650 rows containing American baby names using SQL
- Identified the most common baby names for each year and analyzed trends for specific names.
- Employed a window function to calculate the cumulative sum of occurrences for the name "Olivia."
- Utilized advanced SQL techniques, including aggregate functions, Common Table Expressions (CTEs), and subqueries for data exploration and insights.
