# 💰 Data Science Salary Analysis (2020-2022)

## 📊 Project Overview

A longitudinal analysis of global data science compensation. This project decouples the effects of **geography**, **experience**, and **remote work** to identify the primary drivers of salary.

Using a dataset of 600+ verified records, I performed data cleaning, exploratory analysis, and statistical hypothesis testing (T-Tests, ANOVA) to estimate fair market value in a volatile post-pandemic market.

## 📁 Data Dictionary

The analysis uses a cleaned dataset (`ds_salaries_cleaned.csv`) containing the following key features:

| Column | Description |
| :--- | :--- |
| `work_year` | The year the salary was paid (2020, 2021, 2022). |
| `experience_level` | EN (Entry), MI (Mid), SE (Senior), EX (Executive). |
| `job_title` | Specific role (e.g., Data Scientist, Data Engineer). |
| `salary_in_usd` | The normalized salary converted to USD for comparison. |
| `remote_ratio` | 0 (On-site), 50 (Hybrid), 100 (Remote). |
| `company_location` | The country code of the employer (e.g., US, GB, DE). |

## 🔍 Analysis Performed

* **Data Integrity:** Detected and removed 42 duplicate records; standardized 50+ job titles into 4 core categories (Scientist, Engineer, Analyst, ML).
* **Distribution Analysis:** Analyzed salary spread using histograms and boxplots to detect outliers.
* **Compensation Structure:** Bivariate analysis of Experience vs. Salary and Role vs. Salary.
* **Cohort Analysis:** Tracked year-over-year wage growth and the shift from "Office-First" to "Remote-First" (2020-2022).
* **Statistical Validation:** Used `scipy.stats` to prove significance (P-Values) for the "US Premium" and Remote Work trends.
* **Bias Assessment:** Quantified geographic skew (60% US-based) to ensure transparent reporting.

## 🛠️ Skills Demonstrated

* **Python:** Pandas for complex data manipulation and cleaning.
* **Visualization:** Matplotlib & Seaborn for comparative bar charts and boxplots.
* **Statistical Inference:**
    * **T-Tests:** To compare US vs. Global salaries.
    * **ANOVA:** To compare salaries across Company Sizes (Small vs. Mid vs. Large).
* **Business Intelligence:** Translating raw numbers into actionable career advice.

## 📈 Key Findings

1.  **The "US Premium" is Real:**
    * US-based companies pay **114% more** ($144k vs. $67k) than the global average.
    * *Statistical Significance:* Confirmed (P-Value < 0.05).
2.  **Remote Work is Viable:**
    * There is **no statistical penalty** for working 100% remotely.
    * In 2022, fully remote roles actually showed a higher median salary than hybrid roles.
3.  **The Seniority Leap:**
    * The transition from **Mid-Level** to **Senior** represents the largest financial jump (~40%) in a data career.
4.  **Company Size Matters:**
    * Mid-sized and Large companies pay a premium (~$37k higher) compared to Startups/Small companies.

## 📂 Project Structure

```text
datascience_salary_analysis/
├── data/
│   ├── ds_salaries.csv          # Raw original data
│   └── ds_salaries_cleaned.csv  # Processed data used for analysis
├── notebooks/
│   ├── 1_context_and_question.ipynb
│   ├── 2_data_integrity.ipynb
│   ├── ... (all 7 notebooks)
├── images/                      # Exported visualizations
├── .gitignore                   # Files to exclude from Git
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
```
👨‍💻 Author
Sai Charan

Focus: Data Analysis, Statistical Modeling, Python.

Showcasing end-to-end data science skills for analytical roles.
