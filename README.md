# 🌍 Exploratory Data Analysis in Pandas

This repository contains my Python notebook for performing exploratory data analysis (EDA) on a world population dataset using **Pandas**, **Seaborn**, and **Matplotlib**. The project focuses on understanding population patterns across countries and continents through summary statistics, correlations, grouping, and visualisations.

---

## 📌 Introduction

This project demonstrates a basic exploratory data analysis workflow in Python using **Pandas**.

The notebook works with a global population dataset and explores how population measures vary across continents and over time. The analysis includes descriptive statistics, missing-value checks, correlation analysis, grouping by continent, trend comparisons, and visualisation.

This project highlights practical skills in:

- exploratory data analysis in Python
- data summarisation with Pandas
- correlation analysis
- grouping and aggregation
- data visualisation with Seaborn and Matplotlib
- identifying high-level population trends

---

## 💡 Motivation

Before building models or drawing conclusions from a dataset, it is important to understand its structure, quality, and patterns.

This project uses EDA to answer questions such as:

- Which countries or regions have the largest population shares?
- How do population trends differ across continents?
- Are population-related variables strongly correlated?
- What does the distribution of population measures look like?

The goal is to use Python to turn raw population data into meaningful summary insights.

---

## 📂 Dataset Description

The project uses a CSV file:

- `world_population.csv`

The dataset contains country-level population information, including:

- continent
- population in multiple years
- population density
- growth-related fields
- world population percentage

The notebook explores both cross-sectional and time-based aspects of the dataset.

---

## 🔍 Exploratory Analysis Workflow

The notebook follows a simple EDA process:

### 1. Import libraries
The project uses:

- `pandas`
- `seaborn`
- `matplotlib.pyplot`

These libraries support data manipulation and visual exploration.

### 2. Load the dataset
The dataset is loaded into a Pandas DataFrame using:

```python
df = pd.read_csv("world_population.csv")
