# Module 5 Challenge

## Background


You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specialises in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumours received treatment with a range of drug regimens. Over the course of 45 days, tumour development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

## Instructions

This assignment is broken down into the following tasks:

Prepare the data.

Generate summary statistics.

Create bar charts and pie charts.

Calculate quartiles, find outliers, and create a box plot.

Create a line plot and a scatter plot.

Calculate correlation and regression.

Submit your final analysis.

## Prepare the data

1. Run the provided package dependency and data imports, and then merge the mouse_metadata and study_results DataFrames into a single DataFrame.

2. Display the number of unique mice IDs in the data, and then check for any mouse ID with duplicate time points. Display the data associated with that mouse ID, and then create a new DataFrame where this data is removed. Use this cleaned DataFrame for the remaining steps.

3. Display the updated number of unique mice IDs.

![Local Goverment Area (LGA) Summary](LGA_Summary.PNG)

## School Summary


School name

School type

Total students

Total school budget

Per student budget

Average maths score

Average reading score

% passing maths (the percentage of students who passed maths)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed maths AND reading)

The School Summary key metrics are presented below:

![School Summary](School_Summary.PNG)


## Top Performing Schools (By % Overall Passing)

![Top Performing Schools](Top_Perf_Ov_Passing.PNG)

## Bottom Performing Schools (By % Overall Passing)

![Bottom Performing Schools](Bottom_Perf_Ov_Passing.PNG)


## Maths Scores by Year

![Maths Scores by Year](Maths_Scores_Year.PNG)

## Reading Scores by Year

![Reading Scores by Year](Reading_Scores_Year.PNG)

## Scores by School Spending

![Scores by School Spending](School_Spending.PNG)

## Scores by School Size

![Scores by School Size](School_Size.PNG)

## Scores by School Type

![Scores by School Type](School_Type.PNG)

## Conclusions -- Written Report

1.	Small schools have the highest Average Math and reading scores, with 72.24 % and 71.63 %, respectively. In contrast, the lowest average scores come from large schools, with 69.93% for Maths and 69.68 % for reading. Small schools also have the highest Overall number of students passing, with 79.12 % passing both Maths and Reading, as opposed to large schools, with the lowest overall passing scores of 70.97%.

2.	Overall, the highest grades for Math and Reading come from schools with a $585-630 budget per student, with 72.17 % average grade for math and 70.97 % for Reading. Conversely, the lowest overall grades come from schools with the highest budget per student ($645-680), with 68.88 % on average for Math, 69.06% for reading and 66.77% Overall passing. 

3.	Overall, the best-performing schools are Independent, with 71.11 % average Math marks, 70.48 % Reading and 76.22 % of the students passing overall. On the other hand, in government schools, only 71.27% pass overall, with slightly lower marks of 69.99% for Maths and 69.75 % for reading, respectively. The top performing school, Griffin High School is an independent school with a $585-630 budget per student and the bottommost performing school, Hernandez High School, is a government school with the highest per Student budget of $645-680.

Tables matching the calculations above performed with Excel are presented below to corroborate the results

![Scores by School Size](School_Size_a.PNG)

![Scores by School Spending](School_Spending_a.PNG)

![School Summary Total](School_Type_a.PNG)

Other interesting tables below

![Per Student Budget vs Type count](bud-type.PNG)

![School Size vs Type count](size_type_a.PNG)

![School Size vs Per Student Budget count](size-bud_a.PNG)

![School Summary Total](total_a.PNG)



## Submission

1. Submitted and available in GitHub under https://github.com/lcardsvr/pandas-challenge

2. Written report is included in the Readme.md file 

3. Code for the submission is available under https://github.com/lcardsvr/pandas-challenge/blob/main/PyCitySchools/PyCitySchools_starter.ipynb

4. Excel verification sheet with matching numbers to the calculations obtained above is available under https://github.com/lcardsvr/pandas-challenge/blob/main/PyCitySchools/Resources/students_complete_Excel_Analysis.xlsm 


