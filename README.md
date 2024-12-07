# COMP 603 Final Project - Group 3

## Group Members:
1. Kush Gadhvi
2. Modupe Bello

Final Project
Type: Group Assignment
Total Marks = 50
Submission DL: December 13, 2024, 11:59 PM
Objectives:
	Case Study - Impact of COVID-19 on ABC Company’s Parcel Delivery Business.
	The submission should be in presentation form (e.g., PowerPoint) and demonstrate your ability to use visualization to tell a story while limiting the need for extensive text.
	For this case study, you will be given a business question and a dataset and are asked to perform all steps in the analytical process necessary to answer the business questions in an executive style presentation (i.e., a presentation to executive level who understand the business but are limited in advanced analytics knowledge).
	You are encouraged to go beyond what is explicitly required if it aligns with the overall purpose of the analysis. 

Dataset:
The dataset (COVID_Parcel_Business.csv) includes customer IDs, the year, the week number, and the number of parcels shipped that week. 

Reports and Grading Rubrics (Table):
	A Jupyter Notebook to show the computation performed using Python Language. You may use Excel as an additional tool to verify your results.
	Prepare an executive presentation that:
	Clearly presents relevant descriptive statistics.
	Outlines the objectives of the study in your own words.
	Answers each of the business questions described in the next section.
	Includes the results of any analysis you performed to answer the business question.
	Include any next steps or recommendations you wish to offer.
	Use line, bar, and pie charts in the report.


Topic/Issue	Assigned Marks	Obtained Marks	Comments
PowerPoint slide for Executive-level	20		
Jupyter Notebook with Python Code and Explanations	15		
GitHub code sharing and collaboration	10		
Use of additional tools to help the presentation (e.g. PowerBI to create a chart, Excel to verify the Python Analytical results etc)	5		

Background
The COVID-19 pandemic impacted Canadian businesses in various ways. Some businesses saw unprecedented growth due to increased e-commerce activity, while others found their product or service revenue plummeted. At ABC Company, we have customers from all sectors who have experienced COVID in their unique ways. 

Main Business Question
How did the COVID-19 pandemic impact ABC Company’s parcel business?

Additional Business Questions:
	When were customer volumes first impacted by COVID-19?
	What events within the COVID timeline may have contributed to the change?
(use a line graph to see the changes and match the timeline)
	How did COVID-19 impact peak season in 2020?  (check the peak for 2022 and see the impact.)

The Impact of COVID on Customer Segments:
	How has COVID affected companies in the different customer groups (Enterprise, Large, etc.)?
	What percent of each customer group is growing, moderately growing, and declining during the COVID observation period? 
	What percent of each customer group are new customers during the COVID observation period? 
	What percent of 2019 customers in each group did we lose during the COVID observation period?
	What was the overall impact of COVID on volumes and revenue by customer group?

2019 Important Dates
	START DATE	END DATE
Week 1	Tuesday, January 1, 2019	Saturday, January 5, 2019
Week 53	Sunday, December 29, 2019	Tuesday, December 31, 2019
Peak Season	November 4, 2019	January 20, 2020



2020 Important Dates:
	START DATE	END DATE
Week 1	Wednesday, Jan 1, 2020	Saturday, Jan 4, 2020
Week 53	Sunday, Dec 27, 2020	Thursday, Jan 31, 2020
Pre-COVID Observation Period	Week 1, 2020	TBD by Candidate
COVID Observation Period	TBD by Candidate http://www.whatweekisit.org/	Week 53 2020
Peak Season	November 2, 2020	January 17, 2021

 

Customer Groups and Margin information
Note: For this case study, we will assign an average cost to a parcel and discounts for customers. 
Discounts are applied to customers who agree to ship a specific number of parcels with ABC Company within one year. For the purpose of this exercise, the base cost of sending a parcel without a contract is $22.00. 

 

How to estimate whether a company is growing or not:
	Estimate the Industry standard growth rate (ISGR) by comparing pre-COVID 2020 volumes to the same period in 2019. This pre-COVID period will be used to compare growth rates before COVID-19 to growth rates during the COVID-19 pandemic.
	ISGR(%)=(〖Volume〗_(current_period)-〖Volume〗_(previous_Period))/〖Volume〗_(previous_period) ×100
	Current period: week 1 to week 15, 2020
	Previous period: week 1 to week 15, 2019
(Use this for growth rate )
	Volume: Total parcel volume of the mentioned period

Label	LOW	HIGH
New Customers	0 parcels in 2019/early 2020	1+ parcels during COVID period
High Growth Customers	Greater than ISGR in the COVID observation period	unlimited
Stable Customers	0% growth during COVID period	ISGR during COVID period
Declining Customers	N/A	Negative growth during COVID period
Lost Customers	1+ parcels in 2019/early 2020	0 parcels after onset of COVID period


