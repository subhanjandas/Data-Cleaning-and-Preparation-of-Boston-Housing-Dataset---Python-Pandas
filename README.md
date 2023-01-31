# Data Cleaning and Preparation Guide - Python Pandas

## Introduction 
This project focuses on the analysis of the Boston Housing Dataset using Python's Pandas library. The Excel file containing the data is first imported into a Pandas Data Frame. In order to handle missing and incorrect data, two custom functions are created to highlight these values with a yellow background. The first function float_check_background returns a yellow background to cells that do not contain any numbers, while the second function check_nan_background returns a yellow background to cells with null or NaN values. These functions are applied to all columns except the PTRATIO column.

Next, the project focuses on identifying outliers in the PTRATIO column using another custom function. This function highlights cells in the column with values below 10 or above 25 in yellow. Through this analysis, three different types of outliers were identified, including typing non-numeric values, shift in decimal place during data entry errors, and genuine outliers.

The final step involves cleaning the data for further analysis. The genuine outliers were removed from the dataset and the index was reset. The decimal typing error was corrected and the remaining outliers were imputed with the median of the columns. The missing data was finally substituted with NaN for further analysis. The objective of this project is to clean and prepare the data for better insights and decision-making. The results of this project will provide valuable insights into the Boston Housing Dataset and support the product strategy by providing accurate and reliable data.

## Tools Used
- Python
- 
