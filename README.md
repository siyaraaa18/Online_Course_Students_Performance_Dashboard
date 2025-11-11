## **📊 Online Course Student Performance Analysis**
**🧩 Domain: Data Analytics**

## **📘 Project Overview**

This end-to-end analytics project transforms raw student data into actionable insights through a structured ETL process using Excel and Power BI. The analysis evaluates learning effectiveness, engagement patterns, and completion drivers across global student demographics.

## **Objectives:**

-Assess student engagement levels and learning progress

-Identify high-performing course categories and geographic regions

-Analyze feedback distribution across experience levels

-Understand time investment patterns and completion trends

## **🧩 Tools & Technologies**

**-Excel:** Data cleaning, transformation, and validation

**-Power BI:** Data modeling, DAX measures, and dashboard creation

## 📊 Dataset Structure
| Category | Metrics |
|----------|---------|
| **Demographics** | Age, Gender, Country, Experience Level |
| **Course Details** | Course Name, Category, Enrollment Date |
| **Performance** | Progress %, Completion Status, Feedback Rating |
| **Engagement** | Time Spent, Session Attendance, Engagement Score |

## **🛠️ Technical Implementation: A Two-Stage Process**

## **🧹 Part 1: Data Cleaning (Microsoft Excel)**

The foundation of the analysis was built through meticulous data preparation in Excel.

## **1. Handled Missing & Invalid Data:**

-Replaced blank/zero values in the Age column with the median age.

-Identified and flagged invalid entries in the Feedback_Rating.

-Standardized the Completed column to consistent "Yes"/"No" values.

## **2. Data Transformation & Standardization:**

-Converted all Time_Spent values into a standardized hourly format.

-Formatted the Progress column as a percentage.

-Parsed Session_Attendance to extract the total number of sessions.

-Applied proper date formatting to the Enrollment_Date field.

## **3. Created Derived Metrics:**

-Engagement_Score: A composite metric calculated as:
=MIN((0.7 * Progress + 0.3 * Time_Spent), 100)

-Engagement_Level: Categorized students into High, Medium, Low based on score thresholds.

-Higher_Performer Flag: Identified students who completed the course with a high feedback rating.

## **📈 Part 2: Interactive Dashboard Development (Power BI)**

The cleansed data was imported into Power BI to build a multi-page, interactive reporting suite.

## **📁 Dashboard Architecture:**

## **1. Overview and Performance Summary**

Purpose: A high-level executive summary of platform performance.

## **Key Components:**

-KPI Cards: Total Students, Average Progress, Average Feedback Rating, Average Engagement Score, Course Completion Rate.

## **Core Visualizations:**

-📊 Column Chart – Students by Course Category
  
-📊 Bar Chart – Completion % by Country
  
-🍩Donut Chart – Course Completion by Country

-📋Matrix Table – Feedback Distribution by Course

-Slicers: Course Category | Experience Level | Country | Enrollment Date

## **2. Engagement and Learning Insights**

Purpose: Uncover relationships and trends in the data.

-🔵Scatter Plot: Relationship Between Progress and Feedback Rating (Engagement Correlation)

-📈Line Chart: Enrollment Trend by Month

-📊 Bar Chart: Average Study Time by Course Category (Hours)

-🌡️Engagement Heatmap

## **3. Students Detail**

Purpose: A granular, operational view for detailed student tracking.

## **Key Components:**

-An interactive table displaying student-level data (Name, Course, Progress %, Time Spent, Completion Status, etc.).

-Drill-Through Capability: Serves as a detail page from summary visuals.

## **💡 Key Insights**

- Students aged 25-35 show highest completion rates
  
- Technical courses receive best satisfaction scores
  
- Strong correlation between engagement and completion
  
- Consistent attendance improves feedback ratings

## **🚀 Key Features**

- Dynamic filtering by multiple dimensions
  
- Cross-visual highlighting
  
- Real-time KPI updates
  
- Interactive drill-through

---
## 👤 Author
**Siyara Sathar**  
📧 siyarasathar18@gmail.com  
💼 [LinkedIn](www.linkedin.com/in/siyara-sathar)



