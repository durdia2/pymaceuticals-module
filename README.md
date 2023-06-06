# pymaceuticals-module
    1. Upload and read the csv data using pandas Display the number of unique mice IDs in the data, and then check for any mouse ID with duplicate time points. Display the data associated with that mouse ID, and then create a new DataFrame where this data is removed. Use this cleaned DataFrame for the remaining steps.
    2. Display the updated number of unique mice IDs.
    3. Create a DataFrame of summary statistics
        -should include the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume
    4. Generate two bar charts. Both charts should be identical and show the total total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.
    5. Generate two pie charts. Both charts should be identical and show the distribution of female versus male mice in the study.
    6. Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens.
    7. Create a Line Plot and a Scatter Plot
        -single mouse that was treated with Capomulin, and generate a line plot of tumor volume versus time point for that mouse.
        -Generate a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.
    8.Calculate Correlation and Regression
        -Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.
