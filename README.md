# HR Analytics Case Study in Power BI

## Case Study Overview
The core goal of this analysis is to build a comprehensive report using fictitious datasets. The primary objective is to enable the ficticious HR team to monitor key metrics related to employees. Additionally, we aim to uncover the factors that impact employee attrition, which serves as a secondary goal.

## Dataset Overview
The dataset çcomprises both a fact table and multiple dimension tables. Here's a brief overview:

### Fact table
- Performance Ratings: Contains information on employees' yearly reviews, helping Atlas Labs manage employee performance. It serves as the central point of our snowflake schema, featuring 11 columns and multiple rows per employee.

### Dimension tables
We will work with the following dimension tables to provide contextual information:
- Employee: Provides details about employees (e.g., name, department, etc.).
- EducationLevel: Contains information about employees' education levels.
- RatingLevel: Stores rating levels for performance evaluations.
- SatisfiedLevel: Includes satisfaction levels of employees.

## Snowflake Schema
Our final data model will follow a snowflake schema, with most dimension tables directly connected to the fact table. This schema optimizes data relationships and improves analysis capabilities.

