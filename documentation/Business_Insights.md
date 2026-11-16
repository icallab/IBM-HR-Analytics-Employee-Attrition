# IBM HR Analytics – Business Insights

## 1. Project Overview

This document presents the key business insights derived from the exploratory data analysis (EDA) of the IBM HR Analytics Employee Attrition & Performance dataset.

The analysis focuses on identifying employee attrition patterns, understanding the characteristics associated with employees leaving the company, and highlighting areas that require attention from Human Resources (HR) management.

The objective is to transform employee data into meaningful insights that can support data-driven HR decisions and employee retention strategies.

## 2. Dataset Overview

The dataset contains employee information covering demographic characteristics, job roles, compensation, job satisfaction, work experience, and attrition status.

| Description | Value |
|---|---:|
| Total Employees | 1,470 |
| Total Columns | 35 |
| Attrition Count | 237 |
| Active Employees | 1,233 |
| Attrition Rate | 16.12% |

## 3. Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Employees | 1,470 |
| Employees Who Left | 237 |
| Active Employees | 1,233 |
| Attrition Rate | 16.12% |
| Average Age | 36.92 |
| Average Monthly Income | 6,502.93 |

The company recorded an overall attrition rate of 16.12%, meaning approximately 16 out of every 100 employees left the organization.

## 4. Key Business Insights

### 4.1 Attrition by Age Group

Employees under 25 have the highest attrition rate.

| Age Group | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| Under 25 | 97 | 38 | 39.18% |
| 25–34 | 554 | 112 | 20.22% |
| 35–44 | 505 | 51 | 10.10% |
| 45–54 | 245 | 25 | 10.20% |
| 55+ | 69 | 11 | 15.94% |

**Business Insight:**

- Employees under 25 have the highest attrition rate at 39.18%.
- The 25–34 age group contributes the largest number of attrition cases, with 112 employees.
- Attrition rates are considerably lower among employees aged 35–54.

This suggests that younger employees and early-career workers may require greater attention through onboarding, career development, and retention initiatives.

### 4.2 Attrition by Job Role

| Job Role | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| Healthcare Representative | 131 | 9 | 6.87% |
| Human Resources | 52 | 12 | 23.08% |
| Laboratory Technician | 259 | 62 | 23.94% |
| Manager | 102 | 5 | 4.90% |
| Manufacturing Director | 145 | 10 | 6.90% |
| Research Director | 80 | 2 | 2.50% |
| Research Scientist | 292 | 47 | 16.10% |
| Sales Executive | 326 | 57 | 17.48% |
| Sales Representative | 83 | 33 | 39.76% |

**Business Insight:**

- Sales Representatives have the highest attrition rate at 39.76%.
- Laboratory Technicians contribute the highest attrition count, with 62 employees.
- Research Directors have the lowest attrition rate at 2.50%.

The results indicate that Sales Representatives and Laboratory Technicians should be prioritized for further HR investigation.

### 4.3 Attrition by Department

| Department | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| Sales | 446 | 92 | 20.63% |
| Research & Development | 961 | 133 | 13.84% |
| Human Resources | 63 | 12 | 19.05% |

**Business Insight:**

- Sales has the highest departmental attrition rate at 20.63%.
- Research & Development contributes the largest number of attrition cases, with 133 employees.
- Human Resources has an attrition rate of 19.05%, although its employee population is relatively small.

Sales requires particular attention because it has both a relatively high attrition rate and a substantial number of departing employees.

### 4.4 Attrition by Business Travel

| Business Travel | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| Non-Travel | 150 | 12 | 8.00% |
| Travel_Frequently | 277 | 69 | 24.91% |
| Travel_Rarely | 1,043 | 156 | 14.96% |

**Business Insight:**

- Employees who travel frequently have the highest attrition rate at 24.91%.
- Non-travel employees have the lowest attrition rate at 8.00%.
- Frequent business travel may be associated with additional work demands and reduced work-life balance.

### 4.5 Attrition by Overtime

| OverTime | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| No | 1,054 | 110 | 10.44% |
| Yes | 416 | 127 | 30.53% |

**Business Insight:**

- Employees working overtime have an attrition rate of 30.53%.
- This is substantially higher than the 10.44% observed among employees who do not work overtime.
- Overtime employees account for 127 of the 237 attrition cases.

Overtime is one of the most notable factors associated with employee attrition in this analysis.

### 4.6 Attrition by Job Involvement

| Job Involvement | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| 1 – Low | 83 | 28 | 33.73% |
| 2 – Medium | 375 | 71 | 18.93% |
| 3 – High | 868 | 125 | 14.40% |
| 4 – Very High | 144 | 13 | 9.03% |

**Business Insight:**

- Employees with low job involvement have the highest attrition rate at 33.73%.
- Employees with very high job involvement have the lowest attrition rate at 9.03%.
- Attrition rates decrease as job involvement increases across these categories.

This pattern highlights the importance of employee engagement and involvement in the workplace.

### 4.7 Attrition by Job Satisfaction

| Job Satisfaction | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| 1 – Low | 289 | 66 | 22.84% |
| 2 – Medium | 280 | 46 | 16.43% |
| 3 – High | 442 | 73 | 16.52% |
| 4 – Very High | 459 | 52 | 11.33% |

**Business Insight:**

- Employees with low job satisfaction have the highest attrition rate at 22.84%.
- Employees with very high job satisfaction have the lowest rate at 11.33%.
- Improving employee satisfaction may be an important area for HR retention initiatives.

### 4.8 Attrition by Environment Satisfaction

| Environment Satisfaction | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| 1 – Low | 284 | 72 | 25.35% |
| 2 – Medium | 287 | 43 | 14.98% |
| 3 – High | 453 | 62 | 13.69% |
| 4 – Very High | 446 | 60 | 13.45% |

**Business Insight:**

- Employees with low environment satisfaction have the highest attrition rate at 25.35%.
- The very high satisfaction group has the lowest rate at 13.45%.
- Workplace environment is an important area to investigate when evaluating employee retention.

### 4.9 Attrition by Work-Life Balance

| Work-Life Balance | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| 1 – Bad | 80 | 25 | 31.25% |
| 2 – Good | 344 | 58 | 16.86% |
| 3 – Better | 893 | 127 | 14.22% |
| 4 – Best | 153 | 27 | 17.65% |

**Business Insight:**

- Employees reporting bad work-life balance have the highest attrition rate at 31.25%.
- The Better category has the lowest attrition rate at 14.22%.
- The Best category has a higher attrition rate than the Better category, indicating that the relationship is not strictly linear.

Employees reporting poor work-life balance should receive additional attention.

### 4.10 Attrition by Years at Company

| Years at Company | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| 0–2 Years | 342 | 102 | 29.82% |
| 3–5 Years | 434 | 60 | 13.82% |
| 6–10 Years | 448 | 55 | 12.28% |
| 11–20 Years | 180 | 12 | 6.67% |
| 21+ Years | 66 | 8 | 12.12% |

**Business Insight:**

- Employees with 0–2 years of tenure have the highest attrition rate at 29.82%.
- Attrition decreases considerably among employees with longer tenure.
- The first years of employment appear to be an important period for retention efforts.

### 4.11 Attrition by Distance from Home

| Distance from Home | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| 0–5 Miles | 632 | 87 | 13.77% |
| 6–10 Miles | 394 | 57 | 14.47% |
| 11–20 Miles | 240 | 48 | 20.00% |
| 21+ Miles | 204 | 45 | 22.06% |

**Business Insight:**

- Employees living 21+ miles from work have the highest attrition rate at 22.06%.
- Employees living within 0–5 miles have the lowest rate at 13.77%.
- Attrition rates generally increase across the distance groups.

Commute-related challenges may be worth investigating, particularly for employees living farther from the workplace.

### 4.12 Attrition by Monthly Income

| Monthly Income Group | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| Below 3000 | 395 | 113 | 28.61% |
| 3000–4999 | 354 | 50 | 14.12% |
| 5000–6999 | 286 | 27 | 9.44% |
| 7000–9999 | 154 | 22 | 14.29% |
| 10000+ | 281 | 25 | 8.90% |

**Business Insight:**

- Employees earning below 3,000 have the highest attrition rate at 28.61%.
- Employees earning 10,000 or more have the lowest rate at 8.90%.
- The below-3,000 group also contributes the largest number of attrition cases, with 113 employees.

Compensation should be reviewed as part of a broader employee retention strategy.

### 4.13 Attrition by Stock Option Level

| Stock Option Level | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| 0 | 631 | 154 | 24.41% |
| 1 | 596 | 56 | 9.40% |
| 2 | 158 | 12 | 7.59% |
| 3 | 85 | 15 | 17.65% |

**Business Insight:**

- Employees with Stock Option Level 0 have the highest attrition rate at 24.41%.
- Employees with Stock Option Level 2 have the lowest rate at 7.59%.
- The pattern is not linear, as attrition increases again at Level 3.

This suggests that employee benefits and stock option participation may deserve further investigation.

### 4.14 Attrition by Job Level

| Job Level | Employees | Attrition | Attrition Rate |
|---|---:|---:|---:|
| 1 | 543 | 143 | 26.34% |
| 2 | 534 | 52 | 9.74% |
| 3 | 218 | 32 | 14.68% |
| 4 | 106 | 5 | 4.72% |
| 5 | 69 | 5 | 7.25% |

**Business Insight:**

- Job Level 1 has the highest attrition rate at 26.34%.
- Job Level 1 also contributes the highest attrition count, with 143 employees.
- Job Level 4 has the lowest attrition rate at 4.72%.

Employees in entry-level positions may benefit from stronger career development and retention support.

### 4.15 Attrition by Department and Job Level

The combined analysis reveals differences across departments and job levels.

**Key Findings:**

- Sales – Job Level 1 has the highest attrition rate at 42.11%.
- Research & Development – Job Level 1 has an attrition rate of 23.27%.
- Human Resources – Job Level 3 has an attrition rate of 33.33%, although the group contains only six employees.
- Sales – Job Level 1 contributes 32 attrition cases.

The results indicate that retention challenges may vary across organizational departments and job levels.

### 4.16 Attrition vs. Active Employee Comparison

The average characteristics of employees who left the company were compared with those who remained.

| Metric | Attrition (Yes) | Active (No) | Difference |
|---|---:|---:|---:|
| Average Age | 33.61 | 37.56 | -3.95 |
| Average Monthly Income | 4,787.09 | 6,832.74 | -2,045.65 |
| Average Total Working Years | 8.24 | 11.86 | -3.62 |
| Average Years at Company | 5.13 | 7.37 | -2.24 |
| Average Years in Current Role | 2.90 | 4.48 | -1.58 |
| Average Years with Current Manager | 2.85 | 4.37 | -1.52 |
| Average Distance from Home | 10.63 | 8.92 | +1.72 |

**Business Insight:**

- Employees who left were younger on average than active employees.
- Employees who left had lower average monthly income.
- Employees who left had shorter total work experience and company tenure.
- Employees who left spent less time in their current roles and under their current managers.
- Employees who left lived farther from work on average.

These differences provide a useful overview of employee characteristics associated with attrition.

## 5. Overall Key Findings

Based on the analysis, the following findings deserve particular attention:

| Priority Area | Key Finding |
|---|---|
| Age | Employees under 25 have a 39.18% attrition rate. |
| Job Role | Sales Representatives have a 39.76% attrition rate. |
| Department | Sales has the highest departmental attrition rate at 20.63%. |
| Overtime | Employees working overtime have a 30.53% attrition rate. |
| Job Involvement | Low involvement is associated with a 33.73% attrition rate. |
| Work-Life Balance | Employees reporting bad work-life balance have a 31.25% attrition rate. |
| Tenure | Employees with 0–2 years at the company have a 29.82% attrition rate. |
| Compensation | Employees earning below 3,000 have a 28.61% attrition rate. |
| Job Level | Job Level 1 has a 26.34% attrition rate. |

## 6. Conclusion

The analysis identifies several employee groups with comparatively high attrition rates, particularly younger employees, Sales Representatives, employees working overtime, employees with low job involvement, and employees with shorter company tenure.

Compensation, job satisfaction, work-life balance, business travel, and workplace experience also show meaningful differences across attrition groups.

These findings can help HR management identify priority areas for further investigation and develop more targeted employee retention initiatives.

However, this analysis is descriptive and does not establish causal relationships. Additional investigation, including multivariable analysis and employee feedback, would be necessary to understand the underlying reasons for attrition.

---

**Project:** IBM HR Analytics – Employee Attrition & Performance

**Analysis Focus:** Exploratory Data Analysis, Employee Attrition Patterns, and HR Business Insights

**Dataset Size:** 1,470 Employees

**Overall Attrition Rate:** 16.12%