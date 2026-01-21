# Student-Performance-Analysis
# Student Performance Analysis Dashboard (Microsoft Excel)

## Project Description

This project presents a comprehensive **Student Performance Analysis Dashboard** developed using **Microsoft Excel**. The goal of the analysis is to examine student academic performance, identify key factors influencing scores, and translate analytical findings into a clear, interactive dashboard that supports data-driven decision-making.

Microsoft Excel was selected as the analysis tool due to its widespread use in business and analytics environments, strong built-in statistical capabilities, and ability to combine data preparation, analysis, and visualization within a single platform. This project demonstrates how Excel can be effectively leveraged for analytical workflows typically associated with more advanced BI tools.

---

## Objectives of the Analysis

The key objectives of this project are to:

- Understand the factors that influence student academic performance  
- Analyze relationships between study behavior indicators and actual scores  
- Apply statistical analysis techniques within Excel  
- Design an interactive dashboard for performance monitoring and insights  

---

## Dataset Description

The dataset consists of student-level academic and behavioral metrics. Each record represents an individual student and includes the following variables:

- **Hours Studied**  
  The total number of hours a student spent studying during the evaluation period.

- **Attendance (%)**  
  The percentage of classes attended by the student.

- **Assignments Completed**  
  The number of assignments successfully submitted by the student.

- **Actual Score**  
  The final academic score achieved by the student.

These variables were chosen to evaluate how engagement, consistency, and study habits relate to academic outcomes.

---

## Tools & Technologies Used

### Primary Tool
- **Microsoft Excel**

### Excel Features Utilized
- Data cleaning and structuring techniques  
- Built-in formulas and functions (e.g., AVERAGE, IF, CORREL, COUNTIFS)  
- Correlation analysis using Excel statistical functions  
- Conditional formatting for heatmap visualization  
- Regression analysis using trendlines  
- Charts (bar charts, histograms, scatter plots)  
- Dashboard layout and interactive visual components  

---

## Data Cleaning & Preparation

Prior to analysis, the dataset underwent several preparation steps to ensure accuracy and consistency:

- Organized data into a structured tabular format with defined headers  
- Standardized numeric and percentage values  
- Checked for missing, inconsistent, or invalid entries  
- Ensured uniform data types across all variables  
- Created helper columns where necessary for analysis and visualization  

These steps ensured the dataset was reliable and suitable for statistical analysis and dashboard reporting.

---

## Exploratory Data Analysis (EDA)

### Correlation Analysis

Correlation analysis was conducted to quantify the relationships between study behaviors and student scores.

![Heatmap](Pictures/screenshots/Heatmap.png)

**Methodology:**
- Pairwise correlations were calculated using Excel’s `CORREL()` function  
- A correlation matrix was constructed for all numeric variables  
- Conditional formatting with a color scale was applied to create a correlation heatmap  

**Interpretation:**
- Attendance exhibits the strongest positive correlation with Actual Score  
- Hours Studied and Assignments Completed show weaker relationships  
- Student performance is influenced by multiple variables rather than a single factor  

---

### Score Distribution Analysis

To understand overall performance trends:

- Student scores were grouped into predefined score bins  
- A histogram was created to visualize the distribution  

**Insights from Distribution:**
- Most students fall within the mid-range score categories  
- Extreme high and low scores occur less frequently  
- Performance is moderately distributed rather than highly skewed  

---

## Regression & Predictive Analysis

Regression analysis was applied to estimate the relationship between study behaviors and student scores.

### Approach
- Scatter plots were created to visualize relationships between predictors and scores  
- Linear trendlines were added to identify patterns  
- Regression equations were used to generate predicted scores  

### Purpose
- Demonstrate predictive modeling concepts using Excel  
- Assess how well study behaviors explain academic outcomes  

### Limitations
- Limited dataset size reduces predictive robustness  
- Linear regression assumes relationships that may not fully capture real-world complexity  
- Important variables such as motivation or prior academic ability are not included  

---

## Dashboard Design

The Excel dashboard consolidates key findings into a single, interactive interface.

### Dashboard Sections

- **Class Averages**  
  Displays overall averages for scores, attendance, and study behavior.

- **Gender Comparison**  
  Compares performance metrics across gender categories.

- **Performance Segmentation**  
  Groups students into performance bands for quick assessment.

- **Correlation Heatmap**  
  Visual summary of relationships between academic variables.

- **Actual vs Predicted Score Visualization**  
  Compares observed student scores with regression-based predictions.

### Design Considerations
- Clean, uncluttered layout for readability  
- Consistent color scheme to highlight insights  
- Logical flow from summary metrics to detailed analysis  
- Designed for both technical and non-technical stakeholders  

---

## Key Insights & Findings

- Attendance shows the strongest relationship with academic performance  
- Study hours and assignment completion alone are weaker predictors  
- Student performance is influenced by multiple interacting factors  
- Excel can effectively support statistical analysis and dashboard reporting  

---

## Limitations & Future Improvements

### Current Limitations
- Small dataset size limits generalizability  
- Limited explanatory variables reduce predictive accuracy  
- Regression model is intentionally simple  

### Future Enhancements
- Include additional variables such as prior performance, study methods, or demographics  
- Extend the dashboard using **Power BI** for advanced interactivity  
- Replicate the analysis using **Python** for scalable analytics  
- Store and analyze larger datasets using **SQL**  

---

## Conclusion

This project demonstrates my ability to:

- Clean and prepare data for analysis  
- Apply statistical techniques using Microsoft Excel  
- Conduct exploratory and predictive analysis  
- Design professional dashboards for insight-driven decision-making  

The project highlights **Microsoft Excel as a capable analytics and business intelligence tool**, suitable for end-to-end data analysis when applied with sound analytical principles.
