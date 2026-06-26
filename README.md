# ⏱️ Production Working Hours Analysis Dashboard | Power BI

## 📌 Project Overview

The **Production Working Hours Analysis Dashboard** is an interactive Power BI solution designed to monitor workforce productivity, working hours utilization, overtime trends, budget allocation, and employee performance across multiple divisions and locations.

This dashboard enables operations managers, HR teams, and business leaders to evaluate workforce efficiency, optimize resource allocation, control overtime costs, and improve productivity through data-driven decision-making.

---

## 🎯 Business Objective

The primary objectives of this dashboard are to:

* Monitor employee working hours and productivity.
* Compare planned hours against actual worked hours.
* Track overtime utilization across job roles.
* Analyze workforce performance by division and city.
* Evaluate budget allocation versus actual earnings.
* Support workforce planning and operational efficiency initiatives.

---

## 📊 Executive KPI Summary

The dashboard provides a snapshot of key workforce metrics:

| KPI                  | Value  |
| -------------------- | ------ |
| Total Employees      | 21     |
| Total Worked Hours   | 30,679 |
| Total Unworked Hours | 722    |
| Total Overtime Hours | 1,769  |
| Total Planned Hours  | 29,276 |

### Gender Distribution

| Gender | Employees |
| ------ | --------- |
| Male   | 11        |
| Female | 10        |

---

## 📈 Key Dashboard Insights

### 1. Division-Wise Budget vs Earnings Analysis

The dashboard compares actual earnings against allocated budgets across divisions.

| Division    | Amount Earned | Allocated Budget |
| ----------- | ------------- | ---------------- |
| Photography | Highest       | Highest          |
| Supporting  | Moderate      | Moderate         |
| Management  | Lowest        | Lowest           |

### Key Insight

* Photography division contributes the highest revenue generation.
* Budget allocation closely aligns with division performance.

---

### 2. Planned vs Worked vs Unworked Hours by City

Workforce utilization is analyzed across global locations.

### Cities Covered

* Tokyo
* Toronto
* Cape Town
* Barcelona
* Berlin
* Chicago
* Mumbai
* Mexico City
* Sydney

### Key Findings

* Tokyo records the highest planned and worked hours.
* Unworked hours remain minimal across most cities.
* Workforce utilization appears highly efficient across locations.

---

### 3. Employee Performance Analysis

Top contributors based on amount earned:

| Employee | Amount Earned |
| -------- | ------------- |
| Zoe      | 156K          |
| Nora     | 150K          |
| Sam      | 144K          |
| Sebas    | 122K          |
| Willi    | 100K          |

### Key Insight

* Zoe is the highest revenue-generating employee.
* Performance benchmarking can be used for recognition and incentive planning.

---

### 4. Division-Wise Work Distribution

Comparison of planned and actual worked hours.

| Division    | Planned Hours | Worked Hours |
| ----------- | ------------- | ------------ |
| Photography | 21K           | 22K          |
| Supporting  | 5K            | 5K           |
| Management  | 3K            | 3K           |

### Key Insight

* Photography division exceeded planned hours.
* Supporting and Management maintained close adherence to planned schedules.

---

### 5. Overtime Analysis by Job Title

Overtime distribution across workforce roles.

| Job Title   | Overtime Contribution |
| ----------- | --------------------- |
| Cameraman   | 58%                   |
| Coordinator | 23.8%                 |
| Assistant   | 18.2%                 |

### Key Insight

* Cameramen account for the majority of overtime hours.
* Workload balancing opportunities may exist within operational teams.

---

## 🏢 Workforce Performance Metrics

The dashboard measures:

* Employee Productivity
* Planned vs Actual Hours
* Overtime Utilization
* Resource Allocation
* Workforce Efficiency
* Division Performance
* City-Level Operations
* Employee Contribution Analysis

---

## 🎛️ Interactive Dashboard Features

### Dynamic Filters

Users can analyze data by:

#### Division

* Management
* Photography
* Supporting

#### City

* Barcelona
* Berlin
* Cape Town
* Chicago
* Mexico City
* Mumbai
* Sydney
* Tokyo
* Toronto

These filters allow detailed workforce and operational analysis.

---

## 🛠️ Tools & Technologies Used

| Tool                | Purpose                |
| ------------------- | ---------------------- |
| Power BI Desktop    | Dashboard Development  |
| Power Query         | Data Transformation    |
| DAX                 | KPI & Measure Creation |
| Excel / CSV Dataset | Data Source            |
| Workforce Analytics | Productivity Analysis  |
| HR Analytics        | Resource Planning      |

---

## 📂 Dataset Overview

The dataset contains:

* Employee ID
* Employee Name
* Gender
* Division
* Job Title
* City
* Planned Hours
* Worked Hours
* Unworked Hours
* Overtime Hours
* Allocated Budget
* Amount Earned
* Work Date

---

## 📐 DAX Measures Used

### Total Worked Hours

```DAX
Total Worked Hours =
SUM(EmployeeData[Worked Hours])
```

### Total Overtime Hours

```DAX
Total Overtime Hours =
SUM(EmployeeData[Overtime Hours])
```

### Total Planned Hours

```DAX
Total Planned Hours =
SUM(EmployeeData[Planned Hours])
```

### Total Employees

```DAX
Total Employees =
DISTINCTCOUNT(EmployeeData[Employee ID])
```

### Utilization Rate %

```DAX
Utilization Rate % =
DIVIDE(
    [Total Worked Hours],
    [Total Planned Hours],
    0
) * 100
```

---

## 📷 Dashboard Preview

![Production Working Hours Dashboard](Images/Production_Working_Hours_Dashboard.png)

---

## 🔍 Business Findings

### Workforce Efficiency

* Actual worked hours closely align with planned hours.
* Minimal unworked hours indicate strong workforce utilization.

### Overtime Management

* Significant overtime concentration among Cameramen.
* Potential risk of employee fatigue and workload imbalance.

### Revenue Contribution

* Photography division generates the highest earnings.
* Top-performing employees contribute significantly to overall revenue.

### Resource Planning

* Most divisions are operating near planned capacity.
* Workforce allocation appears optimized.

---

## 💡 Recommendations

### Improve Workforce Planning

* Balance workloads among employees to reduce overtime dependency.
* Optimize shift scheduling based on workload trends.

### Overtime Control

* Monitor departments with consistently high overtime.
* Introduce resource redistribution strategies.

### Employee Performance Management

* Recognize top performers through incentive programs.
* Use productivity metrics for performance reviews.

### Budget Optimization

* Continue allocating resources toward high-performing divisions.
* Evaluate return on investment for each division.

---

## 🚀 Future Enhancements

* Workforce Productivity Forecasting.
* Employee Utilization Scorecards.
* Overtime Prediction using Machine Learning.
* Real-Time Workforce Monitoring.
* Leave and Absenteeism Analytics.
* Shift Performance Analysis.
* Labor Cost Optimization Dashboard.

---

## 📁 Repository Structure

```text
Production-Working-Hours-Analysis/
│
├── Dataset/
│   └── Working_Hours_Data.xlsx
│
├── Dashboard/
│   └── Production_Working_Hours_Dashboard.pbix
│
├── Images/
│   └── Dashboard_Screenshot.png
│
├── README.md
│
└── LICENSE
```

---

## 👨‍💻 Author

**Shivam Kr. Rajput**

Production Head | Manufacturing Analytics Professional | Power BI Developer

**Skills:** Power BI • SQL • Python • Excel • Workforce Analytics • Lean Manufacturing • Six Sigma

### Connect With Me

* LinkedIn: [www.linkedin.com/in/shivamkrrajput](http://www.linkedin.com/in/shivamkrrajput)
* GitHub: github.com/shivamkrrajput

---

## ⭐ Project Impact

This dashboard demonstrates how workforce and operational data can be transformed into actionable business insights using Power BI. By analyzing working hours, overtime, employee productivity, and budget utilization, organizations can improve workforce efficiency, optimize resource allocation, and enhance overall operational performance.

**If you found this project valuable, please consider giving it a ⭐ Star on GitHub!**
