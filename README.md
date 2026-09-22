# Task 6 – Presentation and Reporting

## Fashion Market Research and Data Analysis

### Overview

This repository contains the work completed for **Task 6 – Presentation and Reporting** as part of the Fashion Market Research internship.

The purpose of this task was to consolidate the findings from the previous tasks into a structured report covering:

- Market research and data collection
- Data cleaning and preprocessing
- Exploratory data analysis
- Power BI visualization
- Predictive modelling
- Strategic recommendations
- Overall findings and business implications

The final report combines the results obtained throughout the previous tasks into one comprehensive and logically structured document.


## Objective

The main objective of Task 6 was to present the complete fashion market research workflow in a clear and organized manner.

The report focuses on identifying:

- Pricing patterns across fashion brands
- Product and category distribution
- Customer engagement and popularity
- Sustainability trends
- Factors associated with product pricing
- Strategic recommendations based on analytical findings


## Brands Covered

The analysis covers five fashion brands:

- Nike
- Chanel
- Louis Vuitton
- Zara
- Gucci

These brands represent different segments of the fashion market, including luxury fashion, mass fashion, and sportswear.


## Dataset

The updated dataset used for the final analysis contains:

- **173 product records**
- **19 columns**

The dataset includes information such as:

- Brand
- Product Category
- Sub Category
- Product Name
- Price_INR
- Availability
- Target Age Group
- Segment
- Country of Origin
- Sustainability Score
- Store Type
- Stock Units
- Ratings
- Reviews Count
- Date Added
- Size Variants
- Color Variants
- SKU

### Dataset Update

During the transition from Task 2 to Task 3, the dataset was reviewed and updated to ensure complete brand coverage.

The initial Task 2 submission contained an incomplete version of the dataset because records for **Zara were unintentionally omitted**. This was identified before proceeding with the analysis, and the dataset was updated before Task 3.

Therefore, the **updated 173-record dataset** was used for:

- Power BI analysis
- Data visualization
- Predictive modelling
- Strategic recommendations
- Final Task 6 reporting

This ensures that the final analytical findings are based on the corrected dataset.



## Tools and Technologies

The following tools were used throughout the tasks:

- **Microsoft Excel / CSV** – Dataset preparation and review
- **Python** – Data preprocessing and predictive modelling
- **Jupyter Notebook** – Model development and evaluation
- **Power BI** – Data visualization and dashboard creation
- **Microsoft Word** – Final report preparation
- **GitHub** – Project documentation and version management

### Python Libraries

The predictive modelling work used Python libraries including:

- pandas
- NumPy
- scikit-learn
- matplotlib


## Project Workflow

The overall workflow followed these stages:

### 1. Market Research and Data Collection

Market information was collected for Nike, Chanel, Louis Vuitton, Zara, and Gucci.

The research focused on:

- Product categories
- Pricing
- Brand positioning
- Sustainability
- Customer engagement
- Social media presence
- Market trends

---

### 2. Data Cleaning and Preprocessing

The dataset was reviewed and prepared before analysis.

The preprocessing workflow included:

- Handling missing values
- Correcting incorrectly placed values
- Standardizing dates
- Converting numerical columns into appropriate data types
- Validating ratings and sustainability scores
- Checking duplicate records and SKUs
- Checking invalid and negative numerical values
- Reviewing potential outliers

After the dataset was updated, the complete dataset was used for the subsequent analytical tasks.


### 3. Exploratory Data Analysis

The dataset was analyzed to understand:

- Brand-level pricing
- Sustainability scores
- Customer ratings
- Product categories
- Market segments
- Customer engagement
- Product popularity

Some key observations from the analysis include:

- Chanel had the highest average product price among the analyzed brands.
- Louis Vuitton also showed a high average price level.
- Nike and Zara had substantially lower average prices than the luxury brands.
- The overall average customer rating was approximately **4.5/5**.
- Apparel and accessories represented major portions of the product sample.
- Apparel generated the highest review volume among the analyzed categories.


## Power BI Dashboard

A Power BI dashboard was created to present the major analytical findings interactively.

### Key KPIs

The dashboard includes:

- **Total Products:** 173
- **Average Price:** approximately ₹75K
- **Average Rating:** 4.5
- **Total Reviews:** approximately 32K
- **Average Sustainability Score:** 4.9

### Visualizations

The dashboard contains visualizations for:

- Average Price by Brand
- Average Sustainability Score by Brand
- Price vs Rating by Brand
- Product Mix by Segment
- Product Popularity by Category
- Customer Engagement by Product Category

These visualizations were used to identify patterns and differences across brands, categories, and market segments.


## Predictive Modelling

Predictive modelling was performed to estimate **product price (Price_INR)** using selected product and market-related features.

### Target Variable

Price_INR
