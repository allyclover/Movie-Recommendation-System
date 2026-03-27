# Movie-Recommendation-System
PySpark movie recommendation system using collaborative filtering (ALS) to stimulate how streaming platforms like Netflix recommend content based on user preferences.

---

## Business Problem
With thousands of content options, users often struggle to find relevant movies. This project aims to improve user retention by delivering personalized recommendations.

---

## Tools 
- PySpark
- Spark MLlib (ALS)
- Python

---

## Methodology

### Collaborative Filtering
Used ALS (Alternating Least Squares) to:
- Learn user preferences
- Predict ratings
- Recommend movies

---

### Scenario Testing
Two approaches were compared:

- **Scenario 1 (≥ 25 ratings)**
  - Niche, less-reviewed movies
  - Higher variety

- **Scenario 2 (≥ 100 ratings)**
  - Popular, widely-reviewed movies
  - Higher reliability

---

## Key Insights
- Trade-off between **“Hidden Gems” vs “Popular Picks”**
- Rating volume impacts recommendation confidence
- Different strategies can target different user segments

---

## Business Impact
- Improves personalization without needing sensitive data
- Supports user segmentation
- Can increase engagement and retention

---

## Dataset
MovieLens Dataset  
https://grouplens.org/datasets/movielens/latest/

---

## Author
Allyson Chang
