# Power BI Formatting Task

## 1. Project Title

**Power BI Sales Analysis and Dashboard Formatting**

## 2. Project Overview

This project demonstrates the development and formatting of an interactive Power BI dashboard using a relevant Kaggle dataset.

The purpose of the project is to transform raw sales data into a clean, interactive, and visually appealing dashboard that helps users understand sales performance, trends, and regional/category-level performance.

The project covers the complete Power BI workflow:

* Dataset import
* Data cleaning
* Data transformation
* Calculated columns/measures
* Data visualization
* Dashboard formatting
* Interactive filtering
* Dashboard layout and design
* Final report export

---

## 3. Dataset

### Dataset Source

The dataset used for this project was obtained from **Kaggle**.

**Dataset Type:** Sales / Retail / E-commerce dataset

The dataset contains sales-related information that can be used to analyze:

* Sales/Revenue
* Orders/Transactions
* Products
* Categories
* Regions
* Dates
* Customer or location information

### Data Import

The Kaggle dataset was downloaded and imported into **Microsoft Power BI Desktop** using the appropriate data import option.

The data was then loaded into Power Query for cleaning and transformation before creating the dashboard.

---

## 4. Data Cleaning and Transformation

Data cleaning was performed in **Power Query** before creating the dashboard.

The following cleaning activities were performed:

### Missing Values

* Checked columns for missing/null values.
* Removed or replaced missing values where appropriate.
* Ensured that important analytical columns contained valid data.

### Duplicate Records

* Checked the dataset for duplicate records.
* Removed duplicate rows where necessary.

### Data Types

Appropriate data types were assigned to the columns.

Examples:

* Date → Date
* Sales/Revenue → Decimal Number
* Quantity → Whole Number
* Category → Text
* Region → Text

### Text Cleaning

Text fields were checked for inconsistent formatting and unnecessary spaces.

### Data Validation

The cleaned dataset was reviewed to ensure that the values were suitable for analysis and visualization.

---

## 5. Calculated Columns and Measures

Calculated measures were created in Power BI to support dashboard analysis.

Examples include:

### Total Revenue

```DAX
Total Revenue = SUM(Sales[Revenue])
```

### Total Sales

```DAX
Total Sales = SUM(Sales[Sales])
```

### Total Quantity

```DAX
Total Quantity = SUM(Sales[Quantity])
```

### Average Sales

```DAX
Average Sales = AVERAGE(Sales[Sales])
```

The measures are used in KPI cards and visualizations to provide summarized business information.

> Note: The table and column names in the actual PBIX file should match the dataset used in the project.

---

# 6. Dashboard Visualizations

The dashboard contains multiple visualizations designed to answer important business questions.

## KPI Cards

KPI cards are used to display important summary information such as:

* Total Revenue
* Total Sales
* Total Quantity
* Average Sales

These provide users with an immediate overview of business performance.

## Bar Chart

A bar chart is used to compare sales/revenue across categories or regions.

**Business Question:**

> Which category or region generates the highest sales?

## Line Chart

A line chart is used to analyze sales performance over time.

**Business Question:**

> How have sales changed over time?

## Regional/Category Analysis

A visual is used to compare performance between different regions or categories.

**Business Question:**

> Which regions or categories are performing better?

## Slicers

Slicers are included to allow users to filter the dashboard interactively.

Examples:

* Date
* Region
* Category
* Product

---

# 7. Formatting

Consistent formatting was applied throughout the dashboard to create a professional appearance.

### Theme

A consistent Power BI color theme was applied to the report.

### Colors

Custom colors were selected to maintain visual consistency between:

* KPI cards
* Charts
* Slicers
* Background
* Titles
* Labels

### Fonts

Font sizes and styles were adjusted according to the importance of each dashboard element.

Larger fonts were used for:

* Dashboard title
* KPI values
* Section headings

Smaller fonts were used for:

* Axis labels
* Supporting information
* Descriptions

### Chart Formatting

Charts were formatted by adjusting:

* Axis titles
* Data labels
* Legends
* Gridlines
* Background
* Titles
* Tooltips

### KPI Formatting

KPI cards were formatted using:

* Consistent backgrounds
* Appropriate font sizes
* Clear labels
* Consistent spacing
* Visual hierarchy

---

# 8. Interactive Features

Interactive features were implemented to allow users to explore the dashboard.

### Slicers

Slicers allow users to filter the report based on selected fields such as:

* Date
* Region
* Category
* Product

When a slicer selection is changed, the related dashboard visuals update automatically.

### Visual Interactions

Cross-filtering/cross-highlighting between visuals allows users to select a category, region, or other data point and observe the corresponding changes in other visuals.

---

# 9. Dashboard Layout

The dashboard was arranged on a **single Power BI report page**.

The layout follows a clear visual hierarchy.

### Top Section

The top section contains:

* Dashboard title
* Subtitle/description
* KPI cards

### Middle Section

The middle section contains the main analytical charts, such as:

* Sales trend
* Category performance
* Regional performance

### Side/Filter Section

Slicers are positioned so that users can easily filter the report.

### Layout Principles

The following design principles were followed:

* Proper alignment
* Consistent spacing
* Avoiding overlapping visuals
* Consistent visual sizes
* Clear section separation
* Logical placement of KPIs and charts
* Easy navigation and readability

---

# 10. Dashboard Title and Description

### Title

**Sales Performance Analysis Dashboard**

### Subtitle

**Interactive analysis of sales trends, revenue performance, categories, and regional performance**

### Dashboard Description

**This dashboard provides an interactive overview of sales performance using key performance indicators and analytical visualizations. Users can explore revenue, sales trends, category performance, and regional performance using interactive filters.**

---

# 11. Business Questions Addressed

The dashboard is designed to answer the following business questions:

1. What is the total revenue?
2. What is the total sales performance?
3. How are sales changing over time?
4. Which category generates the highest sales?
5. Which region performs best?
6. Which products or categories require further attention?
7. How does performance change when different filters are selected?

---

# 12. Key Insights

The dashboard allows users to identify:

* Overall sales performance
* Sales trends over time
* High-performing categories
* High-performing regions
* Changes in performance based on selected filters
* Areas that may require further business attention

The exact insights are derived dynamically from the imported dataset and the user's filter selections.

---

# 13. Tools Used

* **Microsoft Power BI Desktop**
* **Power Query**
* **DAX**
* **Kaggle Dataset**

---

# 14. Project File

The final Power BI report is provided as:

**`FORMATTING TASK-POWER BI.pbix`**

The `.pbix` file contains the imported dataset, data transformations, calculated measures, visualizations, formatting, and interactive dashboard.

---

# 15. Final Dashboard Screenshot

A high-resolution screenshot of the completed Power BI dashboard should be included with the submission.

**Screenshot File:**
`PowerBI_Dashboard_Screenshot.png`

The screenshot represents the final single-page dashboard after applying data cleaning, visualization, formatting, interaction, alignment, and layout requirements.

---

# 16. Requirement Completion Checklist

| Assignment Requirement                       | Status    |
| -------------------------------------------- | --------- |
| Download and load a relevant Kaggle dataset  | Completed |
| Perform data cleaning                        | Completed |
| Handle missing values                        | Completed |
| Correct data types                           | Completed |
| Remove duplicates                            | Completed |
| Create calculated columns/measures           | Completed |
| Build at least 3 visualizations              | Completed |
| Create KPI cards                             | Completed |
| Apply consistent theme                       | Completed |
| Apply custom colors                          | Completed |
| Format fonts                                 | Completed |
| Configure axis titles                        | Completed |
| Configure data labels                        | Completed |
| Configure tooltips                           | Completed |
| Add interactive slicers                      | Completed |
| Enable visual interactions                   | Completed |
| Arrange visuals on a single page             | Completed |
| Apply alignment and spacing                  | Completed |
| Add dashboard title                          | Completed |
| Add subtitle                                 | Completed |
| Add description textbox                      | Completed |
| Export Power BI `.pbix` file                 | Completed |
| Capture high-resolution dashboard screenshot | Completed |

---

# 17. Conclusion

This project demonstrates the complete process of developing a professional Power BI dashboard, from importing and cleaning a Kaggle dataset to creating measures, visualizations, interactive filters, and applying consistent formatting.

The final dashboard provides a clear and interactive way to analyze sales performance while demonstrating Power BI dashboard design and formatting best practices.
