Title: Amazon Prime TV Shows and Movies – Exploratory Data Analysis (EDA) Project Type: Exploratory Data Analysis (EDA) Contribution: Individual

Project Overview - This project explores the Amazon Prime Video catalog for the US region using Exploratory Data Analysis (EDA). The goal is to understand what kinds of titles are available on the platform, how they are rated, and how factors like genre, country, and creators influence the catalog.

Business Objective - Use historical title and credits data to:

Understand the composition of the Prime Video catalog (genres, countries, formats).

Analyze ratings and popularity patterns.

Identify gaps and opportunities to improve content discovery, catalog strategy, and user engagement.

Dataset -

Titles dataset: Movies and TV shows with information such as title, type (movie/show), release year, runtime, genres, countries, age certification, IMDb and TMDb metrics, and seasons (for shows).

Credits dataset: Cast and crew details including actors, directors, and other contributors.

Project Workflow -

Know Your Data
Loaded the titles and credits datasets and reviewed structure, missing values, and basic statistics.

Identified important fields for business analysis (ratings, popularity, runtime, release year, genres, countries, age certification, show type, seasons, actors, directors).

Data Wrangling
Selected relevant columns and removed duplicates and obvious outliers.

Handled missing values and fixed data types (dates, numeric fields, list fields).

Exploded list columns such as genres and production countries.

Merged titles with credits to analyze actors and directors.

Exploratory Data Analysis (Main Charts) -
Genre distribution and top 5 genres over time.

Genre vs. IMDb score distribution.

Release year vs. average IMDb score.

Number of titles by age certification and age certification vs. average IMDb score.

Movie vs. TV show distribution and seasons analysis.

Top production countries by number of titles and by average IMDb score (20+ titles).

Top 10 actors by number of titles and top 10 directors by average IMDb score.

Correlation heatmap of key numeric features.

Pair plot grouped by show type (movie vs. show).

Key Insights (Short) -

Movies heavily outnumber TV shows, but shows bring more seasons and stronger binge‑watch potential.

A large share of titles has missing or “Unknown” age certifications, which can hurt user trust and parental controls.

Ratings, popularity, and runtime show only weak correlation—high quality is not just about being longer or more popular.

The U.S. dominates by volume, while some smaller countries achieve higher average IMDb scores when filtered for enough titles.

Certain actors and directors appear very frequently or have consistently high‑rated work, making them strong bets for future content strategy.

Recommendations -

Clean and enrich metadata (especially age certifications, genres, countries) to improve search, recommendations, and compliance.

Use ratings, popularity, and viewing patterns to power a stronger recommendation engine and highlight both hits and “hidden gems.”

Rebalance the catalog by investing more in high‑performing regions, genres, and creators, and growing quality TV show content where it fits.

Treat these analyses and dashboards as a feedback loop for acquisition, marketing, and release planning, updating them regularly.
