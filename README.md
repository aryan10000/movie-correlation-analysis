# Movie Revenue Drivers Analysis

Data analytics project investigating the factors that influence movie box office performance through exploratory analysis, statistical correlation modeling, and data visualization using Python.

## Project Objective

Movie studios invest millions of dollars into production and marketing, yet predicting commercial success remains a major challenge.

This project analyzes historical movie data to identify which factors have the strongest relationship with box office revenue and evaluate whether variables such as budget, audience engagement, ratings, release year, and production companies significantly impact financial performance.

---

## Budget vs Revenue Analysis

<img width="839" height="556" alt="Budget vs Revenue Regression" src="https://github.com/user-attachments/assets/2386c18e-d1a1-4c07-8381-63e64c1746f8" />


### Observation

A strong positive relationship exists between production budget and gross revenue, indicating that higher-budget films generally generate greater box office returns.

---

## Correlation Analysis

<img width="877" height="618" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/30699972-5abd-4d2f-b398-82d8e3129980" />


### Observation

The correlation matrix reveals that budget and audience votes exhibit the strongest positive relationships with gross revenue, while several commonly assumed factors show relatively weak predictive power.

---

## Business Questions

- Does a larger production budget lead to higher revenue?
- Which variables are most strongly associated with box office success?
- Do audience ratings influence financial performance?
- How important are audience votes and engagement metrics?
- Which factors provide the strongest indicators of revenue generation?

---

## Dataset

**Source:** Kaggle Movies Dataset

https://www.kaggle.com/datasets/danielgrijalvas/movies

The dataset contains information on:

- Budget
- Gross Revenue
- Votes
- Ratings
- Genres
- Production Companies
- Release Year
- Runtime
- Country

---

## Analytics Workflow

### Data Preparation

- Missing value analysis
- Null value treatment
- Data type conversion
- Release year extraction
- Dataset standardization

### Exploratory Data Analysis

- Budget vs Gross Revenue analysis
- Votes vs Revenue analysis
- Ratings vs Revenue analysis
- Trend and distribution analysis

### Correlation Modeling

- Pearson Correlation Analysis
- Correlation Matrix Construction
- Heatmap Visualization
- Feature Relationship Evaluation

---

## Key Findings

### Budget is the Strongest Revenue Driver

Production budget demonstrated the highest positive correlation with gross revenue, making it the strongest indicator of commercial success.

### Audience Engagement Matters

Vote count showed a meaningful relationship with revenue, suggesting that audience interest and visibility contribute significantly to financial performance.

### Ratings Have Limited Predictive Power

While highly rated movies can perform well, ratings alone were less correlated with revenue than budget and audience engagement metrics.

### Not All Assumptions Hold

Several variables commonly believed to influence movie success displayed relatively weak relationships with revenue generation.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Statistical Reasoning
- Data Visualization
- Feature Engineering
- Business Insight Generation

---

## Project Outcome

Developed a data-driven framework for evaluating movie success factors and identifying the variables most strongly associated with box office performance. The analysis demonstrates how statistical exploration and correlation modeling can support investment and decision-making within the entertainment industry.

---

## Author

Aryan Soni

Data Analytics | SQL | PostgreSQL | Python | Tableau
