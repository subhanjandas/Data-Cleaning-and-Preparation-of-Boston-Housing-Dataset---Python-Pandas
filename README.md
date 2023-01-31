# Data Cleaning and Preparation Guide - Python Pandas

## Introduction 
This project focuses on the analysis of the Boston Housing Dataset using Python's Pandas library. The Excel file containing the data is first imported into a Pandas Data Frame. In order to handle missing and incorrect data, two custom functions are created to highlight these values with a yellow background. The first function float_check_background returns a yellow background to cells that do not contain any numbers, while the second function check_nan_background returns a yellow background to cells with null or NaN values. These functions are applied to all columns except the PTRATIO column.

Next, the project focuses on identifying outliers in the PTRATIO column using another custom function. This function highlights cells in the column with values below 10 or above 25 in yellow. Through this analysis, three different types of outliers were identified, including typing non-numeric values, shift in decimal place during data entry errors, and genuine outliers.

The final step involves cleaning the data for further analysis. The genuine outliers were removed from the dataset and the index was reset. The decimal typing error was corrected and the remaining outliers were imputed with the median of the columns. The missing data was finally substituted with NaN for further analysis. The objective of this project is to clean and prepare the data for better insights and decision-making. The results of this project will provide valuable insights into the Boston Housing Dataset and support the product strategy by providing accurate and reliable data.

## Tools Used
- Python
- Pandas

## Project Screenshots
- ![image](https://user-images.githubusercontent.com/69835617/215856378-8f5b8f69-c084-4790-8492-ecd15d258356.png)
- ![image](https://user-images.githubusercontent.com/69835617/215856399-2b4929bc-349e-439a-a23a-a28540e618b4.png)
- ![image](https://user-images.githubusercontent.com/69835617/215856431-9f5d92c4-baba-49a0-950d-6b3ccbda175c.png)
- ![image](https://user-images.githubusercontent.com/69835617/215856452-75c69d27-e226-4e8d-b05d-4f700ba343c8.png)
- ![image](https://user-images.githubusercontent.com/69835617/215856470-6bd13ef8-fabb-40e7-93e8-8fe28dad638b.png)
- ![image](https://user-images.githubusercontent.com/69835617/215856492-714fb169-0a0d-4f9e-af60-d70e518f656f.png)
- ![image](https://user-images.githubusercontent.com/69835617/215856510-b17a8072-958b-4be7-9839-e902bf89e006.png)
- ![image](https://user-images.githubusercontent.com/69835617/215856523-57ef84fb-4eb2-4f6b-83bf-11e139be68b9.png)
- ![image](https://user-images.githubusercontent.com/69835617/215856554-8ec5c14e-3f07-45f0-ba5f-8fcc7a8e4d3c.png)
- ![image](https://user-images.githubusercontent.com/69835617/215856571-d1cd79c9-6d2c-44c2-a926-dfd0efa7b376.png)
