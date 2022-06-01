![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Basic Data Cleaning and EDA

For this lab, we will be using the dataset in the Customer Analysis Business Case. This dataset can be found in `files_for_lab` folder.

## Context

An auto insurance company has collected some data about its customers including their _demographics_, _education_, _employment_, _policy details_, _vehicle information_ on which insurance policy is, and _claim amounts_. You will help the senior management with some business questions that will help them to better understand their customers, improve their services, and improve profitability.

**Some business Objectives for the case study could be**:

- Retain customers,
- Analyze relevant customer data,
- Develop focused customer retention programs.

Based on the analysis, take targeted actions to increase profitable customer response, retention, and growth.

### Instructions

1. Import the necessary libraries.
2. Load the we_fn_use_c_marketing_customer_value_analysis.csv into the variable customer_df
i.e. customer_df = pd.readcsv("")
3. First look at its main features (head, shape, info).
4. Rename the columns so they follow the PE8 (snake case).
5. Change effective to date column to datetime format.
6. Fix the data types of any other column/columns as you might see necessary. Note that sometimes there are some features that you might want to use as categorical but they are read as numerical by python (and vice versa). For eg. if there's a column with year values like 2020, 2021, 2022 etc. This column might be read as numerical by python but you woudl want to use that column as categorical data
7. Plot a correlation matrix, comment what do you observe.
8. Create a function to plot every discrete variable. Comment what you can see in the plots.
9. Do the same with the continuous variables (be careful, you may need to change
the plot type to one better suited for continuous data!). Comment what you can see in the plots.
Hint: you can use bar plots to plot categorical data, with each unique category in the column on the x-axis and an appropriate measure on the y-axis
10. Look for outliers in the continuous variables. (HINT: There’s a
good plot to do that!). Did you find outliers? Comment what you will do with them.
11. Check all columns for NaN values. Decide what (if anything) you
will need to do with them.
