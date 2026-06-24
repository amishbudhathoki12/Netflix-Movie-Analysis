# Netflix Movie Analysis

## Project Overview

This project focuses on analyzing Netflix movies using a movie dataset containing information about popularity, genres, ratings, voting, and release dates.

The main objective of this analysis is to explore movie trends, understand genre performance, analyze popularity patterns, and extract meaningful insights from Netflix movie data.

The project follows a complete data analytics workflow including data loading, data cleaning, exploratory data analysis (EDA), and visualization using Python.

---

# Dataset Summary

The dataset contains:

- **Rows:** 9827
- **Columns:** 9

### Dataset Features:

**Movie Information**
- Movie title
- Overview
- Original language

**Movie Details**
- Genre
- Popularity
- Release date

**Voting Information**
- Vote count
- Vote average

### Data Quality

- No missing values were found in the original dataset.
- Duplicate values were checked and handled during the cleaning process.

---

# Tools & Technologies

## Programming Language

- Python

## Libraries Used

### Pandas
Used for:
- Data loading
- Data cleaning
- Data transformation
- Handling duplicates
- Data type conversion

### Matplotlib & Seaborn
Used for:
- Data visualization
- Trend analysis
- Distribution analysis
- Statistical visualization

## Environment

- JupyterLab
- VS Code

---

# Project Workflow

## 1. Data Loading

- Imported the dataset into JupyterLab using Pandas.
- Created a copy of the original dataset for safe data manipulation.
- Reviewed the initial structure of the dataset.

---

## 2. Exploratory Data Analysis (EDA)

Performed EDA to understand the dataset and identify patterns.

Steps performed:

- Checked dataset information and data types
- Reviewed first few records
- Analyzed genre distribution
- Checked duplicate records
- Generated summary statistics
- Examined unique values

---

## 3. Data Cleaning

Data preparation steps included:

- Converted release date from object type to datetime format
- Removed unnecessary columns:
  - Overview
  - Original language
  - Poster URL

- Categorized vote average into different rating categories
- Handled missing values after transformation
- Split and expanded genre values for better analysis
- Converted genre data into categorical format

---

# Data Visualization

Visualizations were created using Matplotlib and Seaborn.

Analysis included:

- Genre distribution analysis
- Vote average distribution
- Movie popularity analysis
- Highest and lowest popularity movies
- Release year distribution

---

# Key Insights

## 1. Most Frequent Genre

The **Drama** genre is the most frequent genre in the dataset, appearing more than 14% among all genres.

---

## 2. Most Popular Genre Based on Votes

Around 25.5% of movies received popular votes.

Drama remained one of the most popular genres among viewers, contributing more than 18.5% of total movie popularity.

---

## 3. Highest Popularity Movie

**Spider-Man: No Way Home** achieved the highest popularity score in the dataset.

Genres:
- Action
- Adventure
- Science Fiction

---

## 4. Lowest Popularity Movie

**The United States, Thread** recorded the lowest popularity score.

Genres:
- Music
- Drama
- War
- Sci-Fi
- History

---

## 5. Highest Movie Release Year

The year **2020** had the highest number of movie releases in the dataset.

---

# Project Structure
Netflix-Movie-Analysis/

│
├── Dataset/
│ └── movies.csv
│
├── Notebook/
│ └── Netflix_Analysis.ipynb
│
├── Images/
│ └── visualizations/
│
├── Report/
│ └── Netflix_Analysis_Report.pdf
│
├── requirements.txt
│
└── README.md


---

# How to Run This Project

### 1. Clone Repository

```bash
git clone <repository-url>
