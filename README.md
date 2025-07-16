# 🎬 Amazon Prime EDA Project

The **Amazon Prime EDA Project** is a comprehensive **Exploratory Data Analysis (EDA)** conducted on the content available on Amazon Prime Video. This project dives deep into the platform's catalog to uncover patterns in content type, genres, ratings, countries of origin, and cast/crew distribution to support strategic decisions for content planning, curation, and marketing.

---

## 📌 Project Objective

To analyze Amazon Prime's video catalog in order to:

* Understand the content distribution across different formats, genres, and countries.
* Identify key contributors like top-rated shows, directors, and actors.
* Explore user perception trends through IMDb scores and TMDB popularity.
* Provide actionable insights for content strategy and platform development.

---

## 🧾 Dataset Overview

* **Main Files:**

  * `titles.csv`: Metadata of Movies and TV Shows (9,871 rows, 15 columns)
  * `credits.csv`: Cast and Crew Details (124,235 rows, 5 columns)

---

## 🧹 Data Preprocessing & Wrangling

* **Missing Values**: Handled in columns like `seasons`, `age_certification`, `tmdb_score`, and `character`.
* **Duplicate Removal**: Eliminated duplicate entries from both datasets.
* **Data Merge**: Merged `titles.csv` and `credits.csv` on `id` to form a unified dataset.
* **Data Type Conversion**:

  * Converted `imdb_score`, `imdb_votes`, `tmdb_score`, and `tmdb_popularity` to numeric types.
  * Converted `type`, `age_certification` to categorical types for analysis.

---

## 📊 Visual Explorations & Insights

### 1. **Content Type Distribution**

* 🥧 Movies far outnumber TV Shows on the platform.
* 💡 Indicates Amazon's heavier investment in film-based content.

### 2. **Top 10 Countries by Content Production**

* 🌎 USA dominates, followed by the UK and India.
* 💡 Highlights regional focus areas in content sourcing.

### 3. **Top 10 Highest-Rated Shows**

* ⭐ Horizontal bar chart showcasing the best-performing shows based on ratings.
* 💡 Great for identifying benchmark content.

### 4. **Top Directors & Actors**

* 🎬 Charts highlight frequently featured creators.
* 💡 Heavy reliance on select talent; may limit diversity.

### 5. **Popular Topics (Word Cloud)**

* ☁️ Common themes: "life", "love", "find".
* 💡 Reflects dominant storytelling motifs.

### 6. **Top 10 Genres**

* 🎭 Drama, Comedy, and Thriller are leading genres.
* 💡 Aligns with global viewer preferences.

### 7. **Age Certification Distribution**

* 🔞 'R', 'PG-13', and 'PG' dominate.
* 💡 Emphasizes mature content strategy.

### 8. **IMDb Rating Distribution**

* 📈 Ratings mostly between 5.5 and 7.5 (peak around 6.0–6.5).
* 💡 Suggests average to moderately high user reception.

### 9. **Content Release Year Distribution**

* 📅 Spike in releases from 2018–2020; dip afterward.
* 💡 COVID-19 impact visible; useful for production forecasting.

### 10. **Runtime vs IMDb Score by Type**

* 🎥 Movies are longer with a wide rating range.
* 📺 Shows are shorter and maintain relatively high scores.

### 11. **TMDB Popularity vs Runtime vs IMDb Score (Bubble Chart)**

* 🔵 Popular content often includes shorter shows or medium-length movies with high IMDb ratings.

---

## 🛠️ Tools & Technologies Used

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn, WordCloud**
* **Jupyter Notebook**

---

## 📁 Project Structure

```
Amazon-Prime-EDA-Project/
│
├── data/
│   ├── titles.csv
│   └── credits.csv
│
├── notebooks/
│   └── Amazon_Prime_EDA.ipynb
│
├── images/
│   └── [Graphs and Visualizations]
│
├── README.md
└── requirements.txt
```

---

## 🧠 Key Takeaways

* Amazon Prime has a strong focus on movie content.
* Genre trends suggest Drama and Comedy remain safe bets.
* Top-rated and highly popular shows are often shorter in duration.
* Content release trends are heavily affected by global events (e.g., COVID-19).
* The majority of content is catered toward mature audiences.

---

## 📬 Contact

**Isha Chaudhary**

📧 [ishachaudhary3928@gmail.com](mailto:ishachaudhary3928@gmail.com)

🔗 [LinkedIn](https://www.linkedin.com/in/ishachaudhary18/)

📍 Noida, India




