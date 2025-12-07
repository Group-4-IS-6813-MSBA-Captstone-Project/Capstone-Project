# Capstone-Project
Fall 2025 IS 6813 Final Capstone Project at the University of Utah for Group 4: Hello World. This repository serves as the collaborative space of the group's combined work in terms of modeling and other aspects of the project.

## Table of Contents
- [Group Notebooks](#group-notebooks)
- [Summary of Business Problem and Project Objective](#summary-of-business-problem-and-project-objective)
 	+ [Business Problem Statement](#business-problem-statement)
	+ [Project Objective](#project-objective)
- [Group 4 Solution to the Business Problem](#group-4-solution-to-the-business-problem)
- [The Business Value of the Solution](#the-business-value-of-the-solution)

## Group Notebooks
| Notebook Title  | About | Link |
| :---: | :---: | :---: |
| IS 6813 Business Problem Statement | Introduction to the capstone project and details about the data provided by SWIRE Coca-Cola| [IS 6813_ Business Problem Statement.pdf](https://github.com/Group-4-IS-6813-MSBA-Captstone-Project/Capstone-Project/blob/main/IS%206813_%20Business%20Problem%20Statement.pdf) |
| IS 6813 EDA Assignment | Group EDA comprised of individual discoveries | [IS 6813 EDA Assignment.Rmd](https://github.com/Group-4-IS-6813-MSBA-Captstone-Project/Capstone-Project/blob/main/IS%206813%20EDA%20Assignment.Rmd)|
| IS-6813 Modeling | Group Modeling based on 4 different success metrics that each team member chose to analyze | [IS 6813 - Modeling.Rmd](https://github.com/Group-4-IS-6813-MSBA-Captstone-Project/Capstone-Project/blob/main/IS%206813%20-%20Modeling.Rmd)|
| IS 6813 Final Presentation | The final presentation slides presented to SWIRE Coca-Cola, inclduing business recommendations | [IS 6813_ Final Presentation.pdf](https://github.com/Group-4-IS-6813-MSBA-Captstone-Project/Capstone-Project/blob/main/IS%206813_%20Final%20Presentation.pdf) |

## Summary of Business Problem and Project Objective
### Business Problem Statement
Swire Coca-Cola’s MyCoke360 ordering platform has been experiencing cases of cart abandonment from their customers, defined as when customers add products to their cart but fail to complete their orders by their next order date. This customer behavior could be contributing to lost revenue and operational inefficiencies. Repeated abandonment may signal a deeper issue such as pricing concerns or misalignment with customer needs. Leadership requires a clear understanding of the drivers of cart abandonment and once identified, provide a recommendation of recovery in order to improve financial and portfolio impact and prioritize interventions that reduce revenue leakage.

### Project Objective
Due to the large dataset containing various features of customer order history and descriptions, a classification model will be implemented to predict the likelihood that a customer will abandon their cart on MyCoke360. A classification model also allows for pattern recognition in order to determine the top key predictors when analyzing the habits of customer cart abandonment.

Proposed Plan:
1. Data Collection & Cleaning: Clean the raw data and combine Google Analytics event data with all order systems, sales, customer, and material data. Define abandoned carts and recovered carts to create labeled outcomes.
2. Model: Build a classification model to predict the probability of cart abandonment at the order window level. Features will include customer segment, device type, time of activity, package type, and historical behavior.
3. Implementation: Use the model outputs to identify customers and packages at highest risk of abandonment. Interventions may include reminder emails/texts, ease of checkout improvements, and adjustments in pricing and availability of packages.
4. Evaluation: Measure success by tracking reductions in abandonment rate, increases in recovery rate, incremental revenue from prevented abandonment, and identification of at-risk packages. Evaluate whether abandonment patterns highlight portfolio risks requiring adjustments to package mix, pricing, or availability.
5. Revision: After initial evaluation, identify areas of weakness in the model and revise - possibly include A/B testing where the new model is compared to older models to see if improvements were made in terms of strength of prediction.

## The Business Value of the Solution
Analyzing why customers are abandoning their cart and the root causes will allow Swire Coca-Cola to predict customers that are most at risk of cart abandonment and implement strategies to combat the issue as a preventative measure. Benefits may include increased revenue from higher order completion rates, improved customer satisfaction with the ordering platform allowing call center agents to focus more on selling than taking orders, and identifying at-risk packages to create a strong portfolio.
 
