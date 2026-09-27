1.	Highlighted the “? “cells in the hospitalisation details using conditional formatting function .
2.	Find out the ? and replaced it with sep in the month column find out the rounded average of year value I got it as =1983 i replaced  ? in year with 1983 
3.	Using Countif function I get the count of “NO”,”YES” and “?" form that I find out “No” is most frequently occurring values for finding which all vales lies in the smoker data>>filter there I find out “NO”,”YES” and “”?.in the hospital tier 2 is the mode so I replaced the ? with tier 2 same for city tier.
Data Transformation:
Using text to columns ,Splited the ‘names’ column in the “Customer Names” Table into 3 meaningful columns: ‘Title’, ‘First Name’, and ‘Last Name’.
4.	Converted the "NumberOfMajorSurgeries" column in the “Medical Examinations” Table to numerical data by replacing non-numeric characters with meaningful numerical values.here "NumberOfMajorSurgeries” means 0 surgery so using find and replace replaced with 0.
5.	Checked for inconsistencies in the 'Heart Issues' and 'smoker' columns like ? and smoker replaced it with mode value (No).
6.	Created a new column named “Weight Status” that categorizes BMI into different
categories using IFS function.

7.	Created a new column named “Diabetes Status” used IFS function to categorize.
8.	Calculated the ‘Age’ of each customer based on their ‘Date of Birth’ and the date of
collection of the dataset, which is 8 july 2023.
9.	Format ‘charges’ column as currency ($).
10.	Created a new sheet named “Healthcare", which combines all three tables into one, using Customer ID as the common column, utilizing VLOOKUP.
11.created pivo chart to show distribution of cancer history among smokers and non-smokers and how does the total number of major surgeries and average HbA1C differ between patients with and without a history of transplants.
12. Analysis using Column/Bar Chart: healthcare charges vary based on different weight statuses and diabetes statuses using pivo chart. compared the average charges for each hospital tier within different states using pivot chart.
13.created the dashboard and added slicer for  “Weight Status” and “Diabetes Status” and enable filter for all slicer by building relations .



