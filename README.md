# World_Bank_Project_Data

In the context of working with nested JSON files, this project is aimed at cleaning, analyzing and visualizing data on projects by the World Bank.

Techniques used in this project include:
- writing custom functions for applying across a pandas series to mark empty strings as 'NaN' values for removal
- normalization of nested JSON data into useful DataFrames 
- merging separate DataFrames for a more useful table for answering questions (i.e., top 10 countries for World Bank projects and top 10 types of World Bank projects)
- writing a custom function to correct missing values in nested lists within a DataFrame
- visualizing the aforementioned figures with bar plots
