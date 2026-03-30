# 🎬 Movie Data Analysis Project

## 📌 Overview

This project analyzes a movie dataset to extract insights about profitability, return on investment (ROI), popular genres, and key contributors like actors, producers, and directors.

---

## 📂 Dataset Features

* Budget
* Revenue
* Genres
* Cast
* Crew (Directors, Producers)
* Language

---

## 🧮 Key Calculations

### Profit

```
Profit = Revenue - Budget
```

### ROI (Return on Investment)

```
ROI = Profit / Budget
```

---

## 📊 Analysis Performed

### 1️⃣ Most Profitable Movie

* Identified the movie with the highest profit.
* Extracted:

  * Producers
  * Director
  * Main Actors

---

### 2️⃣ Language with Highest Average ROI

* Grouped movies by language
* Calculated average ROI for each
* Identified the top-performing language

---

### 3️⃣ Unique Genres

* Extracted all genres from dataset
* Created a unique genre list

---

### 4️⃣ Producers & Directors Analysis

* Created table with:

  * Movie
  * Producers
  * Directors
* Found **Top 3 Producers** based on average ROI

---

### 5️⃣ Most Frequent Actor

* Identified actor appearing in most movies
* Analysis includes:

  * Total movies
  * Genre distribution
  * Total profit contribution

---

### 6️⃣ Directors & Preferred Actors

* Identified Top 3 Directors (by number of movies)
* Found most frequently cast actors for each

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy

---

## ▶️ How to Run

1. Install dependencies:

```
pip install pandas numpy
```

2. Run the script:

```
python analysis.py
```

---

## 📈 Key Insights

* Some low-budget movies achieve extremely high ROI
* Certain languages outperform others in profitability
* A few producers consistently deliver high ROI
* Popular actors dominate specific genres
* Directors often collaborate with preferred actors

---

## 📎 Conclusion

This project demonstrates how data analysis can uncover patterns in the movie industry, helping understand what drives financial success.

---

## 🚀 Future Improvements

* Visualization using Matplotlib / Seaborn
* Machine learning for revenue prediction
* Trend analysis over time

---
