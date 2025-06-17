# Fazal Khan | Aspiring Data Analyst

🔍 Transforming complex data into actionable business insights  
📊 Excel | Python | Data Visualization | Analytics

---

## 🚀 Professional Summary

B.Com graduate with a passion for data-driven decision making. Currently developing expertise in data analysis, visualization, and storytelling. Seeking opportunities to apply analytical skills in real-world business contexts.

**Core Competencies:**  
✅ Data Cleaning & Validation  
✅ Exploratory Data Analysis (EDA)  
✅ Business Intelligence Reporting  
✅ Financial Data Interpretation  
✅ Insight Communication

---

## 🧩 Technical Skills

| **Category**       | **Tools & Technologies**                     | **Proficiency**       |
|--------------------|---------------------------------------------|-----------------------|
| **Data Analysis**  | Excel, Google Sheets, Pandas                | ⭐⭐⭐⭐☆               |
| **Visualization**  | Matplotlib, Seaborn, Excel Charts           | ⭐⭐⭐☆☆               |
| **Programming**    | Python (Pandas, NumPy)                      | ⭐⭐☆☆☆               |
| **Databases**      | SQL (Learning)                              | ⭐☆☆☆☆               |
| **Business Tools** | Tally ERP, Financial Modeling               | ⭐⭐⭐⭐☆               |

---

## 📂 Portfolio Projects

### 💼 1. Sales Performance Analysis | Excel
*Comprehensive sales analytics dashboard for retail business*

- **Objective:** Identify top-performing products and sales trends
- **Methodology:**
  - Cleaned dataset with 10K+ records
  - Created dynamic pivot tables
  - Developed product performance scorecards
  - Visualized regional sales distribution
- **Key Insight:** Identified 3 products contributing 42% of total revenue
- **Tools:** Excel (PivotTables, Power Query, Conditional Formatting)

### 📊 1. Sales Performance Analysis — *Excel Project*

🔗 [Download Project File](Sales_Analysis.xlsx)


---

### ⚓ 2. Titanic Survival Analysis | Python
*Exploratory analysis of passenger survival patterns*

- **Objective:** Identify factors influencing survival rates
- **Methodology:**
  - Performed missing data imputation
  - Analyzed survival correlation with demographics
  - Created comparative visualizations
  - Developed predictive model (logistic regression)
- **Key Insight:** Women in 1st class had 92% survival rate vs 15% for men in 3rd class
- **Tools:** Python (Pandas, Matplotlib, Scikit-learn)

```python
# Sample code snippet
import pandas as pd
import matplotlib.pyplot as plt

titanic = pd.read_csv('titanic.csv')
survival_by_class = titanic.groupby('Pclass')['Survived'].mean()
survival_by_class.plot(kind='bar', color='#2563eb')
plt.title('Survival Rate by Passenger Class')
plt.ylabel('Survival Rate');
