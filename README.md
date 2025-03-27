# I. Introduction
The project involves developing a Power BI dashboard to monitor the Revenue and Payment Ecosystem of a vending machine company, aiming to uncover key insights to support strategic decision-making.

# II. Dataset
To access to the datasets, please refer to the [link](https://docs.google.com/spreadsheets/d/1LqbkwkU10uuIpyg_Lp1dZCyLYJ55tHh0/edit?gid=1069178691#gid=1069178691)

## III. Design thinking approach
## Step 1. Empathize 
### 5W-1H
| **Question**                                           | **Answer**                                                                                               |
|----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| **Who will see the dashboard?**                         | The Chief of Operations, Head of Operations, Operations Executive, Operations Team                         |
| **If we have to choose only one stakeholder, who will it be?** | The Chief of Operations (The requester)                                                                   |
| **What problem will the dashboard help to solve?**      | Delivering insightful answers to key questions:<br><br> 1. *"I would like to have a clear picture of our company's **revenue status**."*<br><br> 2. *"I'm seeking an overall view of our **payment ecosystem**. Could you provide an overview of the relative proportions of payment types? How do these payment types distribute across **provinces, categories, and products**?"*<br><br> 3. *"I would like to understand the breakdown of **revenue by product categories**. Are there specific products that we should prioritize in terms of **product positioning**?"* |
| **Where and when will our stakeholders see the dashboard?** | In meetings, presentation sessions, or any situation where decisions need to be made.                      |
| **Why do we have to build the dashboard?**              | Without the dashboard, stakeholders will lack a comprehensive view and detailed analysis, making it difficult to answer the above questions and make data-driven decisions, ultimately impacting the business. |
| **How will our stakeholders see the dashboard to solve their business objectives?** | They need to first see the overall performance and then zoom into the more detailed layers such as payments, products, and other relevant metrics. |

### Empathy map
| **Category**               | **Description**                                                                                             |
|----------------------------|-------------------------------------------------------------------------------------------------------------|
| **Thinking and feeling**    | They feel confused and find it hard to uncover insights when looking at raw data, which interrupts their decision-making process. |
| **Seeing**                  | They see a massive and chaotic pool of raw data.                                                             |
| **Saying and doing**        | "I want to deep dive into the collected data to find insights. I need to give data-driven decisions." <br> They seek data analysis and visualization that support their decision-making process. |
| **Pains**                   | Insufficient data and information may lead to inefficient solutions and decisions.                           |
| **Gains**                   | Key insights, unmet needs, straight-to-the-point strategies, and data-driven solutions.                      |

### Dataset exploration
| **Table Type** | **Description**     |
|----------------|---------------------|
| **Fact table**  | Bán hàng            |
| **Dim table**   | Danh sách máy       |

## Step 2. Ideate
### Northstar metrics
| **Question**                             | **Answers**                                                                                                 |
|--------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| **What VALUE do you want to measure?**     | 1. Revenue  <br> 2. Payment method distribution                                                             |
| **WHY do you choose this metric?**         | 1. Revenue provides an overview of the company's revenue performance and helps identify trends or issues in revenue generation. <br> 2. Payment method distribution gives insights into how different types of payments are used across regions, product categories, and other factors. |

### Dimension group
| **Dimension Data Group**    | **Define Point of View**               |
|-----------------------------|----------------------------------------|
| **Group 1**                 | time                               |
| **Group 2**                 | location                               |
| **Group 3**                 | product                               |
| **Group 4**                 | transaction status                        |

### Point of view
| **View**    | **Description**             | **Why**                                                                                               |
|-------------|-----------------------------|--------------------------------------------------------------------------------------------------------|
| **View 1**  | Revenue Performance         | Answer question 1 + 3: To assess the overall financial health of the business by tracking revenue trends, identifying key revenue drivers, and optimizing pricing or sales strategies. |
| **View 2**  | Payment Ecosystem           | Answer question 2: To analyze different payment methods, transaction success rates, and customer preferences, ensuring seamless and secure payment experiences while identifying opportunities for improvement. |

# IV. Dashboard
### Data modeling
![Image](https://github.com/user-attachments/assets/3fe7da5e-01b2-467c-a717-363559eef76e)

### Dashboard
<img width="1081" alt="Image" src="https://github.com/user-attachments/assets/08ad1391-1226-4280-96d1-9a9f7bc17199" />

# V. Insights
- Revenue status:
The company's revenue experienced a slight increase from March to April (0.4%), followed by a substantial surge from April to May (366.3%), reflecting steady growth and strong financial health.

- payment ecosystem - relative proportions of payment types - (By provinces, categories, and products)
- revenue by product categories - prioritize in terms of product positioning

# VI. Recommendations
