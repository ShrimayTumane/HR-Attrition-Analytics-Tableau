# 📊 HR Attrition Analytics Dashboard

![Dashboard Preview](dashboard.png)

## 🔗 Live Dashboard
**[View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/shrimay.tumane/viz/HRAttritionAnalyticsDashboardbyShrimayTumane/HRAnalyticsDashboard)**

---

## 📌 Project Overview
An interactive HR analytics dashboard analyzing employee attrition 
patterns across 1,470 employees using the IBM HR Analytics Dataset. 
Built to help HR teams identify key drivers of employee turnover 
and take data-driven retention decisions.

---

## 🔍 Key Insights
- **Sales Representatives** have the highest attrition rate at **39.8%**
- Employees working **overtime are 3× more likely** to leave
- Employees **under 25** experience the highest turnover (**39.2%**)
- **Lower-income employees** show significantly higher attrition
- **Sales department** records the highest departmental attrition (**20.6%**)

---

## 📈 Dashboard Features
- **5 KPI Cards** — Total Employees, Attrition Rate, Avg Age, 
  Avg Income, Avg Tenure
- **Attrition by Job Role** — Sorted bar chart with above/below 
  average color encoding
- **Department Attrition Rate** — Comparative horizontal bars
- **Monthly Income Distribution** — Box-and-whisker plot by 
  attrition status
- **Income vs Tenure Scatter Plot** — Relationship between 
  compensation, tenure, and attrition
- **Attrition by Age Group** — Demographic breakdown
- **Executive Insights Panel** — Key findings summary
- **Interactive Filters** — Department, Gender, Job Role dropdowns 
  with Reset button

---

## 🛠️ Tools & Techniques
| Tool | Usage |
|------|-------|
| Tableau Desktop | Dashboard development |
| Calculated Fields | Attrition Flag, Attrition Rate, Age Groups |
| Table Calculations | WINDOW_AVG for above/below average color logic |
| Box-and-Whisker Plot | Income distribution analysis |
| Dashboard Actions | Filter actions for full interactivity |

---

## 📂 Dataset
- **Source:** IBM HR Analytics Employee Attrition & Performance Dataset
- **Records:** 1,470 employees
- **Features:** 35 columns including Age, Department, Job Role, 
  Monthly Income, Attrition, OverTime, Years at Company

---

## 🎨 Design Decisions
- Dark navy theme (`#0D1B2A`) for professional appearance
- **Orange (`#F28E2B`)** = above average attrition (high risk)
- **Blue (`#4E79A7`)** = below average attrition (safe)
- Color encodes meaning, not decoration

---

*Dashboard by Shrimay Tumane | 
[Tableau Public Profile](https://public.tableau.com/app/profile/shrimay.tumane)*
