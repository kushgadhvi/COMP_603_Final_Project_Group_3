# COMP 603 Final Project - Group 3

## Group Members:
1. Kush Gadhvi
2. Modupe Bello
## Project Desciptions
# Final Project: Impact of COVID-19 on ABC Company’s Parcel Delivery Business

**Type:** Group Assignment  
**Total Marks:** 50  
**Submission Deadline:** December 13, 2024, 11:59 PM  

---

## Objectives:
- Analyze the impact of COVID-19 on ABC Company’s parcel delivery business using the provided dataset.
- Present findings in an executive-style presentation with minimal text and effective visualizations.
- Answer the main business question and additional questions provided.

---

## Dataset:
- **Name:** COVID_Parcel_Business.csv  
- **Fields:** Customer ID, Year, Week Number, Number of Parcels Shipped  

---

## Reports and Grading Rubrics:

| **Topic/Issue**                                     | **Assigned Marks** | **Obtained Marks** | **Comments** |
|-----------------------------------------------------|---------------------|---------------------|--------------|
| PowerPoint Slide for Executive-Level Presentation   | 20                  |                     |              |
| Jupyter Notebook with Python Code and Explanations | 15                  |                     |              |
| GitHub Code Sharing and Collaboration               | 10                  |                     |              |
| Use of Additional Tools                             | 5                   |                     |              |

---

## Background:
The COVID-19 pandemic had diverse effects on Canadian businesses. While some saw growth due to increased e-commerce, others faced revenue declines. ABC Company, serving customers across sectors, experienced unique changes in parcel volumes during this period.

---

## Business Questions:

### Main Question:
**How did the COVID-19 pandemic impact ABC Company’s parcel business?**

### Additional Questions:
1. When were customer volumes first impacted by COVID-19?
2. What events in the COVID timeline contributed to the changes?
3. How did COVID-19 impact the 2020 peak season?

---

## Impact of COVID on Customer Segments:
1. How has COVID affected companies in different customer groups (Enterprise, Large, etc.)?  
2. What percent of each customer group is growing, moderately growing, and declining?  
3. What percent of each customer group are new customers during the COVID observation period?  
4. What percent of 2019 customers in each group did we lose during the COVID observation period?  
5. What was the overall impact of COVID on volumes and revenue by customer group?  

---

## Key Dates:
### 2019:
- **Week 1:** Jan 1, 2019 – Jan 5, 2019  
- **Week 53:** Dec 29, 2019 – Dec 31, 2019  
- **Peak Season:** Nov 4, 2019 – Jan 20, 2020  

### 2020:
- **Week 1:** Jan 1, 2020 – Jan 4, 2020  
- **Week 53:** Dec 27, 2020 – Dec 31, 2020  
- **Pre-COVID Period:** Week 1, 2020 – TBD  
- **COVID Observation Period:** TBD – Week 53, 2020  
- **Peak Season:** Nov 2, 2020 – Jan 17, 2021  

---

## Analytical Guidelines:

### Estimating Growth:
- **Industry Standard Growth Rate (ISGR):**
  
  ISGR (%) = (Volume (current period) - Volume (previous period))/(Volume (previous period) * 100)
  
  - **Current Period:** Week 1 to Week 15, 2020  
  - **Previous Period:** Week 1 to Week 15, 2019  
  - **Volume:** Total parcels shipped during the period.

---

## Customer Segments:
- **High Growth Customers:** Growth > ISGR  
- **Stable Customers:** 0% ≤ Growth ≤ ISGR  
- **Declining Customers:** Growth < 0%  
- **Lost Customers:** Parcels shipped pre-COVID but none during COVID.  
- **New Customers:** No parcels pre-COVID, parcels shipped during COVID.
