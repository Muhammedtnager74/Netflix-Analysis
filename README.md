# 🎬 Netflix Data Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing Netflix content data to uncover valuable insights about content growth, distribution, ratings, countries, and genres.  

The dataset was cleaned, transformed, and analyzed using Python, then visualized through an interactive Power BI dashboard.

---

## 🎯 Objectives

- Understand Netflix content expansion over time
- Compare Movies vs TV Shows
- Identify top contributing countries
- Analyze audience ratings distribution
- Explore most common genres
- Build an interactive business dashboard

---

## 🛠 Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Jupyter Notebook

- **Power BI**
  - Data Modeling
  - DAX Measures
  - Interactive Dashboard

- **Git & GitHub**
  - Version Control
  - Project Publishing

---

## 🧹 Data Cleaning Process

The raw dataset required several preprocessing steps:

- Handling missing values
- Removing duplicates
- Converting `date_added` to datetime format
- Extracting numeric values from `duration`
- Splitting multi-value columns:
  - `country`
  - `listed_in`
- Standardizing text fields
- Creating new columns:
  - `year_added`
  - `month_added`

---

## 📊 Dashboard Pages

### 🔹 Page 1: Executive Overview

Includes:

- Total Titles
- Total Movies
- Total TV Shows
- Content Growth Over Time
- Rating Distribution
- Top Countries
- Movies vs TV Shows

---

### 🔹 Page 2: Content Deep Dive

Includes:

- Top Genres
- Top Directors
- Average Movie Duration
- Average TV Show Seasons
- Monthly Content Additions
- Interactive Filters

---

## 🔍 Key Insights

- Netflix content additions increased rapidly after 2015
- Peak growth occurred in **2019**
- Movies dominate the platform over TV Shows
- Most content is rated **TV-MA** and **TV-14**
- United States contributes the highest number of titles
- India is the second-largest contributor
- Most TV Shows have **1–2 seasons**

---

## 📁 Project Files

```text
Netflix-Analysis/
│── Dataset/
│── data_cleaning.ipynb
│── Netflix Dashboard.pbix
│── Dataset_After_Transform.csv
│── README.md
