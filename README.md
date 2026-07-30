# Automated Data Cleaning & Reporting System

## 📌 Project Overview

The **Automated Data Cleaning & Reporting System** is a Python-based data analytics project developed to automate the process of cleaning, preprocessing, and analyzing real-world datasets. This project uses a hotel booking dataset to identify and handle missing values, remove duplicate records, generate summary statistics, and create insightful visualizations for data-driven decision-making.

---

## 🎯 Project Objective

The objective of this project is to automate data cleaning and reporting tasks to improve data quality, reduce manual effort, and generate meaningful insights through visualization.

---

## ✨ Key Features

- Import and analyze a real-world dataset
- Perform data quality assessment
- Identify and handle missing values
- Remove duplicate records
- Generate descriptive statistics
- Create insightful data visualizations
- Export the cleaned dataset for further analysis

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib

---

## 📂 Dataset

**Dataset:** Hotel Bookings Dataset

The dataset contains booking information for city and resort hotels, including customer details, booking dates, cancellations, stay duration, and more.

---

## 🔄 Project Workflow

1. Import required libraries
2. Load the dataset
3. Inspect the data
4. Analyze missing values
5. Detect duplicate records
6. Clean the dataset
7. Generate statistical summary
8. Create data visualizations
9. Export the cleaned dataset

---

## 📊 Visualizations

The project includes the following visualizations:

- Booking Cancellation Distribution
- Hotel Type Distribution
- Monthly Bookings
- Lead Time Distribution

---

## 📈 Results

### Original Dataset
- Rows: **119,390**
- Columns: **32**

### Cleaned Dataset
- Rows: **87,370**
- Columns: **31**

### Cleaning Operations Performed

- Removed the `company` column due to excessive missing values.
- Filled missing values in `agent`, `country`, and `children`.
- Removed duplicate records.
- Generated descriptive statistics.
- Created analytical visualizations.
- Exported the cleaned dataset.

---

## 📁 Repository Structure

```
Automated-Data-Cleaning-Reporting-System/
│
├── Automated_Data_Cleaning_Reporting_System.ipynb
├── hotel_bookings.csv
├── cleaned_hotel_bookings.csv
└── README.md
```




