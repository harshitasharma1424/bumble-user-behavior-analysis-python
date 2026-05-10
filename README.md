# Bumble User Behavior Analysis using Python

## Project Overview
This project performs Exploratory Data Analysis (EDA) on Bumble user profile data to uncover insights about user demographics, lifestyle patterns, income behavior, engagement trends, and profile completeness.

The analysis focuses on:
- Data Cleaning & Missing Value Handling
- Outlier Detection & Treatment
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insights & Recommendations

> This project is created for educational and portfolio demonstration purposes using a public-style dataset.

---

## Dataset Information
The dataset contains Bumble user profile information including:
- Age
- Gender
- Relationship Status
- Height
- Income
- Education
- Diet Preferences
- Drinking Habits
- Location
- Pets Preferences
- Zodiac Signs
- Last Online Activity

---

## Project Structure

```bash
bumble-user-behavior-analysis-python/
├── dataset/
│   └── bumble_profiles.csv
├── notebook/
│   └── bumble_user_behavior_analysis.ipynb
├── screenshots/
├── README.md
└── requirements.txt
```

---

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Analysis Performed

### 1. Data Cleaning
- Identified missing values across columns
- Replaced invalid income values (-1) with NaN
- Handled missing numerical values using median imputation
- Corrected inconsistent data types
- Visualized missing data patterns using heatmaps

### 2. Outlier Detection & Treatment
- Analyzed outliers in age, income, and height
- Used statistical summaries and visual inspection
- Retained meaningful records while reducing skew impact

### 3. Feature Engineering
Created new features such as:
- `age_group`
- `income_tier`
- `profile_completeness`
- `height_cm`

### 4. Exploratory Data Analysis
Performed analysis on:
- Gender distribution
- Relationship status trends
- Diet & drinking habits
- Geographic distribution
- Pets & zodiac preferences
- Height and income behavior
- Correlation between numerical variables

### 5. Data Visualization
Created:
- Histograms
- Heatmaps
- Scatterplots
- Boxplots
- Bar Charts
- Correlation Charts

---

## Key Insights
- Most users belong to the younger adult age segment.
- Social drinking was the most common drinking behavior.
- Income generally increased with age.
- Male users were more dominant on the platform.
- Certain cities had significantly higher user activity.
- Users with more complete profiles appeared more engaged.

---

## Business Recommendations
1. Encourage profile completion using gamification or onboarding prompts.
2. Improve matchmaking algorithms using lifestyle compatibility features.
3. Create city-specific engagement campaigns based on user density.
4. Use demographic segmentation for premium targeting.
5. Introduce personalized recommendations using behavioral trends.

---

## Screenshots

### Missing Values Heatmap
![Missing Values](screenshots/missing_values_heatmap.png)

### Gender Distribution
![Gender Distribution](screenshots/gender_distribution.png)

### Income vs Age
![Income vs Age](screenshots/income_vs_age.png)

### Correlation Heatmap
![Correlation Heatmap](screenshots/correlation_heatmap.png)

---

## How to Run the Project

### Clone Repository

```bash
git clone https://github.com/your-username/bumble-user-behavior-analysis-python.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Open Jupyter Notebook

```bash
jupyter notebook
```

Open:
`notebook/bumble_user_behavior_analysis.ipynb`

Run all cells to reproduce the analysis and visualizations.

---

## Requirements

```txt
pandas
numpy
matplotlib
seaborn
jupyter
scikit-learn
```

---

## Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering
- Statistical Analysis
- Data Visualization
- Business Insight Generation
- Python Programming

---

## Future Improvements
- Build interactive dashboards using Power BI or Tableau
- Deploy insights using Streamlit
- Add predictive modeling for engagement analysis

---

## Author

### Harshita Sharma

- LinkedIn: https://www.linkedin.com/in/harshitasharma1424
- Tableau: https://public.tableau.com/app/profile/harshita.sharma1388
