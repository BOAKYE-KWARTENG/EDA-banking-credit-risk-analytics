# EDA Banking Credit Risk Analytics
Exploratory Data Analysis on banking credit risk, borrower segmentation, loan default patterns, and lending insights using Python (Pandas, Seaborn, and Machine Learning clustering techniques).


## Executive Summary:
The dilemma that financial institutions continuously have to address is how to make loans available while managing credit risk. For this analysis, I performed Exploratory Data Analysis (EDA) on borrower and loan information to identify patterns related to loan default risk and financial behaviour of the borrowers for a Bank. I examined the attributes of borrowers, financial measures, credit history, loan characteristics, and repayment results using Python (Pandas, Seaborn, and Scikit-learn).

The results showed that borrowers with worse loan grades, higher debt-to-income ratios, and prior default history had higher default risk. In fact, the default rates were quite high for loans rated D-G, with Grade G exhibiting a default rate of 98.44%, and borrowers who defaulted in the past had almost twice the default rate as borrowers who had not defaulted in the past. There were also strong risk differences for home ownership, with renters defaulting much more than homeowners. However, gender, marital status, education level, country and employment type had little variation in default behaviour. The use of borrower segmentation based on K-Means clustering also distinguished between low-risk, medium-risk and high-risk borrower groups, with financially stressed borrowers more likely to be grouped into high-risk clusters. 

Based on these findings, I proposed to the Bank to improve the credit risk assessment of debt exposure, loan grading and previous default activity, in order to make safer, more informed lending decisions, and to introduce targeted monitoring strategies for high-risk borrower segments to aid risk assessment.



## Business Problem:
A financial institution that offers personal and medical loans, education loans and business loans was always challenged to offer loans that are accessible while effectively managing credit risk. The bank had no idea which borrower types, loan products and financial tendencies were linked to the risk of loan default, and it had no visibility on the volume of borrowers in each of these types. If there is no deeper study of borrower income, debt exposure, credit history, loan grades, and repayment habits, high-risk loans might not be identified, resulting in greater financial losses and reduced lending choices. Meanwhile, strict lending standards may cut off the credit for what otherwise might be sound borrowers. 

What possible ways can borrower and loan information be turned into actionable insights to help the financial institution determine high-risk borrowers, enhance lending decisions and develop more data-driven credit risk strategies that are safer?





## Methodology:
**Environment Setup:** Configured the Python analytical environment using Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn for data analysis, visualization, and borrower segmentation.

**Data Loading and Exploration:** Imported the credit risk dataset and performed initial exploration to understand the dataset structure, feature distributions, data types, and missing values.

**Data Cleaning and Preparation:** Cleaned and prepared the dataset by handling missing values, correcting data types, formatting numerical variables, and creating consistent categorical labels for analysis.

**Univariate and Bivariate Analysis:** Conducted exploratory analysis to examine borrower demographics, loan characteristics, repayment behaviour, and default distributions. Relationships between loan default status and variables such as loan grade, home ownership, loan purpose, debt-to-income ratio, employment type, and previous default history were analysed using statistical summaries and visualizations.

**Feature Engineering:** Created additional analytical variables including borrower risk levels and age group categories to support deeper segmentation and risk analysis.

**Multivariate Analysis and Correlation Assessment:** Performed correlation analysis to identify relationships among financial variables such as income, debt exposure, loan amount, and credit history.

**Borrower Segmentation:** Applied K-Means clustering to group borrowers into distinct financial risk segments based on income, loan amount, and debt-to-income ratio. Principal Component Analysis (PCA) was further used to visualize borrower clusters in two-dimensional space.

**Data Visualization and Storytelling:** Developed professional charts, tables, and cluster visualizations to communicate key insights, default patterns, and borrower risk behaviour in a clear and business-focused manner.


## Skills:
* Exploratory Data Analysis (EDA)
* Credit Risk Analysis
* Business & Data Analysis
* Data Cleaning & Preparation
* Data Visualization & Storytelling
* Statistical & Correlation Analysis
* Borrower Risk Profiling
* Customer Segmentation Analysis
* Feature Engineering
* K-Means Clustering
* Principal Component Analysis (PCA)
* Risk-Based Decision Support
* Financial Data Interpretation
* Insight Generation & Business Recommendations
* Python for Data Analytics
* Pandas, Seaborn, Matplotlib & Scikit-learn
* Analytical Thinking & Problem Solving
