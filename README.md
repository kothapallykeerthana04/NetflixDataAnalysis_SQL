# NetflixDataAnalysis_SQL
# 📺 Netflix Data Analysis Using SQL

A data analysis project using SQL to explore trends in the Netflix Movies and TV Shows dataset sourced from Kaggle.

---

## 📌 Project Objective

- Analyze Netflix content using SQL
- Uncover insights on content type, genre popularity, country dominance, and release patterns
- Gain hands-on SQL experience with real-world data

---

## 🎯 Objectives

- Analyze the distribution of Movies vs TV Shows
- Identify top countries, genres, and content ratings
- Discover trends in content release over the years
- Classify content into audience categories (Kids, Family, Teens, Adults)
- Rank titles by release year within each country
- Build stored procedures to fetch titles by actor

📍 Source: [Kaggle – Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 🛠 Tools Used

- SQL (PostgreSQL / MySQL syntax)
- Kaggle (data source)
- Canva / PowerPoint (presentation)


---

## 📌 Key SQL Concepts Used

- `GROUP BY`, `ORDER BY`, `HAVING`
- `CASE` statements
- `RANK() OVER (PARTITION BY ...)` window functions
- `LIKE`, `FIND_IN_SET`, and string functions
- Stored Procedures

---


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


**Insights Gained**
Movies account for a larger portion of Netflix's content

The United States contributes the most content

Drama and International content are most popular

TV-MA and TV-14 are dominant maturity ratings

Recent years show a significant increase in title releases
