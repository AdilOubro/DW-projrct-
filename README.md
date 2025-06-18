Customer Reviews of Bank Agencies in Morocco - Data Warehouse
This repository contains the data warehouse project for analyzing customer reviews of bank agencies across Morocco. 
The project aims to provide insights into customer satisfaction, identify key areas for improvement, and support strategic decision-making for banking institutions in Morocco.

Project Organizers
Adil Oubro
Salma Elnassiry
Project Overview
The core objective of this project is to build a robust data warehouse that consolidates customer feedback from various sources related to Moroccan bank agencies. 
By transforming raw review data into a structured and analyzable format, we enable comprehensive reporting and analytical capabilities.

Repository Structure
This repository is organized as follows:

automatisation/: Contains scripts and configurations for automating data extraction, transformation, and loading (ETL) processes.
dashboard images/: Stores screenshots or exported images of dashboards created from the data warehouse (e.g., Power BI, Tableau, Looker Studio).
data loading/: Includes scripts or documentation related to the initial loading of data into the data warehouse.
data/: Raw or processed source data files before being loaded into the data warehouse.
data_transformation/: Holds scripts (e.g., SQL, Python) used for cleaning, transforming, and integrating data into the data warehouse schema.
paycache/: (Please specify if this folder has a specific purpose related to the project, e.g., temporary payment-related data, caching mechanisms.
If not relevant, consider removing or renaming it for clarity.)
README.md: This file, providing an overview of the project.
Key Features
Data Integration: Aggregates customer reviews from diverse sources.
ETL Pipelines: Automated processes for data extraction, cleaning, transformation, and loading.
Dimensional Modeling: Implements a star or snowflake schema for efficient querying and analysis.
Performance Optimization: Designed for fast data retrieval and reporting.
Insight Generation: Facilitates the identification of trends, pain points, and areas of excellence in bank agency services.
Technologies Used

Version Control: Git, GitHub
Setup and Usage
To set up and run this project locally, follow these steps:

Clone the repository:
Bash

git clone https://github.com/AdilOubro/DW-project.git
cd DW-project


The data warehouse employs a star schema with a central Fact_Customer_Review table linked to several dimension tables such as:

Dim_Date: For analyzing reviews over time.
Dim_Bank_Agency: Details about bank branches (location, name, etc.).
Dim_Customer: (If customer-specific data is collected).
Dim_Sentiment: Categorization of review sentiment (positive, negative, neutral).
Dim_Service_Category: Categories of banking services reviewed.
Future Enhancements
Integration of real-time review streams.
Advanced natural language processing (NLP) for deeper sentiment analysis.
Predictive analytics for customer churn or satisfaction.
Expansion to include other banking products/services.
Contribution
While this project is primarily organized by AdilOubro and Salma Elnassiry, contributions, suggestions, and feedback are welcome. Please open an issue or pull request if you have any ideas or improvements.
