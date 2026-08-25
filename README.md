# 📚 Book Sales Data Analysis Using Python

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a book sales dataset using Python.

The analysis focuses on understanding patterns and relationships across book ratings, genres, languages, authors, publishers, pricing, revenue, sales rank, and units sold.

The project follows a practical data analytics workflow:

**Data Loading → Data Inspection → Data Cleaning → Exploratory Data Analysis → Visualization → Business Insights**

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Understand the structure and quality of the book sales dataset
- Identify missing and duplicate records
- Analyze unique values and categorical variables
- Explore book distribution by genre and language
- Analyze book ratings across different genres
- Study the relationship between book ratings and rating counts
- Analyze the relationship between sale price and units sold
- Compare units sold across author-rating categories
- Analyze author-level sales performance
- Examine publisher revenue
- Analyze total units sold by publishing year

---

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains book-related information including:

- Author
- Publishing Year
- Book Name
- Language Code
- Author Rating
- Book Average Rating
- Book Ratings Count
- Genre
- Gross Sales
- Publisher Revenue
- Sale Price
- Sales Rank
- Publisher
- Units Sold

---

## 🧹 Data Cleaning & Preparation

The project includes several data-quality checks and preparation steps:

- Checked dataset structure and data types
- Checked missing values
- Checked duplicate records
- Checked unique values in each column
- Removed records with missing book names
- Filtered publishing-year values for the analysis
- Reviewed categorical and numerical variables before EDA

---

## 🔍 Exploratory Data Analysis

### 1. Publishing Year Analysis

A histogram is used to understand the distribution of books across publishing years.

### 2. Genre Analysis

The number of books in each genre is analyzed to identify the most represented genres.

### 3. Language Analysis

Language codes are grouped and counted to understand the language composition of the dataset.

### 4. Book Ratings by Genre

A boxplot is used to compare the distribution of average book ratings across genres.

### 5. Book Average Rating vs Book Ratings Count

A scatter plot is used to investigate whether books with higher average ratings tend to receive more ratings.

### 6. Sale Price vs Units Sold

A scatter plot is used to examine the relationship between book sale price and the number of units sold.

### 7. Author-Level Sales Analysis

Sales-related information is analyzed at the author level to compare author performance.

### 8. Publisher Revenue Analysis

Publisher revenue is analyzed to compare revenue performance across publishers.

### 9. Author Rating vs Units Sold

A boxplot is used to compare the distribution of units sold across author-rating categories.

### 10. Total Units Sold by Publishing Year

A line chart is used to analyze changes in total units sold across publishing years.

---

## 📊 Key Insights

Some observations from the analysis include:

- `eng` is the most common language code in the dataset, followed by `en-US`.
- The dataset contains multiple genres, with genre composition analyzed using count-based visualizations.
- Book average ratings are concentrated around the middle-to-upper rating range, while ratings count varies       considerably.
- The relationship between average book rating and number of ratings does not appear to be strongly linear from the scatter plot.
- Units sold vary considerably across author-rating categories, with several high-sales outliers.
- Total units sold fluctuate substantially across publishing years.
- Author and publisher-level analysis provides useful ways to compare sales and revenue performance.

> **Note:** These are descriptive findings from the dataset and should not be interpreted as causal relationships.

---

## 📈 Visualizations

The project includes:

- Publishing Year Distribution
- Book Distribution by Genre
- Distribution of Books by Language
- Book Ratings by Genre
- Book Average Rating vs Book Ratings Count
- Sale Price vs Units Sold
- Units Sold by Author Rating
- Publisher Revenue Analysis
- Total Units Sold by Publishing Year

---

