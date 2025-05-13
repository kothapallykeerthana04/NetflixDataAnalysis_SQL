# NetflixDataAnalysis_SQL
# 📺 Netflix Data Analysis Using SQL

A data analysis project using SQL to explore trends in the Netflix Movies and TV Shows dataset sourced from Kaggle.

---

## 📌 Project Objective

- Analyze Netflix content using SQL
- Uncover insights on content type, genre popularity, country dominance, and release patterns
- Gain hands-on SQL experience with real-world data

---

## 📊 Dataset Overview

- 📁 Dataset: `netflix_titles.csv`
- 🗂 Columns include:
  - `title`, `type`, `director`, `cast`, `country`
  - `release_year`, `date_added`, `rating`, `duration`, `listed_in`

📍 Source: [Kaggle – Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 🛠 Tools Used

- SQL (PostgreSQL / MySQL syntax)
- Kaggle (data source)
- Canva / PowerPoint (presentation)

**SCHEMA**

DROP TABLE IF EXISTS netflix;

CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);
