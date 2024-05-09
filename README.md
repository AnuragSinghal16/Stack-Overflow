# Stack-Overflow

## Introduction
In this analysis, I am using the annual Stack Overflow survey data from 2023 to answer three questions:

  1. Is there a difference in the size of companies that hire self-taught developers than the ones who do not?
  2. What is difference between the salary of self-taught developers vs. formally-educated developers? Does Years of Experience matter?
  3. Does geography matter? Which country are you most likely to excel in as a self-taught developer?

I will only analyse this data using inferential statistics as modelling is not the agenda of this analysis

## Assumptions and Methodology:
1. I have assumed respondents with a formal education as someone with a response = 'Bachelor’s degree (B.A., B.S., B.Eng., etc.)', 'Master’s degree (M.A., M.S., M.Eng., MBA, etc.)', 'Professional degree (JD, MD, Ph.D, Ed.D, etc.)' in the EdLEvel
2. Self-taught developers will be everyone else
3. Columns with all null values are dropped
4. Null rows in EdLevel and CompTotal columns are dropped
5. Direct comparison of Salary was giving a very skewed visualization due to which normalizing the column was necessary

## Data

I've uploaded the dataset folder as a .zip file. Once you extract the folder, you will find the following files:
  1. readme_2023
  2. so_survey_2023
  3. survey_results_public
  4. survey_results_schema

You can read file 1 & 2 to know more about how the survey was conducted and some general terms and conditions. File 3 & 4 are the data file used for the analysis.

File 3 holds the actual response data used to analyse the data, and file 4 can be used to understand the data in file 3. It will help explain what each column stands for.

## Links

Access the data here - https://survey.stackoverflow.co/

I have also written a blog post on Medium to summarise my findings. Please give it a read - https://medium.com/@anuragsinghal1610/breaking-the-mold-self-taught-vs-formally-educated-developers-e19bd5ddc989
