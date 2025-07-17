# UPI-Transactions-Dashboard

This project involves building an interactive Power BI dashboard for analyzing UPI (Unified Payments Interface) transaction data. The goal is to explore transaction trends, demographic insights, and provide interactive visualizations to enhance data understanding.

## Project Overview

This Power BI project includes:

- Loading and profiling UPI transaction data.
- Creating slicers for dynamic filtering by parameters like age group and transaction pages.
- Adding line charts and matrix visuals for trend and detailed analysis.
- Applying conditional formatting and syncing slicers across visuals.
- Designing bookmarks for navigation and focused insights.
- Publishing the final report to Power BI Service.

## Dataset

### Source

The dataset used in this project is provided as:

- **File Name:** `UPI Transactions.xlsx`

### Dataset Structure

The dataset contains information related to UPI transactions, including:

- **Transaction ID:** Unique identifier for each transaction.
- **Date:** Date of the transaction.
- **Transaction Amount:** The amount transacted.
- **User Age:** Age of the user making the transaction.
- **Page:** The category or type of transaction/page.
- **Remaining Balance:** The balance remaining after the transaction.
- Additional fields relevant to transaction profiling and demographic segmentation.

## Tech Stack

- **Power BI Desktop:** For data modeling, visualization, and dashboard creation.
- **Microsoft Excel:** For dataset preparation and preliminary analysis.
- **Power BI Service:** For publishing and sharing reports online.



## Features

- **Data Profiling:** Assessing data quality and structure.
- **Slicers:** 
  - Custom slicers for filtering by age group and pages.
  - Proper formatting and positioning for better UX.
- **Visualizations:**
  - Line chart for transaction trends over time.
  - Matrix visual for a tabular view of transactions and balances.
- **Conditional Formatting:** Highlights key data points within visuals.
- **Bookmarks:** 
  - Bookmark for viewing transaction summaries.
  - Bookmark for checking remaining balances.
- **Publishing:** Final report published to Power BI Service.

## Screenshots / Demo

### Page 1 - Transactions Overview

This page presents a **line chart** depicting the balance trends by month for the year 2024. Multiple slicers allow dynamic filtering by parameters such as Bank Name, City, Device Type, Gender, Age Group, Merchant Name, Payment Method, Purpose, and Transaction Type.

![Page 1 - Transactions Overview](path/to/page1-overview.png)

### Page 2 - Transactions Matrix

This page contains a **Matrix visual** that provides a tabular view of transactions, showing detailed metrics such as transaction amounts, balances, and other segmented insights based on the selected filters.

![Page 2 - Transactions Matrix](path/to/page2-matrix.png)



## Learning Outcomes

- Data loading and profiling in Power BI.
- Creating interactive reports with slicers, charts, and bookmarks.
- Applying conditional formatting and slicer syncing.
- Publishing reports to the Power BI Service for collaboration.
