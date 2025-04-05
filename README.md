# [Power BI] Revenue and Payment Ecosystem Tracking

## I. Introduction
The project involves developing a Power BI dashboard to monitor the Revenue and Payment Ecosystem of a vending machine company, aiming to uncover key insights to support strategic decision-making.

## II. Dataset
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
<img width="1195" alt="Image" src="https://github.com/user-attachments/assets/9364dae4-e50b-4d94-875e-0007233b4f93" />

# V. Insights and Recommendations
| **Insights** | **Recommendations** |
|-------------|---------------------|
| **Ho Chi Minh City** generates **98.06%** of the total revenue, while **Hanoi** contributes only **1.94%**, indicating a major imbalance in **market distribution**. | **Expand sales efforts** in **Hanoi** by launching **targeted marketing campaigns** and ensuring **better product availability** to capture more **market share**. |
| The highest revenue comes from **"Nước" (440M VND)** and **"Snack - Bánh Kẹo" (65M VND)**, making them the **top-performing product categories**. | **Prioritize high-performing categories** by maintaining **adequate stock levels**, running **promotional campaigns**, and offering **bundle deals** to increase **sales further**. |
| The **lowest revenue** comes from **"Trà Chanh" (4M VND)** and **"Thức Ăn Nóng" (3M VND)**, indicating **weak demand** or **low visibility** for these products. | **Improve visibility** and **attractiveness** of these **low-performing products** by **bundling them** with **bestsellers** or offering **limited-time discounts** to encourage trials. |
| **Cash transactions** dominate the **payment ecosystem**, accounting for **63.21%** of all payments, followed by **Momo (15.93%)** and **SkillsHub (15.17%)**. | **Encourage digital payments** by offering **cashback, discounts, or loyalty rewards** for customers using **e-wallets** and other **digital payment methods**. |
| **Ho Chi Minh City** accounts for **97.98%** of all **transactions**, while **Hanoi** only contributes **2.02%**, showing a **lack of payment adoption** in the **northern region**. | **Drive digital payment adoption** in **Hanoi** by increasing **awareness** through **targeted marketing campaigns** and collaborating with **local vendors** to promote **cashless transactions**. |
| **Offices (173M VND)** and **apartments (114M VND)** are the **highest revenue-generating locations**, while **supermarkets (59M VND)** and **cafés (0M VND)** contribute the least. | **Focus on high-performing locations** such as **offices and apartments** by introducing **tailored promotions**, while **reassessing the approach** in **supermarkets and cafés** to improve **product visibility and sales**. |
| **Industrial zones (104M VND)** and **schools (66M VND)** show **strong potential for revenue growth** but remain **underdeveloped**. | **Strengthen partnerships** with **schools and industrial zones** by offering **bulk purchase discounts** and **customized promotions** to increase **order volume** from these **locations**. |
