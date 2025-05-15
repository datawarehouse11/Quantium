# Quantium Data Analysis - Retail Insights

This repository contains materials related to a data analysis project completed as part of the Quantium Data Science job simulation on Forage. The project focuses on understanding customer purchasing behavior in the chips category for a supermarket client. The goal is to provide insights and recommendations to inform the client's strategic plan.

## Project Overview

The project involves analyzing transaction and customer data to identify trends, segment customers, and provide commercial recommendations. The analysis aims to help the client, a Category Manager for Chips, better understand their customer base and their purchasing behavior.

The key objectives of the project are to:

* Examine and clean transaction and customer data.
* Identify customer segments based on purchasing behavior.
* Create visualizations to present data insights.
* Derive commercial recommendations from the data analysis.

## Repository Contents

This repository includes the following files:

* **`Quantium.ipynb`**: This Jupyter Notebook contains the core data analysis, including:
    * Data loading and merging.
    * Data cleaning and preprocessing.
    * Exploratory data analysis (EDA).
    * Customer segmentation.
    * Visualization of results.
* **`Quantium.docx`**: This document provides an overview of the project, including the task description, learning objectives, and background information. It outlines the context of the analysis and the client's needs.
* **`QVI_purchase_behaviour.csv`**: This dataset contains customer demographic and segment information.
* **`QVI_transaction_data.xlsx`**: This dataset contains transaction-level data, including purchase details.

## Data Description

The analysis uses two main datasets:

* **QVI_transaction_data.xlsx**: Contains transaction data, with details on individual purchases.
* **QVI_purchase_behaviour.csv**: Contains customer data, including demographic information and customer segmentation.

Key data attributes include:

* **Transaction Data**: Transaction ID, Customer ID, Transaction Date, Product ID, Quantity, Sales Value.
* **Customer Data**: Customer ID, LIFESTAGE, PREMIUM_CUSTOMER.

## Analysis Performed

The analysis in the `Quantium.ipynb` notebook involves the following steps:

1.  **Data Loading and Merging**: Loading the transaction and customer datasets and merging them to create a combined dataset for analysis.
2.  **Data Cleaning and Preprocessing**: Identifying and handling missing values, inconsistencies, and outliers in the data. This step ensures data quality and prepares it for further analysis.
3.  **Exploratory Data Analysis (EDA)**: Exploring the data to understand key trends and patterns, including:
    * Analyzing sales performance.
    * Examining customer demographics.
    * Investigating purchasing behavior.
4.  **Customer Segmentation**: Identifying distinct customer segments based on their purchasing behavior. This likely involves grouping customers based on attributes like purchase frequency, spending, and product preferences.
5.  **Visualization**: Creating charts and graphs to effectively communicate data insights and findings. This helps in understanding the data and presenting recommendations to the client.

## Key Insights and Recommendations

The analysis aims to provide insights into:

* Customer demographics and their purchasing behavior in the chips category.
* Key drivers of sales performance.
* Opportunities for targeted marketing and product strategies.
* Recommendations for the client's strategic plan for the chip category.

## Libraries Used

The following Python libraries are used in this project:

* **`pandas`**: For data manipulation and analysis.
* **`numpy`**: For numerical computations.

## Getting Started

To view the analysis, open the `Quantium.ipynb` file using Jupyter Notebook or JupyterLab. Ensure you have the necessary Python libraries installed:

```bash
pip install pandas numpy
