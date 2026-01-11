📊 Indian Employment & AI Risk Analysis (2023-2028)
📌 Project Overview
This project provides a comprehensive data analysis of the Indian job market, focusing on salary trends, employment stability, and the perceived risk of AI automation. Starting with a "messy" raw dataset, I performed extensive data cleaning and feature engineering to uncover strategic insights regarding geography, education, and career experience.

🎯 Key Questions Answered:
How does the "Metro Premium" affect monthly salaries in India?

Which industries are most susceptible to AI disruption?

At what age/experience level do Indian professionals reach their peak earning potential?

How does education level correlate with employment status?

🛠️ Tech Stack & Tools
Language: Python 3.x

Libraries: * Pandas (Data Manipulation)

Numpy (Numerical Analysis)

Matplotlib & Seaborn (Advanced Data Visualization)

Environment: Jupyter Notebook / Google Colab

Next Steps: Data is ready for export to Power BI / Tableau.

📈 Analysis & Visualizations
The analysis includes 8 distinct visualization scenarios to provide a 360-degree view of the dataset:

Income Distribution: A solid pie chart representing the share of High, Mid, and Low-income tiers.

Industry Variance: Boxplots showing salary ranges across Tech, Healthcare, Finance, and Retail.

AI Exposure: A stacked bar chart visualizing risk levels by sector.

Career Progression: Bar charts showing the average salary jump from Fresher to Senior levels.

Generational Heatmap: Identifying which age groups feel most threatened by AI.

Market Density: Violin plots showing salary concentration across different age demographics.

Geographic Stability: Comparing employment rates in Metro vs. Non-Metro cities.

🧹 Data Engineering Highlights
To prepare the "Messy" dataset for analysis, I implemented the following:

Standardization: Unified inconsistent naming (e.g., 'Master' vs 'Masters' → 'Postgraduate').

Handling Nulls: Applied logical imputation for missing experience and salary data.

Feature Engineering: * Created LPA (Lakhs Per Annum) for local market relevance.

Created Is_Metro flag for geographic deep-dives.

Derived Salary_Tier and Experience_Level for categorical grouping.

Time Intelligence: Extracted Month/Year from varied date formats for trend analysis.

🚀 Key Insights (Executive Summary)
The Education Gatekeeper: Postgraduate degrees are the strongest predictors for entering the "High Income" bracket.

Metro Hub Advantage: Professionals in Tier-1 cities (Bangalore, Mumbai, Delhi, Hyderabad) enjoy a significantly higher employment-to-unemployment ratio.

The AI Paradox: High-paying Tech and Finance roles report the highest AI risk, suggesting a trade-off between salary and future job security.

Seniority Surge: A massive salary growth spike is observed after the 10-year experience mark.

📂 Project Structure
Plaintext

├── Data/
│   ├── Messy_Employment_India_Dataset.csv   # Original raw data
│   └── Cleaned_Employment_India_Data.csv    # Final processed data
├── Notebooks/
│   └── Employment_Analysis_India.ipynb      # Complete Python code & visualizations
└── README.md                                # Project documentation
📬 Contact & Feedback
If you have any questions or want to discuss the findings, feel free to reach out!

Author: [Your Name]

LinkedIn: [Your LinkedIn Link]

