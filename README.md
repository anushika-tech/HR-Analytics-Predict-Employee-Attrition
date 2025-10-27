# HR-Analytics-Predict-Employee-Attrition


## 📝 Project Overview
This project focuses on understanding and predicting **employee attrition** using HR data analytics.  
Employee turnover is a major challenge for organizations, and this project aims to identify the key factors that cause employees to leave and provide data-driven recommendations to improve retention.

Using **Python (Pandas, Seaborn, Scikit-learn)** for analysis and **Power BI** for visualization, this project demonstrates how HR departments can make evidence-based decisions to improve job satisfaction and workforce stability.

---

## 🎯 Objective
To analyze HR data and build a model that predicts employee attrition, identifies major causes of turnover, and provides actionable insights for improving employee retention strategies.

---

## 🧰 Tools & Technologies
- **Python:** For data preprocessing, analysis, and model building (Pandas, Seaborn, Scikit-learn)  
- **Power BI:** For creating interactive dashboards and visualizing insights  
- **Excel:** For initial data exploration and preparation  

---

## 📂 Dataset Information
Dataset used: [IBM HR Analytics Employee Attrition & Performance (Kaggle)](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)

| Column | Description |
|---------|-------------|
| Age | Age of employee |
| Department | Employee department (Sales, HR, R&D) |
| MonthlyIncome | Employee salary |
| JobRole | Designation/position of employee |
| OverTime | Whether the employee works overtime |
| JobSatisfaction | Satisfaction level (1–4) |
| Attrition | Whether the employee left (Yes/No) |

---

## 🧮 Key Steps

### **1️⃣ Data Collection & Cleaning**
- Imported dataset into Python using Pandas  
- Removed duplicates and null values  
- Encoded categorical features using `LabelEncoder`

### **2️⃣ Exploratory Data Analysis (EDA)**
- Visualized attrition distribution by department, salary, and age  
- Found patterns: attrition highest among younger employees and low-salary groups  
- Analyzed correlation using heatmaps and bar charts

### **3️⃣ Model Building**
- Applied **Logistic Regression** for binary classification  
- Split dataset into training and testing sets (80/20)  
- Achieved ~82% accuracy  
- Generated **Confusion Matrix** and **Classification Report**

### **4️⃣ Visualization & Dashboard**
- Designed an interactive **Power BI Dashboard** with:
  - Cards: Total Employees, Attrition Count, Attrition Rate  
  - Charts: Attrition by Department, Salary Band, Gender, and Age  
  - Insights section summarizing key trends  

### **5️⃣ Insights & Recommendations**
- Attrition highest among employees aged 25–35  
- Overtime and low salary are top attrition drivers  
- Sales and Research departments show maximum turnover  
- Recommend salary benchmarking, flexible work policies, and better career progression programs  

---

## 📈 Dashboard Highlights
Power BI Dashboard Visuals:
- **Pie Chart:** Attrition %  
- **Bar Chart:** Attrition by Department and Job Role  
- **Line Chart:** Salary vs Attrition  
- **KPIs:** Total Employees, Attrition Rate  

---

## 💡 Key Insights
- 16% overall attrition rate observed  
- Employees with **low income and overtime workload** are more likely to leave  
- Work-life balance and job satisfaction have strong retention impact  
- Targeted interventions can reduce turnover by focusing on at-risk groups  

---

## 📎 Deliverables
- `HR_Analytics_Project_Report_2Page.pdf` – Final 2-page report  
- `hr_analytics.ipynb` – Python notebook for analysis and model  
- `HR_Attrition_Dashboard.pbix` – Power BI dashboard file  
- `README.md` – Project documentation  

---

## 🧠 Learning Outcomes
- Understanding of HR data analysis using Python and Power BI  
- Experience with classification models (Logistic Regression)  
- Ability to interpret and visualize HR insights effectively  

---

### ⭐ If you found this project helpful, don’t forget to star the repository!
