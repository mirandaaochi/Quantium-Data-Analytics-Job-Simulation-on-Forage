# Quantium Data Analytics Job Simulation on Forage

Founded in 2002, Quantium has a long history of innovation in data science across all sectors of the economy. As a rapidly growing global leader in data science and AI, we are dedicated to growing our team of ambitious, diverse, and fun employees! Our team of employees work together to harness the power of data to drive revolutionary change that benefits us all and deliver the best results for our clients.

Through this program, you will act as a data analyst at Quantium and take part in the challenging but fun work our data analysts do daily! You will learn practical skills such as data validation, data visualisation, statistical testing and more. After completing each module, you will be able to compare your work with real model solutions created by the Quantium team for a chance to learn directly industry leaders.

## Executive Summary

**Task One: Data Preparation and Customer Analytics**

Conduct analysis on your client's transaction dataset and identify customer purchasing behaviours to generate insights and provide commercial recommendations.

**Task Two: Experimentation and Uplift Testing**

Extend your analysis from Task 1 to help you identify benchmark stores that allow you to test the impact of the trial store layouts on customer sales.

**Task Three: Analytics and Commercial Application**

Use your analytics and insights from Task 1 and 2 to prepare a report for your client, the Category Manager.

## Business Problem

**Task One: Data Preparation and Customer Analytics**

The Category Manager for Chips, wants to better understand the types of customers who purchase Chips and their purchasing behavior within the region. The insights from your analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.

**Task Two: Experimentation and Uplift Testing**

The Category Manager for Chips, has asked us to test the impact of the new trial layouts with a data driven recommendation to whether or not the trial layout should be rolled out to all their stores.

## Methodology

**Task One: Data Preparation and Customer Analytics**

What You'll Learn:
  * Understand how to examine and clean transaction and customer data.
  * Learn to identify customer segments based on purchasing behavior.
  * Gain experience in creating charts and graphs to present data insights.
  * Learn how to derive commercial recommendations from data analysis.

What You'll Do:
  * Analyze transaction and customer data to identify trends and inconsistencies.
  * Develop metrics and examine sales drivers to gain insights into overall sales performance.
  * Create visualizations and prepare findings to formulate a clear recommendation for the client's strategy.

**Task Two: Experimentation and Uplift Testing**

What You'll Learn:
  * Understand experimentation and uplift testing, comparing trial and control stores.
  * Learn control store selection based on defined metrics.
  * Gain experience in data visualization.
  * Perform statistical analysis to assess sales differences and formulate recommendations.

What You'll Do:
  * Define metrics to select control stores.
  * Analyze trial stores against controls.
  * Use R for data analysis and visualization and summarise findings and provide recommendations.

**Task Three: Analytics and Commercial Application**

What You'll Learn:
  * Gain experience in preparing a client report based on data analysis.
  * Understand the "Pyramid Principles" framework for report structure.
  * Practice creating data visualizations and key callouts.
  * Develop skills in translating data into actionable insights and recommendations.

What You'll Do:
  * Use the Pyramid Principles framework for structuring the report.
  * Submit a report that incorporates data visualizations, key insights, and recommendations.

## Skills

R: data validation, data visualization, statistical testing

## Results and Business Recommendations

**Chips Category Review**

![Transactions over time](https://github.com/user-attachments/assets/cdbe9236-33ee-426a-967d-ee460570542b)

Chip transactions have remained relatively consistent over the last 52 weeks. There is a notable increase and gap that occurs in December.

![Transactions in December](https://github.com/user-attachments/assets/a1395dd8-a677-4332-aaf5-a5e8a80af709)

Zooming in, we see that transactions in the week including Christmas were negatively affected by store closures for the holiday.

![Proportion of sales](https://github.com/user-attachments/assets/abdf1675-946c-464e-a410-d7185868335c)

Chip sales were mainly to Budget - older families, Mainstream - young singles/couples, and Mainstream - retirees.

![Proportion of Customers](https://github.com/user-attachments/assets/4d384064-494c-4c96-aba0-b57cff009d13)

There are more mainstream young singles/couples and retirees in total.

![Units per Customer](https://github.com/user-attachments/assets/7bbb70e3-b614-4256-be8e-3f79845d6ea7)

Affluence appears consistent across each individual life stage profile. Older families and young families generally buy more chips per customer.

![Price per Unit](https://github.com/user-attachments/assets/341bb1b2-fe6e-4f7f-9016-73e26fbee55c)

Mainstream, mid-age, and young singles/couples are more likely to pay more per packet. This is indicative of impulse buying behavior.

**Trial Store Performance**

Trial Stores: 77, 86, 88

The trial period goes from the start of March 2019 to June 2019.

Control stores were selected based on similarities in monthly overall sales revenue, monthly number of customers, and monthly number of transactions per customer.

*Trial Store 77 vs. Control Store 233*

![Control vs  Trial (77) Customers](https://github.com/user-attachments/assets/52ec40ca-afd9-4495-b277-8efbd956d31f)

![Control vs  Trial Sales (77)](https://github.com/user-attachments/assets/f3011052-39e2-4105-ba78-60d5b034a401)

From February to May, the trial store (77) outperformed the control store highlighting the success of the new store layout.

*Trial Store 86 vs. Control Store 155*

![Control (155) vs  Trial (86) Total Customers by Month](https://github.com/user-attachments/assets/f353d01f-3ca1-4cd0-a9a5-9326ccab1c75)

![Control (155) vs  Trial (86) Total Sales by Month](https://github.com/user-attachments/assets/7466b40b-7b48-4e81-bcfc-518b14d6390e)

From February to May, the trial store (86) outperformed the control store with customers but not sales.

*Trial Store 88 vs. Control Store 237*

![Control (237) vs  Trial (88) Total Customers](https://github.com/user-attachments/assets/a1c9c093-5571-4022-b2ce-d932220bb420)

![Control (237) vs  Trial (88) Total Sales](https://github.com/user-attachments/assets/ddf935bb-9c59-49ee-bded-34819536f67e)

From February to May, the trial store (88) outperformed the control store highlighting the success of the new store layout.

The results for trial stores 77 and 88 during the trial period show a significant difference in at least two of the three trial months but this is not the case for trial store 86. We can check with the client if the implementation of the trial was different in trial store 86 but overall, the trial shows a significant increase in sales. 
