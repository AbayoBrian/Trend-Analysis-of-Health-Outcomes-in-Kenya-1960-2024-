## 📌 Project Title

Trend Analysis of Health Outcomes in Kenya (1960–2024): A Data-Driven Study for Policy and Development

Overview

This project analyzes long-term health and demographic trends in Kenya using World Bank indicator data. The goal is to generate insights that support evidence-based decision-making in public health, policy planning, and development programs.

The analysis focuses on child mortality, population structure, and dependency ratios to understand how health outcomes have evolved over time.

Relevance

This project is aligned with organizations such as:

Amref Health Africa
African Population and Health Research Center
UN Environment Programme
Dataset
Source: World Bank Open Data
Coverage: 1960–2024
Structure: Country-year panel dataset
Key focus country: Kenya (KEN)
Key Features Analyzed
Infant mortality (counts → rates)
Under-five mortality (counts → rates)
Population structure (male/female)
Age dependency ratio
 Methodology
1. Data Cleaning
Removed missing values
Filtered Kenya (ISO code: KEN)
Sorted data by year
2. Feature Engineering
Converted raw death counts into:
Infant death rate per 1000 population
Under-five death rate per 1000 population
Created total population feature
3. Exploratory Data Analysis
Trend analysis over time
Correlation analysis between demographic pressure and mortality
   Key Insights
Infant and under-five mortality rates show a long-term decline
Improvements reflect progress in healthcare access and child survival programs
Higher dependency ratios may increase pressure on health systems
   Tools Used
Python (Pandas, NumPy)
Matplotlib
Jupyter Notebook / Google Colab
How to Run
1. Clone repository
2. Open notebook in Google Colab or Jupyter
3. Upload health.csv dataset
4. Run cells sequentially
 Future Improvements
Integrate poverty and education datasets
Build predictive model for mortality trends
Create Power BI dashboard for policy visualization
