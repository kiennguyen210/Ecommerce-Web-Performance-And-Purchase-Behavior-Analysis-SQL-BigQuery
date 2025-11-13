# Ecommerce Web Performance & Purchase Behavior Analysis | SQL, BigQuery
![Image](https://github.com/user-attachments/assets/87a187d0-9f07-4941-ab65-62e06929886b)

👉🏻Change Icon emoji 🔥🔍📘🚩 to your likings by clicking "Start" + "."

 _Analyze the performance of an e-commerce website, focusing on traffic, engagement, and revenue over time | SQL_

**Author:** Kien Nguyen Duy  

**DOB:** 2000-11-22  

**Tools Used:** SQL

---

## 📑 Table of Contents  
1. [📌 Background & Overview](#-background--overview)  
2. [📂 Dataset Description & Data Structure](#-dataset-description--data-structure)
4. [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)

---

## 📌 Background & Overview  

### Objective:
### 📖 What is this project about? What Business Question will it solve?

🎯 Main Business Question

How can the business optimize website performance and user conversion by analyzing visitor behavior, traffic sources, and product-level purchase patterns?

📘 Project Overview

- This project analyzes website traffic and e-commerce performance data over several months in 2017.
- It focuses on understanding user behavior, traffic source effectiveness, and conversion performance at multiple levels (session, user, and product).
- The project uses SQL queries to extract insights from web analytics data such as visits, pageviews, bounce rates, transactions, and revenue.

💡 Business Questions this project answers

- ✔️ How does website performance change across months (visits, pageviews, and transactions)?
- ✔️ Which traffic sources bring the most valuable visitors and have the lowest bounce rates?
- ✔️ How does revenue vary by traffic source and over time (weekly and monthly trends)?
- ✔️ How do purchasers behave differently from non-purchasers in terms of engagement (pageviews, transactions, and spending)?
- ✔️ What is the average value per session and per customer, helping to measure marketing ROI?
- ✔️ Which products are commonly purchased together, revealing potential cross-sell opportunities?
- ✔️ What is the conversion funnel from product view → add-to-cart → purchase, and how efficient is it for each product?

### 👤 Who is this project for?  

- ✔️ Digital Marketing Teams – to evaluate traffic sources, campaign performance, and bounce rate.
- ✔️ E-commerce Managers – to monitor key metrics like transactions, revenue, and conversion rates.
- ✔️ Product Managers – to identify top-performing and underperforming products and potential bundling opportunities.
- ✔️ Data Analysts – to build dashboards or performance reports using SQL and analytics data.
- ✔️ Business Decision Makers / Executives – to make data-driven decisions about marketing spend, website optimization, and sales strategy.

---

## 📂 Dataset Description & Data Structure  

### 📌 Data Source  
- Source: (Mention where the dataset is obtained from—Kaggle, company database, government sources, etc.)  

### 📊 How to access the data

1. Log in to your **Google Cloud Platform** account and create a new project.
2. Open the **BigQuery Console** and select your project.
3. Click on **"Add Data"** in the navigation panel, then choose **"Search a project"**.
4. In the search bar, enter the project ID: **bigquery-public-data.google_analytics_sample.ga_sessions and press Enter**.
5. Click on the **ga_sessions_** table to explore its structure and data.

---

## ⚒️ Main Process


👉🏻 First, explain codes' purpose - what they do in 1, 2 short sentences.

*_Example_*

## Task 1: Analyze bounce rate...

Bounce rate represents the percentage of website sessions where users visit only one page and leave without interacting further with the site. A high bounce rate can indicate that visitors are not [....]

**_📌You need to show your understanding/ thinking process when you do this analysis. In the above exp, I explain the meaning of Bounce Rate in Marketing performance analysis - which demonstrates my understanding about the metric & its role in my projects/ flow of analysis"_**
**_📌If the task is just simple as "Remove duplication, Replace null value.."--> Summarize all steps related to Transforming & Cleaning data steps in a group & explain shortly at once the reason why you need that transformation_**

👉🏻 Then how your query/ code & Insert screenshots of your result

 **_If your result is a very long table with many records, only show top 5/10 and bottom 5/10 rows, or records that relevant to the insights/ observation below_**

*_Example_*

### Project Results:

| Period   | Name                | Count Items | Count Orders | Sales        |
|:---------|:--------------------|------------:|-------------:|-------------:|
| Apr 2014 | Bib-Shorts          |           4 |            1 |       233.97 |
| Feb 2014 | Bib-Shorts          |           4 |            2 |       233.97 |
| Jul 2013 | Bib-Shorts          |           2 |            1 |       116.99 |
| Jun 2013 | Bib-Shorts          |           2 |            1 |       116.99 |
| Apr 2014 | Bike Racks          |          45 |           45 |     5,400.00 |
| Aug 2013 | Bike Racks          |         222 |           63 |    17,387.18 |
| Dec 2013 | Bike Racks          |         162 |           48 |    12,582.29 |
| Feb 2014 | Bike Racks          |          27 |           27 |     3,240.00 |
| Jan 2014 | Bike Racks          |         161 |           53 |    12,840.00 |
| Jul 2013 | Bike Racks          |         422 |           75 |    29,802.30 |
| ...      | ...                 |         ... |          ... |          ... |
| May 2014 | Vests               |         610 |          103 |    23,640.71 |
| Nov 2013 | Vests               |         315 |           75 |    12,937.24 |
| Oct 2013 | Vests               |         611 |           93 |    23,255.74 |
| Sep 2013 | Vests               |         623 |          102 |    24,100.47 |
| Jul 2013 | Wheels              |           4 |            1 |       698.63 |
| Jun 2013 | Wheels              |           3 |            1 |       450.91 |
| Sep 2013 | Wheels              |           1 |            1 |        83.30 |

*A summary of the full results. The complete dataset is available in the repository.*

👉🏻 Finally, explain your observations/ findings from the results 
  
 _Describe trends, key metrics, and patterns._  

---

## 🔎 Final Conclusion & Recommendations  

👉🏻 Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following:  

📍 Key Takeaways:  
✔️ Recommendation 1  
✔️ Recommendation 2  
✔️ Recommendation 3

**_📌Remember to summarize the most core insights/ observations you extract from the entire projects. 
 Recap ONLY key actions/ recommendations. DO NOT copy paste everything above_**
