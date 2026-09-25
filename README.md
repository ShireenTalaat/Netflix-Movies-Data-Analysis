# Netflix Movies Data Analysis Dashboard

## 📊 Overview

This repository contains a **Netflix Movies Data Analysis Dashboard** built with **Microsoft Power BI**. Designed with a custom dark theme mimicking the Netflix brand identity (Black, Red, and White), this dashboard provides a comprehensive analysis of a curated dataset of top-rated movies.

The dashboard focuses on key metrics such as IMDb ratings, genre distribution, movie duration, and age ratings to uncover trends in high-quality cinema.

---

## 🖼️ Dashboard Preview

![Netflix.jpg](https://github.com/ShireenTalaat/Netflix-Movies-Data-Analysis/blob/main/Netflix.jpg)
---

## 📈 Key Performance Indicators (KPIs)

| Metric | Value |
| :--- | :--- |
| **Total Movies Analyzed** | 50 |
| **Average Rating** | 8.26 |
| **Total Genres** | 21 |

---

## 📋 Dashboard Components

### 1. Movie Count by Age Rating (Donut Chart)
A breakdown of the dataset by MPAA age ratings.
*   **R (Restricted):** 31 movies (62%) - The dominant category, reflecting the mature themes of many top-rated films.
*   **PG-13:** 14 movies (28%).
*   **PG:** 5 movies (10%).

### 2. IMDb Rating Distribution (Bar Chart)
A histogram showing the frequency of IMDb ratings within the dataset.
*   The ratings are heavily skewed towards the higher end (8.0 - 9.0+), consistent with a "Top Rated" dataset.
*   There is a significant cluster of movies rated around 8.0 and 9.0.

### 3. Top 10 Highest-Rated Movies (Horizontal Bar Chart)
A list of the highest-performing movies in the dataset (likely rated 9.0+). Visible titles include:
*   *The Shawshank Redemption*
*   *The Godfather*
*   *The Dark Knight*
*   *Pulp Fiction*
*   *Schindler's List*
*   *Fight Club*
*   *Forrest Gump*
*   *Inception*
*   *The Lord of the Rings*
*   *The Matrix*

### 4. Avg IMDb Rating by Year (Line Chart)
Tracks the average rating of movies in the dataset across decades (1940 - 2020).
*   **Peak:** A notable spike in average ratings around the 1970s/1980s.
*   **Trend:** A general decline in average rating for the most recent years (2010-2020), likely due to the recency bias or a larger volume of releases diluting the "top" list.

### 5. Avg Duration (mins) by Category (Bar Chart)
Analyzes the average runtime of movies based on their genre combinations.
*   **Longest Genres:** **Drama/War** and **Biography** movies have the longest average durations (approx. 150-160 mins).
*   **Shortest Genres:** **Horror/Thriller** and **Animation** tend to have shorter runtimes (approx. 100-110 mins).

---

## 💡 Key Insights

1.  **Quality over Quantity:** The dataset represents a "Best of" list, with an impressive average rating of **8.26**.
2.  **Mature Content Dominates:** Over 60% of the top-rated movies are rated **R**, suggesting that mature, complex storytelling is highly correlated with critical acclaim in this dataset.
3.  **Genre Length:** Epic genres like **Drama/War** and **Biography** require more screen time (avg ~160 mins) compared to faster-paced genres like **Horror/Thriller**.
4.  **Classic Cinema:** The "Top 10" list is dominated by classics from the 1970s, 90s, and early 2000s.

---

## 🛠️ Tools & Technologies

*   **Microsoft Power BI:** Dashboard development and visualization.
*   **DAX:** Used for calculating averages and counts.
*   **Custom Theming:** JSON theme file applied to match Netflix branding (Dark background, Red accents).

