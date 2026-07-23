# 📊 SearaBank Talent Recruitment Analysis

> **Disclaimer**  
> The company name **SearaBank** and the associated business scenario used in this project are entirely fictional and created for educational purposes as part of a structured case study. Any resemblance to actual companies, institutions, or datasets is purely coincidental.

---

# 📌 Project Overview

Recruitment is one of the most critical processes in a rapidly growing digital bank. As hiring demand increases, manual resume screening becomes inefficient and makes it difficult for HR teams to identify candidates who match specific technical requirements.

This project analyzes recruitment data from **SearaBank**, a fictional digital banking company, to build a **data-driven recruitment dashboard** that helps HR identify qualified candidates based on technical skills, experience level, recruitment channels, and geographic distribution.

The project covers the complete analytics workflow, including:

- Data cleaning
- Data transformation
- Exploratory Data Analysis (EDA)
- Interactive dashboard development

---

# 🎯 Business Problem

SearaBank plans to expand its workforce in 2026 to support the growth of its flagship products:

- Seara Hub Pockets
- Seara Smart-PayLater

However, the HR team faces several challenges:

- Manual resume screening is time-consuming.
- Candidate skills are difficult to compare objectively.
- Recruitment decisions are not yet fully data-driven.
- Talent distribution across BI tools and programming skills is unclear.

### Recruitment Requirements

| Position | Headcount | Required Skills |
|-----------|----------:|----------------|
| Senior Credit Risk Analyst | 1 | SQL, Python |
| Junior Data Analyst (PayLater) | 1 | Excel + BI Tools |
| Junior Data Analyst (Pockets) | 2 | Excel + BI Tools |

---

# 🎯 Project Objectives

This project aims to:

- Analyze candidate technical competencies.
- Map candidate readiness for Junior and Senior Data Analyst positions.
- Compare Fresh Graduate and Experienced candidate capabilities.
- Analyze recruitment sources and candidate demographics.
- Support HR with data-driven recruitment recommendations.

---

# ❓ Business Questions

- Which BI platform has the largest pool of qualified Junior candidates?
- Are Fresh Graduates competitive with Experienced candidates in SQL and Python?
- Which recruitment channel contributes the most applicants?
- How are candidates distributed geographically?
- Which candidate segments best fit Junior and Senior roles?

---

# 🛠 Tech Stack

| Category | Tools |
|----------|-------|
| Data Cleaning | Google Sheets |
| Data Transformation | Google Sheets |
| Data Visualization | Looker Studio |

---

# 🔄 Project Workflow

## 1. Data Cleaning

- Replaced missing values with "-"
- Removed duplicate records
- Standardized text formatting
- Grouped candidate locations into provinces

---

## 2. Data Transformation

Performed feature engineering by transforming multi-response text fields into structured boolean features.

Techniques used:

- `IF`
- `REGEXMATCH`
- `REGEXREPLACE`
- `VLOOKUP`

---

## 3. Exploratory Data Analysis

Analyzed:

- Candidate demographics
- Technical skills
- Recruitment channels
- Candidate motivations
- Geographic distribution

---

## 4. Dashboard Development

Built an interactive recruitment dashboard in **Looker Studio** to support data-driven hiring decisions.

---

# 📈 Project Results

## Candidate Overview

- Total Candidates: **681**
- Fresh Graduates: **386 (56.7%)**
- Experienced: **295 (43.3%)**

---

## Technical Skills

Most common technical skills:

| Skill | Candidates |
|--------|-----------:|
| SQL | 561 |
| Python | 546 |
| Excel | 527 |

### BI Tools

| BI Tool | Candidates |
|---------|-----------:|
| Power BI | 516 |
| Tableau | 446 |
| Looker Studio | 401 |

---

## Recruitment Sources

- **80.6%** of applicants came from **LinkedIn**, making it the most effective recruitment channel.

---

## Geographic Distribution

Most applicants are concentrated in:

- West Java
- DKI Jakarta
- East Java
- Central Java

---

# 💡 Key Insights

### 1. Strong Fresh Graduate Talent Pool

Fresh Graduates account for more than half of all applicants (56.7%), indicating a highly competitive entry-level talent market.

---

### 2. SQL & Python are Highly Common

SQL and Python are the two most frequently mastered technical skills among applicants.

Interestingly, around **300 Fresh Graduates** already satisfy the initial SQL & Python requirements for Senior-level screening.

---

### 3. Tableau Dominates Junior Candidate Skills

Among candidates meeting Junior Analyst requirements:

- Excel + Tableau dominates (224 candidates)
- Excel + Power BI is significantly smaller
- Excel + Looker Studio has the smallest talent pool

---

### 4. LinkedIn is the Primary Recruitment Channel

More than 80% of applicants were sourced from LinkedIn, highlighting its effectiveness for digital talent acquisition.

---

# 📊 Business Recommendations

## Junior Data Analyst Recruitment

- Prioritize candidates with **Excel + Tableau** since they represent the largest qualified talent pool.
- Fast-track candidates with **Power BI** and **Looker Studio** due to limited availability.

---

## Senior Credit Risk Analyst Recruitment

- Use **SQL** and **Python** as primary screening criteria.
- Although many Fresh Graduates meet technical requirements, prioritize Experienced candidates during final interviews because the role requires stronger business context and risk management experience.

---

## Talent Pipeline Strategy

- Develop a Senior Talent Pipeline by nurturing high-performing Fresh Graduates.
- Expand sourcing efforts beyond LinkedIn to diversify candidate acquisition channels.

---

# 📌 Dashboard
Link Dashboard: https://datastudio.google.com/u/0/reporting/b6b04004-0200-402a-b2f9-415cabace185/page/p_s5x9015o4d?s=uH3xsgE7EyQ
> <img width="1875" height="1407" alt="SearaBank-Talent-Recruitment-Dashboard-2026" src="https://github.com/user-attachments/assets/c92ddea1-e99e-4609-9409-7cb4bdb5cf15" />



---

