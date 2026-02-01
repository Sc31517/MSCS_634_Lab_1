# MSCS_634_Lab_1
# README – Data Preprocessing and Analysis Lab

## Purpose of the Lab
The purpose of this lab was to understand and apply key data preprocessing techniques using Python and Pandas. In this lab, I worked with a Superstore sales dataset to practice data collection, data cleaning, handling missing values, outlier detection, data reduction, scaling, and discretization. The goal was to prepare raw data into a clean and structured format suitable for analysis and visualization.

## Key Insights from Visualizations and Statistical Measures
From the exploratory analysis and preprocessing steps, I observed that sales and profit values vary significantly across different product categories and regions. Some products generated high sales but resulted in negative profit due to heavy discounts. Outlier detection using the IQR method helped identify unusually high sales values that could distort analysis. Scaling the data allowed numerical features to be compared more effectively, and discretizing sales into categories made it easier to interpret sales performance levels.

## Challenges Faced and Decisions Made
One of the main challenges I faced was handling file encoding issues while loading the dataset, which required specifying the correct encoding format. Another challenge was that the dataset contained very few or no missing values, so I demonstrated missing value handling techniques for learning purposes. I also made decisions to remove outliers using the IQR method and reduce data dimensionality by dropping less relevant identifier columns to improve efficiency and clarity of analysis.

This lab helped me gain hands-on experience in preparing real-world data for further analysis and modeling.
