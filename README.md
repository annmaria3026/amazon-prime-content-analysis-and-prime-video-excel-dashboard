# Amazon Prime Content Dashboard (Excel)

An interactive Excel dashboard that analyses the Amazon Prime catalogue of movies and TV shows, built with Pivot Tables, charts and slicers.

## Dashboard Preview

![Dashboard](dashboard-screenshot.png)

## Project Overview

The goal was to understand what content Amazon Prime offers: how it splits between movies and TV shows, how it has changed over time, and which ratings and genres are most common.

## Dataset

- **Source:** [Amazon Prime Movies and TV Shows – Kaggle (Shivam Bansal)](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)
- **Size:** 9,668 titles
- **Columns:** show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

## Analysis Performed

Six Pivot Tables feed six charts, and six slicers (type, release year, country, rating, director, genre) let you filter the whole dashboard interactively:

1. Content by type (movies vs TV shows)
2. Titles by release year
3. Titles by country
4. Titles by age rating
5. Titles by director
6. Titles by genre

## Key Findings

- The catalogue has **7,814 movies** and **1,854 TV shows**, so movies make up about 81% of titles.
- Releases grew steadily over 2011–2021, peaking in **2021 with 1,442 titles**.
- **13+** is the most common age rating (2,117 titles), followed by 16+ (1,547) and 18+ (1,243).
- Drama is the most common genre among the top genres shown (986 titles).

## Tools Used

- Microsoft Excel
- Pivot Tables
- Slicers
- Excel Charts

## Files

- `ANN_MARIA_DASHBOARD.xlsb`: the Excel dashboard
- `dashboard-screenshot.png`: screenshot of the dashboard

## Limitations

- Some titles have no director (2,082) or no rating (337), so those counts are lower than the total of 9,668.

## Author

**Ann Maria Rebeiro**
[LinkedIn](https://linkedin.com/in/ann-maria-rebeiro) | annmariarebeiro911@gmail.com
