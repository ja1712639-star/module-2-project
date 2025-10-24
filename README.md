#  Amazon Prime Video EDA Project

## Overview

This project performs "Exploratory Data Analysis (EDA)" on the Amazon Prime Video dataset to understand content diversity, audience preferences, and platform trends.
The goal is to clean the data, visualize key insights, and summarize findings related to movies and TV shows available in the United States.



## Business Context

In today’s competitive streaming industry, platforms like "Amazon Prime Video" are expanding their content libraries to cater to diverse audiences.
Through this project, we aim to uncover:

  Which genres and regions dominate the platform
  How the content library has evolved over time
  Which titles are the most popular or highly rated

These insights can help improve "content strategy, audience engagement and investment decisions".

 ## Objectives

 Explore and understand the structure of the dataset
 Handle missing values and duplicates
 Identify content trends by genre, region, and release year
 Analyze IMDb scores and TMDB popularity
 Create visualizations to present findings clearly
 Conclude with meaningful business insights

## Tools & Libraries Used

 Python
 Pandas
 NumPy
 Matplotlib
 Seaborn
 Colab Notebook

##  Project Structure

AmazonPrime_EDA_Project/
│
├── data/                 → titles.csv and credits.csv  
├── notebooks/            → colab notebooks for analysis  
├── images/               → Saved visualizations  
├── presentation/         → PPT or video presentation  
└── README.md             → Project documentation  

##  Steps Performed

1. Data Loading & Exploration – Used 'head()', 'info()', 'shape ()' and 'describe()' to understand the dataset.
2. Data Dictionary – Explained all columns from both files.
3. Handling Missing Values – Instead of dropping missing rows, replace with unknown for text and median for numbers.
4. Data Cleaning – Combined `titles.csv` and `credits.csv` using the 'id' column.
5. Visualization (5 types used):

    Bar chart: count of Movies vs TV Shows
    Pie chart: genre distribution
    Histogram: release year trends
    Scatter plot: IMDb score vs TMDB popularity
    Heatmap: correlation of numeric features
     
6. Conclusion –
The analysis shows that Amazon Prime mainly features movies, with Drama, Comedy, and Thriller as the most popular genres. The United States, India, and the United Kingdom are the top content-producing countries. These insights highlight Prime Video’s diverse catalog and global reach in the streaming industry.

##  Key Insights

 Drama and Comedy are the most frequent genres.
 Movies make up the majority of Prime Video’s catalog.
 Content growth increased after 2015.
 IMDb and TMDB ratings are positively correlated.

## How to Run

1.  Open the notebook:

   [notebooks/AmazonPrime_EDA.ipynb](https://colab.research.google.com/drive/1-EVoZGhL3Hx8YqYaKgUUwphPtMWCcH06?usp=sharing)
  
2. Run all cells to generate outputs and visualizations.

## Presentations
https://meeting.zoho.in/meeting/public/videoprv?recordingId=911ca8ad5a41fe37244e236d3873071ced7a510765fcd7e55f5383fe74e61b5b





