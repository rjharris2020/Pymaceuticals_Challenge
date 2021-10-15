# Pymaceuticals

## What does this challenge entail and what am I looking to accomplish?

In a hypothetical senario, I am a senior data analyst at a company called Pymaceuticals, I've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC (a common skin cancer) tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. I have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

### Here are the following tasks I completed:
1. Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID. Use the cleaned data for the remaining steps.
2. Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
3. Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.
4. Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.
5. Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
6. Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
7. Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
8. Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.
9. Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
10. Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.
