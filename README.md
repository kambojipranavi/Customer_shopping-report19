PROBLEM STATEMENT :
A retail company wants to analyze customer shopping data to find trends and factors influencing buying decisions, aiming to boost sales, loyalty, and engagement.
"How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?"

# Customer Shopping Behaviour Dashboard (Power BI)

This repository contains a project focused on analyzing customer behavior. The workflow involves data cleaning in Python, analysis in MySQL, and visualization in a Power BI dashboard. This dashboard provides a comprehensive overview of KPIs, sales trends, and customer demographics to drive data-driven business decisions.

## Dashboard Preview

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/48b0c7c5-4eba-48dd-a009-1b9df843cfe2" />


## 📈 Project Overview

The primary goal of this dashboard is to provide a clear and interactive view of customer purchasing patterns. By analyzing metrics related to sales, customer engagement, and demographics, stakeholders can identify key trends, understand customer preferences, and discover opportunities for growth.

## 📊 Key Features & Visualizations

This dashboard is built with a variety of visualizations and interactive slicers to allow for deep-dive analysis.

### 1. Key Performance Indicators (KPIs)

At-a-glance cards that highlight the most important metrics:
* Total Number of Customers: A count of unique customers.
* Average Purchase Amount: The average revenue generated per transaction.
* Average Review Rating: The average customer satisfaction rating (out of 5).

### 2. Interactive Slicers

Dynamic filters that allow users to segment the data in real-time:
* Subscription Status
* Gender
* Product Category
* Shipping Type

### 3. Core Visualizations

* % of Customers by Subscription Status: A donut chart showing the proportion of subscribed vs. non-subscribed customers.
* Revenue by Category: A bar chart comparing total revenue across different product categories.
* Sales by Category: A bar chart comparing the total number of units sold across product categories.
* Revenue by Age Group: A horizontal bar chart segmenting revenue by customer age demographics (e.g., Adult, Senior, Young Adult, Middle-aged).
* Sales by Age Group: A horizontal bar chart segmenting unit sales by the same customer age demographics.


## 🛠 Tools & Technologies

This project's workflow is built on a stack of powerful data tools:

* Data Cleaning: Python (using libraries like Pandas) was used for data cleaning, transformation, and preparation (ETL).
* Data Analysis & Storage: MySQL was used for data storage, querying, and analysis.
* Data Visualization: Microsoft Power BI was used to connect to the data and build the final interactive dashboard.
* DAX (Power BI): Used within Power BI to create key measures such as Average Purchase Amount and Average Review Rating.


## 🚀 How to Use
Open the .pbix file: You will need Power BI Desktop installed on your machine to open and interact with the project file.
Explore: Use the slicers on the left-hand side to filter the data and uncover new insights. Hover over visualizations for more detailed tooltips.
