Samsung Smartphone Business Intelligence Analysis
Project Overview

This project presents a Business Intelligence analysis of Samsung smartphone specifications using Power BI. The objective of the analysis is to explore how key technical specifications such as RAM, storage capacity, battery size, and price relate to customer ratings and perceived product value.

By transforming raw smartphone data into interactive dashboards, the project aims to identify patterns in product performance, highlight high-value smartphones, and provide insights that can support product design and pricing decisions.

The analysis demonstrates how Business Intelligence tools can be used to convert structured product data into actionable insights for strategic decision-making.

Business Problem

Smartphone manufacturers must balance technical specifications, pricing strategies, and customer satisfaction to remain competitive in a rapidly evolving market.

However, identifying which product features contribute most to positive user perception and value can be challenging when dealing with large datasets.

This project addresses the following questions:

How are Samsung smartphones distributed across price segments?

Which technical specifications influence customer ratings?

Do higher-priced smartphones necessarily receive higher ratings?

Which smartphones deliver the best value relative to their price and specifications?

Dataset

The dataset used in this project contains technical specifications of Samsung smartphones.

Key attributes include:

Model name

Price

RAM

Storage capacity

Battery capacity

Android version

Processor type

Camera specifications

Customer rating

During the ETL process, the dataset was cleaned, transformed, and converted into a structure suitable for Business Intelligence analysis.

Data Preparation (ETL Process)

Data preparation was performed before building the dashboards to ensure accuracy and usability.

Steps included:

Removing irrelevant columns

Handling missing or inconsistent values

Converting price values to USD

Standardizing specification formats

Creating derived fields such as storage tiers

Structuring the dataset for analytical modeling

A star schema model was implemented to organize the data efficiently within Power BI.

Data Model

The dataset was structured using a star schema to optimize analytical performance.

Fact Table

Fact_Smartphones

Dimension Tables

Dim_Processor

Dim_Android

Dim_Camera

Dim_Display

This modeling approach improves query efficiency and supports scalable dashboard development.

Power BI Dashboards

Three interactive dashboards were developed to analyze the smartphone product portfolio.

Dashboard 1 — Product Overview

Purpose: Provide a high-level view of Samsung’s smartphone portfolio.

Key visuals:

KPI cards (Average Price, Average Rating, Total Smartphones)

Price distribution histogram

RAM distribution chart

Insights obtained:

Distribution of smartphones across price segments

Overview of specification configurations within the portfolio
<img width="945" height="559" alt="image" src="https://github.com/user-attachments/assets/9e6b4f56-1999-41a1-8ef4-4cbed49c4751" />


Dashboard 2 — Performance Analysis

Purpose: Identify how technical specifications influence customer ratings.

Key visuals:

Price vs Rating scatter plot

Rating by RAM bar chart

Rating by Storage bar chart

Battery capacity distribution

Insights obtained:

Relationship between technical specifications and user satisfaction

Identification of specification levels associated with higher ratings
<img width="945" height="539" alt="image" src="https://github.com/user-attachments/assets/4fdbd7b2-0e88-4fd4-9de8-9de317ef3132" />

Dashboard 3 — Product Value Analysis

Purpose: Identify smartphones that deliver strong value relative to their price.

Key visuals:

Price vs RAM scatter plot

Price vs Storage scatter plot

Top Value Smartphones table

Insights obtained:

Detection of models offering strong specifications at competitive prices

Identification of potential pricing inefficiencies

Key Insights

Several important insights emerged from the analysis:

Samsung smartphones are concentrated in mid-range price segments.

Customer ratings are consistently high across most models, typically between 4.0 and 4.3.

Higher RAM and storage configurations tend to correlate with slightly higher ratings.

Some mid-range devices deliver strong specifications and ratings at relatively moderate prices, representing strong value propositions.
<img width="945" height="571" alt="image" src="https://github.com/user-attachments/assets/5b11f430-a733-4243-b5e9-07a6fb090252" />

Business Value

This analysis demonstrates how product data can be transformed into actionable insights using Business Intelligence tools.

The dashboards provide decision-makers with a clear understanding of:

Product portfolio structure

Feature impact on customer satisfaction

Price-to-performance relationships

High-value product opportunities

These insights can support more effective product development and pricing strategies.

Limitations

Some limitations of the analysis include:

The dataset does not include sales volume or revenue data.

Customer ratings may not fully represent long-term user satisfaction.

Competitor smartphone data was not included for comparative analysis.

Future Improvements

Future extensions of the project could include:

Integrating sales data to analyze product demand and revenue performance

Incorporating competitor smartphone datasets for benchmarking

Applying predictive models to estimate the impact of specifications on ratings

Developing price segmentation and market positioning dashboards

Tools & Technologies

Power BI

Python (for data cleaning and ETL)

Pandas

Data Modeling (Star Schema)
