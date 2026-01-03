\# 💰 Data Science Salary Analysis (2020-2022)



\## 📊 Project Overview



A longitudinal analysis of global data science compensation. This project decouples the effects of \*\*geography\*\*, \*\*experience\*\*, and \*\*remote work\*\* to identify the primary drivers of salary.



Using a dataset of 600+ verified records, I performed data cleaning, exploratory analysis, and statistical hypothesis testing (T-Tests, ANOVA) to estimate fair market value in a volatile post-pandemic market.



\## 📁 Data Dictionary



The analysis uses a cleaned dataset (`ds\_salaries\_cleaned.csv`) containing the following key features:



| Column | Description |

| :--- | :--- |

| `work\_year` | The year the salary was paid (2020, 2021, 2022). |

| `experience\_level` | EN (Entry), MI (Mid), SE (Senior), EX (Executive). |

| `job\_title` | Specific role (e.g., Data Scientist, Data Engineer). |

| `salary\_in\_usd` | The normalized salary converted to USD for comparison. |

| `remote\_ratio` | 0 (On-site), 50 (Hybrid), 100 (Remote). |

| `company\_location` | The country code of the employer (e.g., US, GB, DE). |



\## 🔍 Analysis Performed



\* \*\*Data Integrity:\*\* Detected and removed 42 duplicate records; standardized 50+ job titles into 4 core categories (Scientist, Engineer, Analyst, ML).

\* \*\*Distribution Analysis:\*\* Analyzed salary spread using histograms and boxplots to detect outliers.

\* \*\*Compensation Structure:\*\* Bivariate analysis of Experience vs. Salary and Role vs. Salary.

\* \*\*Cohort Analysis:\*\* Tracked year-over-year wage growth and the shift from "Office-First" to "Remote-First" (2020-2022).

\* \*\*Statistical Validation:\*\* Used `scipy.stats` to prove significance (P-Values) for the "US Premium" and Remote Work trends.

\* \*\*Bias Assessment:\*\* Quantified geographic skew (60% US-based) to ensure transparent reporting.



\## 🛠️ Skills Demonstrated



\* \*\*Python:\*\* Pandas for complex data manipulation and cleaning.

\* \*\*Visualization:\*\* Matplotlib \& Seaborn for comparative bar charts and boxplots.

\* \*\*Statistical Inference:\*\*

&nbsp;   \* \*\*T-Tests:\*\* To compare US vs. Global salaries.

&nbsp;   \* \*\*ANOVA:\*\* To compare salaries across Company Sizes (Small vs. Mid vs. Large).

\* \*\*Business Intelligence:\*\* Translating raw numbers into actionable career advice.



\## 📈 Key Findings



1\.  \*\*The "US Premium" is Real:\*\*

&nbsp;   \* US-based companies pay \*\*114% more\*\* ($144k vs. $67k) than the global average.

&nbsp;   \* \*Statistical Significance:\* Confirmed (P-Value < 0.05).

2\.  \*\*Remote Work is Viable:\*\*

&nbsp;   \* There is \*\*no statistical penalty\*\* for working 100% remotely.

&nbsp;   \* In 2022, fully remote roles actually showed a higher median salary than hybrid roles.

3\.  \*\*The Seniority Leap:\*\*

&nbsp;   \* The transition from \*\*Mid-Level\*\* to \*\*Senior\*\* represents the largest financial jump (~40%) in a data career.

4\.  \*\*Company Size Matters:\*\*

&nbsp;   \* Mid-sized and Large companies pay a premium (~$37k higher) compared to Startups/Small companies.



\## 📂 Project Structure





ds-salary-analysis/

├── data/

│   ├── ds\_salaries.csv          # Raw original data

│   └── ds\_salaries\_cleaned.csv  # Processed data used for analysis

├── notebooks/

│   ├── 1\_context\_and\_question.ipynb

│   ├── 2\_data\_integrity.ipynb

│   ├── 3\_distribution\_science.ipynb

│   ├── 4\_compensation\_structure.ipynb

│   ├── 5\_cohort\_analysis.ipynb

│   ├── 6\_statistical\_validation.ipynb

│   └── 7\_bias\_and\_limits.ipynb

├── images/                      # Exported visualizations for this README

├── requirements.txt             # Python dependencies

└── README.md                    # Project documentation







👨‍💻 Author

Sai Charan



Focus: Data Analysis, Statistical Modeling, Python.



Showcasing end-to-end data science skills for analytical roles.

