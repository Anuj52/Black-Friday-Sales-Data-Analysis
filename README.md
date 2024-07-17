# Black Friday Sales Data Analysis

## Project Overview

Black Friday is a significant shopping event known for deep discounts and special deals on various products. Our dataset contains 537,578 rows and 12 columns, and our primary goal is to analyze this data to extract valuable market insights that can benefit the company.

This project is divided into the following parts:

1. Dataset Walkthrough
2. Analyzing Columns
3. Analyzing Gender
4. Analyzing Age & Marital Status
5. Multi Column Analysis
6. Occupation and Products Analysis
7. Combining Gender & Marital Status

## Prerequisites

- Pandas
- Numpy
- Seaborn

## Project Parts

### 1. Dataset Walkthrough

- **Objective:** Understand the dataset's structure, column names, data types, and identify any null values.
- **Outcome:** Identified many null values in `Product_Category_2` and `Product_Category_3`. Decided to delete these columns to avoid data loss issues.

### 2. Analyzing Columns

- **Objective:** Use `unique()` and `nunique()` functions to determine the number of unique values in each column.
- **Outcome:** Determined the total number of customers (`User_ID`) and products (`Product_ID`), as well as unique values in columns like `Gender` and `Age`.

### 3. Analyzing Gender

- **Objective:** Analyze the `Gender` column to see which gender has more entries and which gender is purchasing more.
- **Outcome:** Found that the dataset contains more male data than female. Grouped data by gender and visualized the findings using pie charts and bar plots.

### 4. Analyzing Age & Marital Status

- **Objective:** Analyze the `Age` and `Marital_Status` columns to understand purchasing patterns.
- **Outcome:** Identified the age group making the maximum number of orders and the highest purchasing amount. Found that 60% of people are unmarried and 40% are married. Visualized findings using pie charts and bar plots.

### 5. Multi Column Analysis

- **Objective:** Perform multi-column analysis to get deeper insights using Seaborn for visualization.
- **Outcome:** Conducted analysis combining `Age` and `Gender`, using Seaborn to create visualizations with the hue parameter for better interpretation.

### 6. Occupation and Products Analysis

- **Objective:** Analyze `Occupation`, `Product_ID`, and `Product_Category_1` columns.
- **Outcome:** Used count plots and bar plots to understand data distribution and identify the product with the maximum purchasing amount.

### 7. Combining Gender & Marital Status

- **Objective:** Combine `Gender` and `Marital_Status` for analysis.
- **Outcome:** Performed various data visualizations using Seaborn to derive insights when combining these two columns.

## How to Run the Project

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd <repository-directory>
