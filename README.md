# 🎬 Movie Data Analysis using Python

A comprehensive **Data Cleaning and Exploratory Data Analysis (EDA)** project performed on a real-world movie dataset using **Python, Pandas, and NumPy**. This project demonstrates the complete workflow of importing data, cleaning missing values, feature engineering, and extracting meaningful business insights through exploratory analysis.

---

## 📌 Project Overview

The entertainment industry generates massive amounts of data related to movie production, ratings, revenues, budgets, and audience engagement. Raw datasets often contain missing values, duplicate records, and inconsistent information that make analysis difficult.

This project focuses on preparing the movie dataset through data preprocessing techniques and performing exploratory data analysis to answer key business questions, including:

- Which movies generated the highest profits?
- Which directors consistently produce highly rated movies?
- Which genre combinations perform the best?
- Which actors receive the highest audience and critic appreciation?
- Which foreign-language movies rank among IMDb's top-rated films?

---

## 🎯 Project Objectives

- Import and inspect the movie dataset.
- Understand the dataset structure.
- Handle missing values.
- Remove unnecessary columns.
- Eliminate duplicate records.
- Perform feature engineering.
- Calculate movie profits.
- Identify the Top 10 profitable movies.
- Generate the IMDb Top 250 list.
- Analyze top-performing directors.
- Identify the most successful genre combinations.
- Compare audience and critic favorite actors.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Jupyter Notebook | Development Environment |
| CSV Dataset | Data Source |

---

## 📂 Project Structure

```
Movie-Data-Analysis/
│
├── Movie_Data_Analysis.ipynb
├── Movie+Assignment+Data.csv
└── README.md/
```

---

## 📊 Dataset Information

The dataset contains detailed information about movies including:

- Movie Title
- Director Name
- Actor Names
- Genres
- Budget
- Gross Revenue
- IMDb Score
- Number of User Reviews
- Number of Critic Reviews
- Language
- Country
- Facebook Likes
- Movie Duration

---

## 🔄 Project Workflow

```
Movie Dataset
      │
      ▼
Import Libraries
      │
      ▼
Load Dataset
      │
      ▼
Dataset Inspection
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Business Insights
      │
      ▼
Conclusion
```

---

# 📖 Project Steps

## Step 1 – Import Required Libraries

- Import Pandas
- Import NumPy
- Suppress warning messages

---

## Step 2 – Load Dataset

- Read CSV file
- Create DataFrame
- Preview dataset

---

## Step 3 – Dataset Inspection

Performed:

- Dataset Shape
- Dataset Information
- Data Types
- Statistical Summary
- Column Names

---

## Step 4 – Missing Value Analysis

- Calculate missing values
- Calculate missing value percentages
- Identify incomplete features

---

## Step 5 – Data Cleaning

Cleaning includes:

- Remove unnecessary columns
- Remove incomplete records
- Fill missing language values
- Remove duplicate records

---

## Step 6 – Feature Engineering

New feature created:

- **Profit = Gross Revenue − Budget**

Financial columns converted into **Million USD** for better readability.

---

## Step 7 – Exploratory Data Analysis

The following analyses were performed:

### 💰 Profit Analysis

- Calculate movie profits
- Sort movies by profitability
- Identify Top 10 profitable movies

---

### ⭐ IMDb Top 250 Analysis

- Filter highly rated movies
- Apply minimum vote threshold
- Rank movies

---

### 🌍 Foreign Language Movie Analysis

- Extract non-English movies
- Identify highest-rated international films

---

### 🎬 Director Analysis

- Group movies by director
- Calculate average IMDb score
- Rank directors

---

### 🎭 Genre Analysis

- Split movie genres
- Analyze genre combinations
- Calculate average gross revenue

---

### 👨‍🎤 Actor Analysis

Actors compared:

- Meryl Streep
- Leonardo DiCaprio
- Brad Pitt

Comparison Metrics:

- User Reviews
- Critic Reviews

---

# 📈 Key Findings

✔ Successfully cleaned the dataset.

✔ Removed missing values.

✔ Removed duplicate records.

✔ Calculated movie profitability.

✔ Identified Top 10 profitable movies.

✔ Generated IMDb Top 250 ranking.

✔ Identified highest-rated directors.

✔ Determined most profitable genre combinations.

✔ Compared audience and critic favorite actors.

---

# 📊 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Manipulation
- Data Transformation
- Business Insight Generation
- Pandas
- NumPy
- Python Programming

---

# 🚀 Future Improvements

The project can be extended by:

- Building a Movie Revenue Prediction Model
- Creating a Movie Recommendation System
- Performing Sentiment Analysis on Reviews
- Building Interactive Dashboards using Tableau or Power BI
- Deploying the project using Streamlit or Flask

---

# 🎯 Learning Outcomes

Through this project, the following concepts were practiced:

- Working with real-world datasets
- Handling missing values
- Removing duplicate records
- Data preprocessing techniques
- Feature engineering
- Exploratory Data Analysis
- GroupBy operations
- Sorting and Filtering
- Aggregation Functions
- Business Insight Extraction

---

# 👨‍💻 Author

**Hariharan A**

B.Tech – Computer Science and Engineering

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
