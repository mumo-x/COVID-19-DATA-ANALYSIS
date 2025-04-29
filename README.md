# COVID-19 Testing Analysis – Data Refresh and Visualization Project

This project provides a basic Python-based data analysis pipeline using publicly available COVID-19 testing data from the **European Centre for Disease Prevention and Control (ECDC)**.

📊 **Dataset Source:**  
[European Centre for Disease Prevention and Control – COVID-19 Testing Data](https://www.ecdc.europa.eu/en/publications-data/covid-19-testing)

---

## 📌 Project Objectives

The main goals of this project are to:

- **Refresh and clean** the latest testing data.
- Perform **exploratory data analysis (EDA)** to extract insights.
- Build **visualizations** to represent trends and comparisons.
- Deliver a concise **reporting output** for further use or publication.

---

## 🧰 Project Components

### 1. Data Cleaning
- Handling missing or inconsistent values.
- Parsing dates and standardizing column formats.
- Filtering relevant country-level data.

### 2. Exploratory Analysis
- Identifying trends in testing volume and test positivity rates.
- Comparing statistics across European countries.

### 3. Visualization
- Line charts and bar plots for time series and country comparisons.
- A **feature importance plot** (see note below).

### 4. Reporting
- Summarized output via plots and in-notebook markdown commentary.

---

## ⚠️ Licensing Notice

Some code and visualizations—such as the **feature importance plot**—include adaptations from third-party sources. Specifically, credit is given to **[baxterromero44]** for the original plotting structure.

Please ensure compliance with any relevant licenses before reusing or modifying this portion of the project.

---

## 💻 Getting Started

### 🔧 Prerequisites

Ensure you have Python 3.7+ and the following libraries installed:

```bash
pandas
matplotlib
seaborn
numpy
requests
