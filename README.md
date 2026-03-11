# Anime Industry Analytics Dashboard
### Anime Industry Analytics: What Drives Anime Success?

## Project Overview

The global anime industry has experienced significant growth in recent years, with streaming platforms increasingly investing in anime content to attract global audiences. However, not all anime titles perform equally well in terms of ratings, popularity, and audience engagement.

This project analyzes a dataset of anime titles to identify **key factors that contribute to anime success**. Using Python for data analysis and Power BI for visualization, the project explores patterns related to genres, episode length, studios, and audience engagement.

The goal is to generate **data-driven insights that could help streaming platforms make better decisions regarding content acquisition, production, and promotion.**

## Project Highlights

- Analyzed **500 anime titles** to identify patterns in ratings, popularity, and engagement.
- Built a **complete data analytics workflow** including data cleaning, exploratory analysis, feature engineering, and visualization.
- Created a **custom Success Score metric** combining ratings, popularity, and fan engagement.
- Developed a **Power BI dashboard** to visualize industry insights interactively.
- Generated insights that could support **content strategy decisions for streaming platforms.**

## Dashboard & Visual Insights

Below are key visualizations generated during the analysis.

### Genre Performance

<img width="600" height="360" alt="top_genres" src="https://github.com/user-attachments/assets/4a8f3c43-ac23-4e45-a20b-5d0f3340f650" />

### Episode Length vs Rating

<img width="600" height="360" alt="episode_vs_score" src="https://github.com/user-attachments/assets/639a3ff1-bfcc-4492-96c3-12504c169356" />

### Popularity vs Rating

<img width="600" height="360" alt="popularity_vs_rating" src="https://github.com/user-attachments/assets/060cf1a3-ec27-4a33-a2a7-fc0733ff348f" />

### Studio Performance

<img width="600" height="360" alt="top_studios" src="https://github.com/user-attachments/assets/331a7fce-90ac-479b-917d-4eaae9af18b0" />

### Anime Industry Production Trend

<img width="600" height="360" alt="anime_production_trend" src="https://github.com/user-attachments/assets/65d015db-6c52-4229-91f8-767064f25bca" />

### Top Successful Anime (Success Score)

<img width="600" height="360" alt="top_success_anime" src="https://github.com/user-attachments/assets/4dda4135-29ce-43e2-a25e-36bbd1c0683a" />

## Business Problem

Streaming platforms must continuously decide which anime content to acquire, produce, or promote. Understanding what factors influence anime success is essential for making informed decisions.

This project explores several key questions:

- Which genres produce the highest rated anime?
- Do longer anime series perform better than shorter seasonal anime?
- Which studios consistently produce highly rated anime?
- Are the most popular anime also the highest rated?
- What characteristics define a highly successful anime title?

By analyzing historical data, the project identifies patterns that may help guide **content strategy and investment decisions.**

## Dataset Description

The dataset contains **500 anime titles** along with metadata and audience engagement metrics.

### Key Features

- **Title** – Name of the anime
- **Score** – Average audience rating
- **Episodes** – Number of episodes in the series
- **Genres** – Genre categories associated with the anime
- **Studios** – Production studios
- **Members** – Number of users interested in the anime
- **Favorites** – Number of users who marked the anime as a favorite
- **Year** – Release year

These variables allow analysis of both **content characteristics and audience behavior.**

## Tools & Technologies

This project demonstrates several tools commonly used in data analyst roles.

- **Programming & Data Analysis** - Python, Pandas, NumPy
- **Data Visualization** - Matplotlib, Seaborn
- **Business Intelligence** - Power BI
- **Development Environment** - Jupyter Notebook, VS Code, GitHub

## Project Workflow

### 1. Data Cleaning

The raw dataset contained missing values and inconsistent formats.

Data preparation steps included:

- Handling missing values
- Removing duplicate records
- Converting columns to appropriate data types
- Splitting multi-value categorical fields such as genres and studios

A cleaned dataset was created to enable accurate analysis.

### 2. Exploratory Data Analysis (EDA)

Several analyses were performed to answer the business questions.

#### Genre Performance Analysis

- Evaluated which anime genres receive the highest average ratings.

#### Episode Length Analysis

- Investigated whether anime with more episodes perform better than shorter series.

#### Studio Performance Analysis

- Identified studios that consistently produce highly rated anime.

#### Popularity vs Rating Analysis

- Compared audience popularity with quality ratings to identify hidden gems and mass-market hits.

#### Industry Trend Analysis

- Examined how anime production volume and ratings have evolved over time.

### 3. Feature Engineering

To better measure anime performance, additional analytical metrics were created.

### Engagement Ratio

```Engagement Ratio = Favorites / Members```

This metric helps identify anime with strong fan loyalty relative to their audience size.

### Success Score

A composite metric was created to measure overall anime success.

The score combines:

- Rating quality
- Popularity
- Fan engagement

By combining these factors, the Success Score identifies anime that perform strongly across multiple dimensions.

## Key Insights

#### Genre Trends

- Genres such as **Action, Fantasy, and Psychological** tend to achieve higher average ratings.
- Business implication:
Streaming platforms may prioritize these genres to maximize audience engagement.

#### Optimal Episode Length

- Anime with **13–24 episodes** often achieve higher ratings than extremely long series.
- Business implication:
Short seasonal formats may help maintain quality while controlling production costs.

#### Studio Performance

- Certain studios consistently produce highly rated anime.
- Business implication:
Streaming platforms may benefit from partnering with proven studios to improve content quality.

#### Popularity vs Quality

- Some anime are extremely popular despite moderate ratings, while others have excellent ratings but lower popularity.
- Business implication:
High-rated but under-discovered anime represent opportunities for targeted promotion.

#### Industry Growth

- Anime production has increased steadily over time, reflecting strong global demand.
- Business implication:
Streaming platforms may continue expanding anime investment strategies.

## Power BI Dashboard

An interactive Power BI dashboard was developed to visualize key insights.

#### Dashboard Features

- Genre rating analysis
- Studio performance comparison
- Episode count vs rating visualization
- Popularity vs rating scatter analysis
- Industry trend visualization
- Top successful anime ranking

The dashboard allows stakeholders to explore anime performance metrics interactively.

## Project Structure

```
anime-industry-analytics
│
├── data
│   ├── raw_anime_dataset.xls
│   ├── cleaned_anime_dataset.xls
│   └── anime_final_dataset.xls
│
├── visuals
│   ├── anime_production_trend.png
│   ├── correlation_heatmap.png
│   ├── episode_vs_score.png
│   ├── popularity_vs_rating.png
│   ├── rating_trend.png
│   ├── top_genres.png
│   ├── top_studios.png
│   └── top_success_anime.png
│
├── notebooks
│   └── anime_analysis.ipynb
│
├── dashboard
│   └── anime_dashboard.pbix
│
└── README.md
```

## Skills Demonstrated

This project demonstrates several skills expected from data analysts:

- Data Cleaning and Preparation
- Exploratory Data Analysis
- Feature Engineering
- Data Visualization
- Business Insight Generation
- Dashboard Development
- Data Storytelling

## Limitations

- Dataset size is limited to 500 anime titles.
- External factors such as marketing budget or streaming platform availability were not included.
- Ratings are based on user reviews and may contain bias.

## Conclusion

This project demonstrates how data analytics can be applied to understand audience behavior and content performance in the anime industry.

By combining data analysis, visualization, and business insights, the project highlights how streaming platforms can leverage data to improve **content strategy, marketing, and investment decisions.**
