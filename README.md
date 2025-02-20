![national-cancer-institute-to8o0bqOA6Q-unsplash](https://github.com/user-attachments/assets/1e4096c6-700e-4f34-b2dd-dff449f47a30)


Photo by <a href="https://unsplash.com/@nci?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">National Cancer Institute</a> on <a href="https://unsplash.com/photos/gray-laboratory-machine-to8o0bqOA6Q?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
  


# Matplotlib-challenge
In this assignment, you’ll apply what you've learned about Matplotlib to a real-world situation and dataset.

Background

You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

Instructions

This assignment is broken down into the following tasks:

Prepare the Data

Run the provided package dependency and data imports, and then merge the mouse_metadata and study_results DataFrames into a single DataFrame.

Display the number of unique mice IDs in the data, and then check for any mouse ID with duplicate time points. Display the data associated with that mouse ID, and then create a new DataFrame where this data is removed. Use this cleaned DataFrame for the remaining steps.

Display the updated number of unique mice IDs.

<img width="410" alt="image" src="https://github.com/user-attachments/assets/1874919e-4930-4763-8d97-7db624162d12">


Generate Summary Statistics

Create a DataFrame of summary statistics. Remember, there is more than one method to produce the results you're after, so the method you use is less important than the result.

Your summary statistics should include:

A row for each drug regimen. These regimen names should be contained in the index column.

A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/726a6fcf-9963-4b0b-b32a-7647482c88ef">


Create Bar Charts and Pie Charts

Generate two bar charts. Both charts should be identical and show the total total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.

Create the first bar chart with the Pandas DataFrame.plot() method.

Create the second bar chart with Matplotlib's pyplot methods.

<img width="339" alt="image" src="https://github.com/user-attachments/assets/48ef84e3-0c11-4a6f-92b8-1b67c1a7d348">

Generate two pie charts. Both charts should be identical and show the distribution of unique female versus male mice in the study.

Create the first pie chart with the Pandas DataFrame.plot() method.

Create the second pie chart with Matplotlib's pyplot methods.

<img width="256" alt="image" src="https://github.com/user-attachments/assets/b5339503-373b-44f6-bfdd-076d333c8f47">

Calculate Quartiles, Find Outliers, and Create a Box Plot

Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens. Use the following substeps:

Create a grouped DataFrame that shows the last (greatest) time point for each mouse. Merge this grouped DataFrame with the original cleaned DataFrame.

Create a list that holds the treatment names as well as a second, empty list to hold the tumor volume data.

Loop through each drug in the treatment list, locating the rows in the merged DataFrame that correspond to each treatment. Append the resulting final tumor volumes for each drug to the empty list.

Determine outliers by using the upper and lower bounds, and then print the results.

<img width="386" alt="image" src="https://github.com/user-attachments/assets/a2496b31-5237-4e25-ac5c-1e95240965c9">

Using Matplotlib, generate a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group. Highlight any potential outliers in the plot by changing their color and style.

<img width="366" alt="image" src="https://github.com/user-attachments/assets/caf32c7b-fc55-481d-ac32-b3e87a5573c4">

Create a Line Plot and a Scatter Plot

Select a single mouse that was treated with Capomulin, and generate a line plot of tumor volume versus time point for that mouse.

<img width="356" alt="image" src="https://github.com/user-attachments/assets/25d9efc7-d02e-4418-ac98-c3897b89363d">

Generate a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.

<img width="356" alt="image" src="https://github.com/user-attachments/assets/01108375-1e9d-494b-91f5-e66a38963395">

Calculate Correlation and Regression

Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.

Plot the linear regression model on top of the previous scatter plot.

<img width="383" alt="image" src="https://github.com/user-attachments/assets/7646b68f-5dee-4235-aa2b-e0754826fc8a">







## References

Some of the code examples and solutions in this repository were generated with the help of OpenAI's ChatGPT model. For more information about ChatGPT, visit [OpenAI's website](https://www.openai.com/chatgpt).











