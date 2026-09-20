# 📊 Power BI Data Analysis & Interactive Dashboards

## 📌 Project Overview

This project is an end-to-end **Data Analysis and Business Intelligence project using Microsoft Power BI**.

The main goal of the project was to transform raw data into meaningful insights through **data cleaning, data modeling, DAX calculations, and interactive dashboards**.

The project includes **6 interactive dashboards**, each designed to analyze a different aspect of the data and help users understand performance, trends, and key business metrics.

---

## 🎯 Project Objectives

The main objectives of this project were:

* Clean and prepare the raw data for analysis.
* Build a suitable data model.
* Create relationships between tables.
* Develop calculated measures using **DAX**.
* Create interactive and easy-to-understand dashboards.
* Analyze important KPIs and business metrics.
* Identify trends and patterns in the data.
* Present the final results through professional Power BI visualizations.

---

# 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX (Data Analysis Expressions)**
* Data Modeling
* Data Visualization
* GitHub

---

# 🗂️ Project Workflow

The project was completed through the following steps:

```text
Raw Data
   ↓
Data Cleaning & Transformation
   ↓
Data Modeling
   ↓
Relationships
   ↓
DAX Measures
   ↓
Data Visualization
   ↓
6 Interactive Dashboards
   ↓
Business Insights
```

---

# 🧹 1. Data Preparation & Cleaning

The first stage of the project was preparing the raw dataset before starting the analysis.

I used **Power Query in Power BI** to clean and transform the data.

The main data preparation steps included:

### Removing unnecessary data

Unnecessary columns and information that were not required for the analysis were removed to keep the dataset clean and efficient.

### Handling missing values

Missing or incomplete values were checked and handled depending on the type of column and its importance to the analysis.

### Removing duplicates

Duplicate records were checked and removed where necessary to make sure that the analysis was based on reliable data.

### Changing data types

Each column was assigned the appropriate data type, such as:

* Text
* Whole Number
* Decimal Number
* Date
* Date/Time

Correct data types are important because they affect calculations, filtering, sorting, and visualization.

### Renaming columns

Columns were renamed when necessary to make the dataset easier to understand and work with.

### Data transformation

The data was transformed into a structure that could be used effectively for analysis and visualization.

These transformations helped create a cleaner and more consistent dataset before building the data model.

---

# 🧩 2. Data Modeling

After preparing the data, the next step was creating the **data model**.

The tables were connected using relationships based on common fields.

The goal of the data model was to make sure that:

* Tables communicate correctly with each other.
* Filters work properly across the dashboards.
* DAX calculations return accurate results.
* The model is organized and easy to maintain.

The relationships between the tables were created according to the available keys and business logic of the dataset.

---

# 🧮 3. DAX Measures

After preparing the data model, I created several **DAX measures** to calculate the main KPIs used throughout the dashboards.

DAX was used because it allows dynamic calculations that respond to filters and user interactions inside Power BI.

The measures were created based on the business requirements of the project.

Examples of the types of calculations used include:

### Total Values

Measures were created to calculate overall totals such as total sales, total quantity, total revenue, or other main numerical metrics depending on the dataset.

Example:

```DAX
Total Value =
SUM('Table'[Value])
```

### Counts

Counting records, customers, products, orders, or other entities was performed using DAX functions such as:

```DAX
Total Records =
COUNTROWS('Table')
```

### Distinct Counts

For unique entities, `DISTINCTCOUNT` can be used.

Example:

```DAX
Unique Customers =
DISTINCTCOUNT('Table'[Customer_ID])
```

### Averages

Average values were calculated using functions such as `AVERAGE`.

Example:

```DAX
Average Value =
AVERAGE('Table'[Value])
```

### Percentages

Percentage-based KPIs were calculated using DAX measures and appropriate filter context.

Example:

```DAX
Percentage =
DIVIDE([Current Value], [Total Value], 0)
```

### Time-Based Analysis

Where applicable, DAX was also used to analyze changes over time, compare periods, and identify trends.

The main advantage of using measures instead of static calculated values is that the results dynamically change when the user interacts with slicers and filters.

---

# 📊 4. Dashboard Design

The final Power BI report contains **6 interactive dashboards**.

Each dashboard focuses on a specific part of the analysis while maintaining a consistent design and user experience.

---

## 📈 Dashboard 1 — Overview Dashboard

The first dashboard provides a general overview of the dataset and the most important KPIs.

It is designed to give the user a quick understanding of the overall performance.

The dashboard includes:

* Main KPI cards
* Summary charts
* Overall performance indicators
* Filters and slicers
* High-level business insights

This dashboard acts as the starting point of the report.

---

## 📊 Dashboard 2 — Performance Analysis

The second dashboard focuses on analyzing performance in more detail.

It allows users to compare different categories and identify which areas are contributing the most to the overall results.

The dashboard uses interactive visuals to make comparisons easier and highlight important differences.

---

## 📅 Dashboard 3 — Trend Analysis

The third dashboard focuses on trends over time.

Time-based visualizations were used to analyze how the main metrics changed across different periods.

This dashboard helps identify:

* Growth and decline
* Seasonal patterns
* Changes over time
* High and low performance periods

Interactive filters allow users to analyze specific periods in more detail.

---

## 👥 Dashboard 4 — Customer / Category Analysis

The fourth dashboard provides a more detailed analysis of the available customer or category-related data.

The purpose of this dashboard is to understand the distribution of the data and identify the most important segments.

Different visualizations were used to compare categories and highlight differences between them.

---

## 🔍 Dashboard 5 — Detailed Analysis

The fifth dashboard provides a deeper level of analysis.

Instead of focusing only on high-level KPIs, this dashboard allows the user to explore the data in greater detail.

Interactive slicers and visualizations make it possible to filter the data and investigate specific segments.

---

## 📌 Dashboard 6 — Insights Dashboard

The final dashboard summarizes the most important findings from the analysis.

It combines the key metrics and visualizations needed to understand the main conclusions from the dataset.

The dashboard is designed to provide a clear and concise view of the most important insights discovered during the analysis.

---

# 🎛️ Interactivity

One of the main goals of the report was to make the dashboards interactive rather than static.

The report includes interactive elements such as:

* Slicers
* Filters
* Cross-filtering
* Interactive charts
* KPI cards
* Dynamic DAX measures

When users select a specific category, date, or other filter, the visualizations update automatically based on the selected context.

---

# 🧠 DAX & Filter Context

An important part of the project was understanding how **DAX measures interact with the filter context**.

The measures were designed to respond dynamically to the selections made by the user.

For example, when a user selects a specific period or category from a slicer, the DAX measures recalculate the results based on the selected filter context.

This makes the dashboards dynamic and allows users to explore the data from different perspectives.

---

# 📌 Key Concepts Used

During the project, several important Power BI concepts were applied:

* Power Query
* Data Cleaning
* Data Transformation
* Data Modeling
* Relationships
* DAX Measures
* Aggregations
* Filter Context
* KPI Analysis
* Time-Based Analysis
* Interactive Slicers
* Data Visualization
* Dashboard Design



# 📈 Insights

Through the analysis and dashboards, the project provides a clear view of the most important patterns and KPIs within the dataset.

The dashboards make it easier to:

* Monitor overall performance.
* Compare different categories.
* Analyze trends over time.
* Identify high-performing and low-performing segments.
* Explore the data interactively.
* Support data-driven decision making.

---

# 🚀 How to Use the Project

1. Download or clone the repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. Make sure the required dataset is available.
4. Refresh the data if necessary.
5. Navigate through the six dashboards.
6. Use the slicers and filters to explore the data interactively.

---

# 💡 What I Learned

This project helped me practice and improve my skills in:

* Data cleaning and transformation using Power Query.
* Building data models in Power BI.
* Creating relationships between tables.
* Writing DAX measures.
* Understanding filter context.
* Designing interactive dashboards.
* Selecting appropriate visualizations for different types of analysis.
* Turning raw data into meaningful business insights.
* Presenting analytical results in a clear and professional way.

---


Data Analyst | Power BI | SQL | Excel | DAX

---

# ⭐ Project

If you found this project useful or interesting, feel free to explore the repository and check out the dashboards and analysis.
