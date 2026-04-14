# Netflix Data Analysis & Recommendation System 📊🎬

## 📌 Project Summary

This project performs an exploratory data analysis (EDA) on Netflix content to uncover patterns in content type, genres, ratings, duration, and growth trends over time.
Additionally, a **content-based recommendation system** is built to suggest similar titles based on textual and categorical features.

---

## 📌 Project Objective

* Analyze Netflix dataset to identify content trends
* Compare Movies vs TV Shows across multiple dimensions
* Understand genre popularity, ratings, and duration patterns
* Study time-based trends in content addition
* Build a recommendation system to suggest similar content

---

## 🛠 Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn (TF-IDF, Cosine Similarity)

---

## 📂 Project Structure

* `notebooks/` → Complete EDA + Recommendation System
* `requirements.txt` → Dependencies

---

## 🔍 Analysis Performed

### 1. Data Preparation

* Handling Missing Values
* Feature Engineering

---

### 2. Exploratory Data Analysis (EDA)

#### 🔹 Univariate Analysis

* Content distribution: Movies vs TV Shows
* Top 10 directors
* Top cast (actors & actresses)
* Top content-producing countries
* Release trends over time
* Rating distribution
* Genre distribution
* Average movie duration
* Average number of seasons in TV Shows
* Word patterns in adult content descriptions
* Titles added by year, month, and day

---

#### 🔹 Bivariate Analysis

* Rating distribution across Movies & TV Shows
* Content trends over years
* Content distribution across top countries
* Content distribution across top directors
* Yearly & monthly trends of content addition
* Genre trends over time
* Movie duration across genres
* Children's ratings distribution by country
* TV show seasons trend over time

---

## 🤖 Recommendation System

A **content-based recommendation system** is implemented using:

* TF-IDF Vectorization
* Cosine Similarity
* Combined features:

  * Description
  * Genre
  * Cast
  * Director

### 🔹 How it works

* Converts text data into numerical vectors
* Computes similarity between titles
* Recommends top similar content based on input title

---

## 📈 Key Insights

* Movies are more prevalent than TV Shows on Netflix
* Majority of content has been added after 2015
* Drama and Comedy dominate as the most common genres
* Content production is concentrated in a few top countries
* Movie durations vary significantly by genre
* TV Shows maintain relatively stable season counts over time
* Genre trends evolve, reflecting changing audience preferences

---

## 📌 Future Improvements

* Build interactive dashboards (Power BI / Plotly)
* Optimize recommendation system performance
* Add hybrid recommendation techniques
* Deploy as a web application

---

## 📌 Author

**Shravan Vemula**
