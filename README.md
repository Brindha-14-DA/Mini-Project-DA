# 📊 UK Educational Institutions Inspection & Analytics Portal

## 🚀 **1. Project Overview**

This project transforms and analyses UK Educational Institution inspection data sourced from the UK government. The aim is to provide a clear, interactive **Power BI dashboard** that highlights inspection trends, provider performance, and regional variations.

---

## 📂 **2. Data Source**

**Source:** Gov.uk
**Dataset:** Management information – further education and skills (2010–2025)
**Domain:** Education (Further Education & Skills)

---

## ❗ **3. Problem Statement**

The project aims to address the following:

* Analyse inspection outcomes across UK regions and provider types
* Identify performance gaps and improvement opportunities
* Study year-wise inspection trends over time
* Compare current vs previous inspections
* Understand how many institutions fall into key rating categories: **Outstanding**, **Good**, **Requires Improvement**, **Inadequate**

---

## 🧾 **4. Dataset Attribute Details**

| Attribute                                           | Type                     |
| --------------------------------------------------- | ------------------------ |
| Provider URN                                        | Text                     |
| Provider UKPRN                                      | Text                     |
| Provider Name                                       | Text                     |
| Provider Type                                       | Text                     |
| Provider Group                                      | Text                     |
| Local Authority                                     | Text                     |
| Region                                              | Text                     |
| Ofsted Region                                       | Text                     |
| Date Of Latest Short Inspection                     | Date                     |
| No. of Short Inspections Since Last Full Inspection | Whole Number             |
| Inspection Number                                   | Text                     |
| Inspection Type                                     | Text                     |
| First Day of Inspection                             | Date                     |
| Last Day of Inspection                              | Date                     |
| Date Published                                      | Date                     |
| Overall Effectiveness                               | Whole Number (1–4 scale) |
| Quality of Education                                | Whole Number             |
| Behaviour and Attitudes                             | Whole Number             |
| Personal Development                                | Whole Number             |
| Leadership and Management                           | Whole Number             |
| Contribution to Meeting Skills Needs                | Text                     |
| Is Safeguarding Effective?                          | Text                     |
| Previous Inspection Number                          | Text                     |
| Previous Last Day of Inspection                     | Date                     |
| Previous Ratings (multiple fields)                  | Whole Number             |
| Improved/Declined/Stayed Same (Overall Comment)     | Text                     |

---

## 🛠 **5. Tools & Technologies**

* **Power BI** — Reporting & visualization
* **Microsoft Excel** — Data cleaning & preprocessing
* **Power Query** — Data transformation
* **DAX** — Custom calculations and KPIs

---

## 🧹 **6. Data Pre-Processing**

Data cleaning included:

* Handling missing values
* Standardising formats
* Deriving calculated fields
* Converting rating text to **numeric scores (1–4)**
* Preparing the dataset for analytics and modelling

---

## 🧮 **7. Data Modelling & DAX**

### **Data Model**

* Calendar table
* Relationships established
* Inspection fact table
<img width="858" height="537" alt="image" src="https://github.com/user-attachments/assets/a9c3a7f7-8462-48fe-a572-d92423bb9e5b" />

### **Calculated Columns**

* **Rating Score** (4 = Outstanding → 1 = Inadequate)
* Inspection Duration Days
* Years Since Last Inspection

### **Key Measures**

* Total Institutions Inspected
* Inspection Duration
* Count Full Inspections
* Count Short Inspections
* Count Previous Inspections
* Count Without Previous Inspections
* Count by Rating Categories (Outstanding, Good, RI, Inadequate)
* Percentages for each rating category

---

## 📊 **8. Analysis & Visualisations**

### 🚩 Dashboard Features

* High-level overview of inspection volumes and regional distribution
* Year-on-year inspection trend analysis
* Rating distribution by provider type and region
* Comparison of current vs previous inspection outcomes
* Interactive slicers: Year, Region, Provider Type, Provider Name
* Visuals include:

  * Line charts
  * Bar & Column charts
  * Donut charts
  * KPI Cards
  * Tables & Matrix

---

## 🔍 **9. Insights & Key Findings**

### **Descriptive Insights**

* Most institutions fall into the **Good** category
* Certain regions have consistently higher inspection activity
* Full inspections dominate over short inspections

### **Diagnostic Insights**

* Leadership & management weaknesses often correlate with declining performance
* Underperforming regions reveal gaps in governance or resource allocation

### **Predictive Insights**

* Providers showing continuous progress are likely to improve future ratings
* Regions with patterns of low performance may face increased inspection frequency

### **Prescriptive Recommendations**

* Target underperforming regions with leadership & governance support
* Monitor declining providers closely
* Promote sharing of best practices from top-performing institutions
* Apply data-driven review cycles for ongoing improvement

---

## 🏁 **10. Conclusion**

The integrated use of **Excel, Power Query, and Power BI** enabled efficient transformation of raw UK inspection data into a powerful analytics solution.

The dashboard reveals:

* Performance patterns
* Regional quality gaps
* Improvement trends
* Actionable insights for decision-makers

This project demonstrates how data-driven examination of inspection outcomes can support better strategic planning in the UK education sector.

👤 Author

Name: Brindha Senthilkumar <br/>
Role: Data Analyst <br/>
Contact: [Brindha_Linkedin] (https://www.linkedin.com/in/brindha-senthilkumar-742b18273/)

