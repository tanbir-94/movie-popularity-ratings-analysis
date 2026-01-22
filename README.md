#  Movie Popularity & Ratings Analysis (EDA Project)

##  Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a movie dataset to understand
how **popularity, audience ratings, release timing, and genres** influence movie performance.

The goal of this project is to demonstrate **real-world data analysis thinking** —
from data cleaning and feature engineering to visualization and insight generation —
using Python.

---

##  Dataset Information
- **Total Movies:** 9,827
- **Source:** TMDB-style movie dataset (`mymoviedb.csv`)
- **Features:**  
  - Release_Date  
  - Title  
  - Overview  
  - Popularity  
  - Vote_Count  
  - Vote_Average  
  - Original_Language  
  - Genre  
  - Poster_Url  

---

##  Tools & Libraries Used
- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib** – visualization
- **Seaborn** – statistical visualization
- **Jupyter Notebook**

---

##  Analysis Workflow

### 1 Data Understanding & Quality Check
- Inspected dataset structure and data types
- Verified **no missing values**
- Checked and confirmed **no duplicate records**

### 2️ Data Cleaning & Feature Engineering
- Converted `Release_Date` to datetime format
- Extracted:
  - Year
  - Month
  - Day of Week
  - Quarter
- Dropped less useful columns (`Overview`, `Poster_Url`)
- Processed multi-value `Genre` column using split and explode technique
- Created **Rating_Category** feature based on audience ratings

### 3️ Exploratory Data Analysis (EDA)
- Top 10 most popular movies
- Popularity distribution analysis
- Relationship analysis:
  - Popularity vs Vote Count
  - Popularity vs Vote Average
- Rating category analysis
- Time-based analysis:
  - Year-wise release trends
  - Month, weekday, and quarter impact on popularity
- Genre-based analysis:
  - Genre frequency
  - Average popularity by genre
  - Average ratings by genre

---

##  Key Insights

###  Popularity & Ratings
- Higher audience ratings generally lead to higher popularity
- High ratings alone do not guarantee extreme popularity
- Blockbuster movies dominate popularity due to large vote counts

###  Time-Based Trends
- Movie releases peaked between **2000–2020**
- **Quarter 1 and Quarter 4** releases show higher average popularity
- Mid-week releases (Wednesday–Thursday) perform better

###  Genre Insights
- **Drama and Comedy** dominate movie production
- **Adventure and Fantasy** genres achieve the highest popularity
- **History, War, and Music** genres receive higher average ratings despite lower popularity

---

##  Business Implications
- Studios can maximize reach by releasing movies in **early-year or Q4**
- High-energy genres are ideal for large-scale releases
- Critically appreciated genres benefit from targeted niche marketing

---

##  Project Structure

movie-popularity-ratings-analysis/
│
├── movie_popularity_ratings_eda.ipynb
├── mymoviedb.csv
└── README.md


Conclusion
This project showcases an end-to-end EDA workflow with a strong focus on data understanding, transformation, visualization, and insight generation.
It reflects practical data analysis skills expected from a Data Analyst / MIS / BI role.


Author
Md Tanbir Rja
Aspiring Data Analyst
