# Python Cleaning Renewables Energy African Countries

# Introduction
This repository encompasses the code and documentation for the data cleaning process of the Renewables-Energy-African-Countries dataset. The project's objective is to refine and optimize the dataset, which contains information about renewable energy in African countries.

# Dataset Source and Overview
The Renewables Energy African Countries dataset utilized in this project was sourced from a data cleaning challenge on the US Energy Information Administration. It includes data on renewable energy production across African countries, categorized by energy source, country, and year. The dataset features three primary columns: 'Country,' 'Energy Source,' and 'Year,' with associated values representing renewable energy production (in billion kWh) for each combination. This dataset facilitates the analysis of renewable energy adoption trends in Africa, offering insights into country-specific and temporal patterns, as well as the distribution of renewable energy sources across the continent. The original dataset comprises 1290k records of renewable energy data.

# Issues Found in the Data:
During the initial exploration and analysis of the Renewables-Energy-African-Countries dataset, several issues were identified, including:

- Raw dataset - Extraneous data not required.
- Duplicate values - Removal of duplicate values in certain columns to maintain data integrity.
- Missing values - Addressing missing values in all columns through careful handling and computation.
- Inconsistent formatting - Standardization of data formatting across various columns for consistency.
- Removal of 30 columns to ensure dataset consistency for analysis.

# Tools Used:
The data cleaning project employed the following tools and libraries:

- Excel for dataset reorganization (including additional columns and renaming).
- Python for data cleaning tasks.
- Pandas for data manipulation, cleaning, and handling missing values.
- NumPy for mathematical operations and array handling during the cleaning process.
- Jupyter Notebooks for an interactive environment for code development, exploration, and documentation.

# Data Cleaning Process
The data cleaning process encompassed the following steps:

- Data Understanding - A thorough examination of the dataset to understand its structure, columns, and meanings. A data dictionary was created with online sources to provide insights into column representations.
- Data Exploration - Exploratory Data Analysis was performed to gain insights, identify patterns, and uncover anomalies.
- Handling missing values - The EDA revealed valid reasons for missing values, with the year columns having the most.
- Standardizing formatting - Inconsistent formatting issues, such as variations in units, were resolved through data transformations and normalization techniques.
- Validation and quality checks - The cleaned dataset underwent rigorous validation to ensure data quality, accuracy, and integrity.

# Documentation
For detailed information about the data cleaning process, please refer to the Jupyter notebooks available in the repository. These notebooks contain step-by-step explanations, code samples, and documentation demonstrating each stage of the data cleaning process.




