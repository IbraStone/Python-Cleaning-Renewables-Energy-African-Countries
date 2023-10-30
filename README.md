# Python Cleaning Renewables Energy African Countries

# Introduction
This repository contains the code and documentation for the data cleaning process of the Renewables-Energy-African-Countries dataset. The goal of this project is to clean and enhance the dataset which provides information about Renewables Energy African Countries.

# Dataset Source and Overview
The Renewables Energy African Countries dataset used in this project was obtained from a data cleaning challenge on US Energy Information Administration.The dataset provides information on renewable energy production across African countries, categorized by energy source, country, and year. It comprises three main features: 'Country,' 'Energy Source,' and 'Year,' with corresponding values indicating the renewable energy production (in billion kWh) for each combination. This dataset enables analysis of the evolution of renewable energy adoption in Africa, examining trends across countries and over time, and provides insights into the distribution of renewable energy sources across the continent.The original  dataset contains 3235 records of player data. 

# Issues found in the data
During the initial exploration and analysis of the Renewables-Energy-African-Countries dataset, several issues were identified including:
- Raw dataset - Unnecessary data no needed.
- Duplicate values - Some columns had duplicats values which required to remove to maintained th data integrity.
- Missing values - All columns had missing values which required careful handling and computation.
- Inconsistent formatting - This was observed across different columns making it necessary to standardize the data for consistency.
- Dropped 30 columns in order to have some consistent data for the analysis.

# Tools Used
For the data cleaning project, the following tools and libraries were used:

- Excel to reorganize the dataset (adding some columns and renamed)
- Python for data cleaning tasks.
- Pandas was instrumental in data manipulation, cleaning and handling missing values.
- NumPy was utilized for mathematical operations and array handling during the cleaning process.
- Jupyter Notebooks provided an interactive environment for code development, exploration and documentation.

# Data Cleaning Process
The data cleaning process involved the following steps:

Data Understanding - The dataset was thoroughly examined to understand the structure, columns and their meanings. The data did not have a data dictionary attached. With the help of online sources I was able to create one that helped me gain an understanding of what all the columns represented.
Data Exploration - Exploratory Data Analysis was performed to gain insights into the data, identify patterns and uncover anomalies.
Handling missing values - Through the EDA performed, I quickly realised there was a valid reason for the missing values all columns. The year columns represented were the most to have missing values.
Standardizing formatting - Inconsistent formatting issues eg the values in all columns that were stored with different units were resolved by applying transformations and  data normalization techniques.
Validation and quality checks - The cleaned dataset underwent rigorous validation to ensure the quality, accuracy and integrity of the data.

# Documentation
For detailed information about the data cleaning process, please refer to the Jupyter notebooks provided in the repository. It contains step by step explanations, code samples and documentation showing each stage of the data cleaning process. 


