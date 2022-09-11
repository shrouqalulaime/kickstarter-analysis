# Kickstarting with Excel

## Overview of Project

### Purpose
The project aims to increase the chance of a successful fundraising campaign by analyzing and studying patterns of previous campaign projects. Two principal analysis parts are needed: the first is to find the relationship between the outcome of fundraising campaigns and the goal amount, and the second is to study the correlation between the outcome of a campaign and the launch date. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The relationship between a theater fundraising project's outcome and the launch date is shown in Figure 1. 
The results show that launching a fundraising campaign in May has the highest number of successful projects. The results show a decreasing trend for the number of successful projects starting from June to the end of the year (December). Generally, theater projects are less likely to be canceled throughout the year. The results also show that there is no apparent relationship between the project status to be failed and the launch date. Therefore, other factors might impact the chance of a theater fundraising project to be failed. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/48078471/189516381-f751cc86-d530-4969-93ec-f9ad9afdea16.png)

### Analysis of Outcomes Based on Goals
Figure 2 shows the relationship between the outcome of the play's fundraising project and the gaol. The results show that when the goal is less than $1,000, there is a high probability for the project to succeed (about 76%), and the probability decreases as the gaol amount increases, with zero chance of being successful when the gaol amount is within the range of $45k to $50k. The opposite trend is shown for the failed projects. The probability of a project failing increases as the funding goal amount increases, with more than 80% failing when the amount exceeds $45k. Generally, the plays' campaign projects are less prone to be canceled.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/48078471/189516418-4f9efaac-3861-45d9-8d19-8765a70f39b7.png)

### Challenges and Difficulties Encountered
Many challenges were encountered while working on the first assignment. First, getting used to Github syntax to complete the analysis report was challenging, especially how to insert images with the report. The way to overcome that is by referencing the GitHub documentation formatting syntax. The other challenge was how to use the COUNTIFS function in excel. I referred to the Excel function help section and reviewed the descriptive text about that function. However, it seemed I needed more help, so I watched a video explaining the proper way to implement that function.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?\
1. The best time to launch a fundraising project is in May; there is a high chance of success.
2. Theater projects are less prone to be canceled, so it is recommended to use theater projects.

- What can you conclude about the Outcomes based on Goals?\
The percentage of plays projects to succeed decreases as the goal decreases. Therefore, it is recommended to aim for a goal of less than $15k with more than a 50% probability of completion. 

- What are some limitations of this dataset?\
1. Different currency formats are used for gaol and pledged columns. This might create a bias for outcome based on the gaols plot. 
2. Deadline and launched_at columns use a nonreadable dates format.

- What are some other possible tables and/or graphs that we could create?\
Other charts can be added for more detailed analysis, such as:
1. Studying the relationship between the project's outcome and county. Different campaign projects might have other results. 
2. Find the relationship between the Parent category/subcategory and the outcome. 
