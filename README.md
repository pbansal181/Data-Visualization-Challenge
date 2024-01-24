# Data-Visualization-Challenge
This is a Data Visualization Challenge in Python and data includes pharmaceutical company data that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
The data includes 2 types of data - 1 is mouse data which contains data for 249 mice (Treated drug, sex, age and weight). Other data contains the study (tumor volume, timepoint and metastatic data).

This task is broken down into the following tasks:
•	Prepare the data.
•	Generate summary statistics.
•	Create bar charts and pie charts.
•	Calculate quartiles, find outliers, and create a box plot.
•	Create a line plot and a scatter plot.
•	Calculate correlation and regression
•	Submit the final analysis.

**Steps**
1.	Merge the data
The 2 datasets are merged and checked the first 5 rows of the data
2.	Your summary statistics should include:
   
•	A row for each drug regimen. These regimen names should be contained in the index column.

•	A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume
4.	Generate two bar charts. Both charts should be identical and show the total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.
•	Create the first bar chart with the Pandas DataFrame.plot() method.
•	Create the second bar chart with Matplotlib's pyplot methods.
5.	Generate two pie charts. Both charts should be identical and show the distribution of female versus male mice in the study.
•	Create the first pie chart with the Pandas DataFrame.plot() method.
•	Create the second pie chart with Matplotlib's pyplot methods.
6.	Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens. Use the following substeps:
•	Create a grouped DataFrame that shows the last (greatest) time point for each mouse. Merge this grouped DataFrame with the original cleaned DataFrame.
•	Create a list that holds the treatment names as well as a second, empty list to hold the tumor volume data.
•	Loop through each drug in the treatment list, locating the rows in the merged DataFrame that correspond to each treatment. Append the resulting final tumor volumes for each drug to the empty list.
•	Determine outliers by using the upper and lower bounds, and then print the results.
7.	Using Matplotlib, generate a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group. Highlight any potential outliers in the plot by changing their color and style.
8.	Create a Line Plot and a Scatter Plot
•	Select a single mouse that was treated with Capomulin, and generate a line plot of tumor volume versus time point for that mouse.
•	Generate a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.
9.	Calculate Correlation and Regression
•	Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.
•	Plot the linear regression model on top of the previous scatter plot.


