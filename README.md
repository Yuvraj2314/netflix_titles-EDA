# netflix_titles-EDA
# 📺 Netflix Movies & TV Shows – Exploratory Data Analysis

This project performs **Exploratory Data Analysis (EDA)** on the Netflix Movies and TV Shows dataset from Kaggle to uncover patterns, trends, and insights about Netflix's global content library.

---

## 📂 Dataset

- **Source:** [Netflix Movies and TV Shows Dataset – Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
- **Size:** ~7,000+ entries
- **Features:**
  - `show_id`: Unique ID
  - `type`: Movie or TV Show
  - `title`: Title of the show
  - `director`: Director of the show
  - `cast`: Cast members
  - `country`: Country of origin
  - `date_added`: Date added to Netflix
  - `release_year`: Year of release
  - `rating`: Content rating
  - `duration`: Duration (minutes or seasons)
  - `listed_in`: Genres/categories
  - `description`: Summary of the show

---

## 🛠️ Tools & Libraries

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

---

## 📊 EDA Process

1. **Data Loading & Inspection**
   - Shape, info, description
   - Duplicate & missing value check

2. **Data Cleaning**
   - Handling missing values
   - Date formatting
   - Country value replacement

3. **Univariate Analysis**
   - Distribution of Movies vs TV Shows
   - Top producing countries
   - Ratings frequency

4. **Bivariate Analysis**
   - Content trends by year
   - Genre distribution
   - Duration patterns

5. **Visualization**
   - Bar charts, heatmaps, count plots

---

## 🔍 Key Insights

- **Movies** dominate over **TV Shows** in Netflix’s library.
- **United States** produces the most Netflix content, followed by India and the UK.
- **2018–2020** saw the highest number of content additions.
- Most common ratings: **TV-MA**, **TV-14**, and **PG**.
- Top genres: **Dramas**, **International Movies**, and **Comedies**.

---

   ```bash
   git clone https://github.com/<your-username>/netflix-eda.git
