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

### Usage

You can find the dataset in this repository. It can be opened with Excel or imported directly into Power BI Desktop for analysis.

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

## How to Use

1. Clone or download this repository.
2. Open the `UPI Transactions.xlsx` file for a data preview.
3. Open the `.pbix` Power BI report file (provided) using Power BI Desktop.
4. Refresh the data if needed or connect your own dataset with the same schema.
5. Explore the dashboard using available filters, slicers, and bookmarks.

## Requirements

- Power BI Desktop (latest version recommended)
- Microsoft Excel (optional, for viewing dataset)

## Learning Outcomes

- Data loading and profiling in Power BI.
- Creating interactive reports with slicers, charts, and bookmarks.
- Applying conditional formatting and slicer syncing.
- Publishing reports to the Power BI Service for collaboration.
