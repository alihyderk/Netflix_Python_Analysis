🎥 Netflix Titles – Python Exploratory Data Analysis

A complete end-to-end EDA project using Pandas, Matplotlib, Seaborn & WordCloud.

📌 Project Overview

This project analyzes the popular Netflix Titles Dataset, which contains information about movies and TV shows available on Netflix.
The goal of this project is to:

Explore Netflix’s content growth

Analyze genres, ratings, durations, countries, directors, and cast

Visualize global content trends

Apply data cleaning & preprocessing

Generate 12 professional visualizations

Create a meaningful narrative for portfolio & recruiters

This project is ideal for showcasing Python data analysis skills, visual storytelling, and real-world EDA workflow.

📁 Project Structure
Netflix_Python_Analysis/
│
├── data/
│   └── netflix_titles.csv
│
├── notebooks/
│   └── netflix_analysis.ipynb
│
├── images/
│   ├── netflix_title_over_years.png
│   ├── movies_vs_tvshows.png
│   ├── movies_tvshows_on_netflix_years.png
│   ├── Top_countries_producing_content.png
│   ├── 15_most_genres.png
│   ├── distribution_content_ratings.png
│   ├── movie_duration_distribution.png
│   ├── top_20_actors_netflix.png
│   ├── 15_directors_most_title.png
│   ├── Tvshows_seasons_distribution.png
│   └── world_cloud_netflix_descriptions.png
│
└── README.md

🧹 Data Cleaning & Preprocessing

In this project, the following steps were performed:

✔ Converted date_added into datetime format
✔ Extracted year_added
✔ Cleaned country column & removed “Unknown”
✔ Separated movie durations into numeric format
✔ Cleaned genre and cast lists
✔ Removed nulls where necessary
✔ Prepared the dataset for visualization

📊 Insights & Visualizations

Below is a detailed breakdown of the insights extracted from each plot.

1️⃣ Netflix Titles Added Over the Years

📈 Massive growth from 2015 to 2019, peaking in 2019.

Netflix aggressively expanded its library during these years, before slowing down around 2021 due to global production challenges.

2️⃣ Movies vs TV Shows

Movies: ~6100

TV Shows: ~2700

Netflix still has more movies, but TV shows grew significantly after 2016.

3️⃣ Movies & TV Shows Added Per Year

TV Shows increased rapidly from 2016 onward, reflecting Netflix’s shift toward original episodic content.

4️⃣ Top 10 Content-Producing Countries

USA, India, and UK dominate content production.

After cleaning missing values, the distribution became more accurate.

5️⃣ Top 15 Directors

Directors like Rajiv Chilaka, Jan Suter, Raúl Campos appear frequently — many from international/animated content.

6️⃣ Top 20 Most Frequent Actors

Most frequent actors include:

Anupam Kher

Shah Rukh Khan

Akshay Kumar

Amitabh Bachchan

Netflix has a strong presence of Indian cinema due to global demand.

7️⃣ Content Rating Distribution

Most titles are rated TV-MA and TV-14, showing Netflix’s focus on adult and teen audiences.

8️⃣ Movie Duration Distribution

Most movies range between 80–120 minutes, forming a near-normal distribution.

9️⃣ Most Frequent Genres

Top genres:

International Movies

Dramas

Comedies

International TV Shows

Netflix invests heavily in global storytelling, multilingual content, and drama-heavy narratives.

🔟 Cleaned Country Distribution

This chart excludes unknown countries to show a realistic distribution of content across world markets.

1️⃣1️⃣ TV Show Seasons Distribution

Most TV shows have:

1 season (very high count)

Very few extend beyond 5 seasons

Netflix tends to make limited-run series rather than long franchises.

1️⃣2️⃣ Word Cloud of Descriptions

Most common themes include:

family

world

life

find

love

woman

young

man

Netflix focuses heavily on drama, relationships, mystery, crime, and personal journeys.

🛠️ Tech Stack Used
Tool	Purpose
Python	Core programming
Pandas	Data cleaning & manipulation
NumPy	Numeric processing
Matplotlib / Seaborn	Data visualization
WordCloud	NLP visualization
Jupyter Notebook	Interactive development

▶️ How to Run the Project
1. Clone the repository
git clone https://github.com/your-username/Netflix_Python_Analysis.git
cd Netflix_Python_Analysis

2. Install dependencies
pip install -r requirements.txt

3. Open Jupyter Notebook
jupyter notebook

4. Run the analysis

Open:

notebooks/netflix_analysis.ipynb


Execute all cells to reproduce the full analysis.

💡 Key Insights Summary

Netflix’s content library exploded after 2015, peaking in 2019.

Movies dominate, but TV shows are growing fast.

USA, India, and UK lead in global Netflix content.

Drama, International Movies, and Comedies are top genres.

TV-MA dominates ratings → content aimed at adults.

Most TV shows have only 1 season.

Word cloud shows themes of family, love, life, world, young characters.

🏁 Conclusion

This project provides a comprehensive overview of Netflix's global content strategy.
It demonstrates strong skills in:

Python data cleaning

Exploratory data analysis

Data visualization

Storytelling with data

Real-world dataset interpretation

Perfect addition to a data analyst portfolio.

📎 Future Enhancements

🔹 Build a dashboard with Power BI / Tableau
🔹 Create a recommendation system
🔹 Add clustering to group similar content
🔹 Run sentiment analysis on descriptions

AUTHOR:
ALI HYDER
M.A. DATA AND DISCOURSE STUDIES/ GERMANY
