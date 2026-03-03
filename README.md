# NETFLIX_DATA_ANALYSIS
# 🎬 Netflix Movies & TV Shows: Content Strategy Analysis
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-orange)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-red)
![Data-Cleaning](https://img.shields.io/badge/Data-Cleaning-green)

## 📌 Project Overview
This project explores the Netflix library to identify trends in content production, regional distribution, and rating classifications. The goal is to understand how Netflix has pivoted its content strategy over the years and which genres/regions dominate the platform.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas (Data Wrangling), NumPy, Matplotlib, Seaborn (Advanced Visualization)
* **Dataset:** 8,800+ records of Movies and TV Shows.

## 🧹 Data Cleaning & Management
Handling a dataset with global metadata required rigorous cleaning:
* **Missing Value Treatment:** Strategically handled nulls in `Director`, `Cast`, and `Country` to ensure regional analysis remained accurate.
* **Temporal Analysis:** Converted `date_added` into a standard datetime format and extracted **Year** and **Month** to track library growth over time.
* **Categorical Mapping:** Standardized `rating` and `type` features for cleaner visualization and grouping.

## 📊 Key Business Insights
* **Content Growth:** A significant surge in content production was observed starting from 2015, with Movies consistently outnumbering TV Shows.
* **Rating Dominance:** Analysis shows that **TV-MA** and **TV-14** are the most prevalent ratings, indicating a focus on mature and teen audiences.
* **Regional Leaders:** The **United States, India, and the United Kingdom** emerge as the top content producers, reflecting Netflix's global expansion strategy.
* **Director Analysis:** Identified the most prolific directors and cast members, providing insight into Netflix’s frequent collaborators.

## 📈 Featured Visualizations
* **Content Distribution:** Comparison of Movies vs. TV Shows using Pie and Bar charts.
* **Yearly Trends:** Time-series analysis showing the volume of content added per year.
* **Top 10 Countries:** Horizontal bar plots illustrating the geographic concentration of content.
* **Rating Heatmaps:** Visual breakdown of content suitability across different genres.

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/netflix-content-analysis.git](https://github.com/your-username/netflix-content-analysis.git)
