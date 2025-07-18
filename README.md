Youth Tobacco Use Data Analysis

This project analyzes youth tobacco usage patterns to uncover trends, correlations, and risk factors. The aim is to support public health strategies by identifying key drivers of tobacco use among young individuals using statistical and machine learning techniques.

Objective
	•	Analyze tobacco use behaviors among youth populations
	•	Explore how factors like peer influence, parental smoking, and socioeconomic status impact usage
	•	Use statistical and predictive modeling to better understand risk groups and patterns
	•	Present findings through clean and accessible visualizations for public health insights

Dataset Overview

The dataset includes records on youth tobacco usage along with demographic and behavioral variables:
	•	ID: Unique identifier
	•	Age: Age of the individual
	•	Gender: Male / Female / Other
	•	Region: Geographic location
	•	Tobacco_Use: Type and frequency of tobacco use
	•	Socioeconomic_Status: Categorical indicator of income or education background
	•	Parental_Smoking: Whether parents/guardians smoke
	•	Peer_Influence: Influence of peer group on tobacco use
	•	Health_Status: Self-reported health condition

Project Workflow

Data Collection and Preprocessing:
	•	Gathered youth tobacco use data from public sources
	•	Cleaned missing values, standardized categories, and encoded categorical features
	•	Verified data quality and filtered out noisy entries

Exploratory Data Analysis (EDA):
	•	Analyzed distribution of tobacco use by age, gender, and region
	•	Identified patterns in usage based on parental smoking and peer influence
	•	Used correlation heatmaps to understand variable relationships

Statistical Analysis:
	•	Examined relationships between tobacco use and socioeconomic/health factors
	•	Used chi-square tests, ANOVA, and correlation coefficients for deeper insights

Predictive Modeling:
	•	Built classification models to predict likelihood of tobacco use
	•	Applied logistic regression, decision trees, and random forest (if applicable)
	•	Evaluated model performance using accuracy, precision, recall, and F1-score

Data Visualization:
	•	Bar charts and histograms for demographics
	•	Heatmaps for correlation
	•	Stacked plots showing usage by peer and parental influence

Results and Insights
	•	Higher tobacco use observed among certain age groups and regions
	•	Strong correlation found between peer influence and usage patterns
	•	Socioeconomic and parental habits showed moderate predictive power
	•	Predictive models achieved promising accuracy in identifying at-risk youth

Tools and Technologies
	•	Programming Language: Python
	•	Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
	•	Development Environment: Jupyter Notebook, GitHub

Future Improvements
	•	Add time-series data to observe trends across years
	•	Collect more granular data on types of tobacco products
	•	Deploy an interactive dashboard using Streamlit for public health teams

