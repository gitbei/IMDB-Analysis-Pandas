# Analyzing IMDB Dataset using Pandas

## Overview
This project focuses on analyzing the IMDB dataset using the Python library Pandas. The dataset consists of information about movies and directors, including attributes like title, genre, release year, director, budget, revenue, and more. The primary goal of this analysis is to extract meaningful insights and trends from the dataset.

## Data Preprocessing
- **Reading the Data**: The datasets for movies and directors are read into Pandas DataFrames.
- **Checking Unique Values**: A check is performed to identify the unique values of attributes in the dataset.
- **Handling Duplicates**: Any duplicate records in both tables are handled to ensure data integrity.
- **Merging Datasets**: The movies and directors datasets are merged based on common attributes to create a comprehensive dataset for analysis.

## Analysis
- **Identifying Best Movies**: Analysis is conducted to find the best-rated movies based on user ratings.
- **Productive Directors**: Directors are evaluated based on the number of movies they have directed in their active years.
- **Calculating Profit**: Profit is calculated for each movie by subtracting the budget from the revenue.
- **High Budget Movies**: Analysis is performed to identify movies with high budgets.

## Usage
1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the analysis scripts to perform various analyses on the IMDB dataset.
