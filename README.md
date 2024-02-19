# Providing data-driven suggestions for HR 

**Overview**

In this project, we are going to analyze a dataset and build predictive models that can provide insights to the Human Resources (HR) department of a large consulting firm.

We will use different machine learning models to predict whether or not an employee will leave the company. We then will compare their performance and choose the champion model for deployment

**Business Understanding**

The HR department at Salifort Motors wants to take some initiatives to improve employee satisfaction levels at the company. They collected data from employees, but now they don’t know what to do with it. They want to be provided with data-driven suggestions based on the data. They have the following question: what’s likely to make the employee leave the company?

My goals in this project are to analyze the data collected by the HR department and to build a model that predicts whether an employee will leave the company.

If we can predict employees likely to quit, it might be possible to identify factors that contribute to their leaving. Because it is time consuming and expensive to find, interview, and hire new employees, increasing employee retention will be beneficial to the company.

**Data Understanding**

In this [dataset](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv), there are 14,999 rows, 10 columns. The features included information on employee-reported job satisfaction levels [0–1], the score of the employee's last performance review [0–1], the number of projects the employee contributes to, the average number of hours the employee worked per month, Whether or not the employee left the company. 

The visualization below shows a stacked boxplot showing average_monthly_hours distributions for number_project, comparing the distributions of employees who stayed versus those who left.
[](images/monthly_hours_vs_#projects.png)


