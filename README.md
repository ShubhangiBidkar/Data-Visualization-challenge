# Data-Visualization- Pharmaceutical trail analysis

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

## Instructions

• Check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

• Use the cleaned data.

• Generate Summary Statistics which consists of mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

• Create Bar Charts and Pie Charts using Pandas DataFrame.plot() method and Matplotlib's pyplot methods which shows the total total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.

o NOTE:Charts should be identical

• Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.Calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens.

• Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

• Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

• Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

## Resources

Data Source : Mouse_metadata.csv,Study_results.csv,analysis_data.csv

Tools : Python 3.7.6, Pandas, Jupyter Notebook,Matplotlib

## Results

##### Summary Statistics

##### Number of Mice per Drug Regiem

Using both pandas and matplotlib methods

• With pandas

• With Matplotlib

##### Distribution of male vs female mice across all the treatements

Using both pandas and matplotlib methods

• With pandas

• With Matplotlib

##### Fours regimens: Capomulin, Ramicane, Infubinol, and Ceftamin

##### Mouse ID 1509's Tumor Vol. in Capomulin Treatment

##### Weight vs Average Tumor Volume (Capomulin regimen)

##### Corelation between Weight vs Average Tumor Volume (Capomulin regimen)
