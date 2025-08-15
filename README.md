# Netflix-Data-Analysis
Data analysis and visualization of Netflix dataset using Python.
📌 Overview

This project focuses on exploring and analyzing the Netflix dataset to uncover trends, patterns, and insights.
We use Python along with pandas, NumPy, and Matplotlib/Seaborn for data cleaning, transformation, and visualization.
The dataset contains information about TV Shows and Movies available on Netflix, including details like title, cast, director, release year, rating, and more.
Objectives

Clean and preprocess Netflix data.
Explore and visualize trends in Netflix content.
Answer key business and data questions such as:
How has Netflix content grown over the years?
What are the most common genres?
Which countries produce the most Netflix content?
Ratings distribution for movies and TV shows.
Relationship between release year and duration.

📂 Dataset
The dataset is publicly available on Kaggle - Netflix Movies and TV Shows.
Key Columns:
show_id – Unique identifier
type – Movie or TV Show
title – Name of the content
director – Director name
cast – Main cast members
country – Country of production
date_added – Date when added to Netflix
release_year – Original release year
rating – Audience rating (e.g., PG, TV-MA)
duration – Duration in minutes or seasons
listed_in – Genre(s)
description – Short summary

🛠️ Technologies Used
Python 3
Pandas – Data manipulation
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Statistical plots
Jupyter Notebook – Code execution and analysis

📊 Key Steps in the Project
1. Data Loading
import pandas as pd
df = pd.read_csv("netflix_titles.csv")

2. Data Cleaning
Handle missing values (NaN)
Remove duplicates
Convert data types
Standardize column formats

3. Data Exploration (EDA)
Content type distribution
Top 10 genres
Country-wise content count
Trends in content release over the years
Ratings analysis

4. Data Visualization

Example:
import seaborn as sns
import matplotlib.pyplot as plt
sns.countplot(data=df, x="type", palette="coolwarm")
plt.title("Movies vs TV Shows on Netflix")
plt.show()

5. Insights
Movies dominate Netflix's content library.
The number of releases increased significantly after 2015.
The United States, India, and the UK are the top contributors.
Common genres include Dramas, Comedies, and Documentaries.
📈 Sample Visualizations
📊 Movies vs TV Shows bar chart
🌍 Top Countries producing Netflix content
📅 Release year trends
🎭 Most frequent genres
⭐ Rating distribution

🚀 How to Run This Project
Prerequisites
Make sure you have the following installed:
Python 3.x
Jupyter Notebook (or Google Colab)

Required libraries:
pip install pandas numpy matplotlib seaborn

Steps:
Clone this repository:
git clone https://github.com/MuhammadSuleman101/netflix-analysis.git

Navigate to the project folder:
cd netflix-analysis
Open the Jupyter Notebook:
jupyter notebook
Run the cells step-by-step.

📌 Future Improvements
Add interactive dashboards using Plotly or Power BI.
Perform time series analysis on release trends.
Implement content recommendation using ML.


👨‍💻 Author
Muhammad Suleman
📧 Email: sulemanyaqoob0309@gmail.com
🌐 GitHub: MuhammadSuleman101
