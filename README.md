# Amazon Prime Movie and TV Shows Analysis Using Microsoft Power BI

### Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Data Source](#data-source)
- [Tools and Techniques Used](#tools-and-techniques-used)
- [Type of Analysis Used](#type-of-analysis-used)
- [Key Performance Indicators](#key-performance-indicators)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)

### Project Overview
This project analyzes the Amazon Prime Movies and TV Shows dataset to uncover key trends in content distribution, genres, ratings, and release patterns. The goal is to provide insights into Amazon Prime Video's catalog, helping to understand content availability, dominant genres, and the evolution of movie and TV show releases over time.

![Amazon prime video dashboard screenshot](https://github.com/user-attachments/assets/8a3f05a6-add8-403a-92fa-cc8c45d5bb20)

### Objectives
1.	To analyze the distribution of content types (Movies vs. TV Shows) on Amazon Prime Video.
2.	To identify the most popular genres and ratings among available titles.
3.	To track content release trends over the years and understand the platform’s growth.
4.	To examine content distribution by country and provide insights into regional preferences.
5.	To generate recommendations for content strategy based on observed trends.

### Methodology
The dataset consists of multiple columns providing detailed information about Amazon Prime’s catalog. Each column was analyzed to extract meaningful insights:
-	show_id: Unique identifier for each title.
-	Type: Indicates whether the entry is a Movie or TV Show.
-	Title: Name of the movie or TV show.
-	Director: Lists the director(s) of the content.
-	Cast: Lists the main actors featured in the content.
-	Country: The country where the movie or TV show was produced.
-	date_added: The date the content was added to Amazon Prime.
-	release_year: The year the content was originally released.
-	rating: The content’s rating, indicating the appropriate audience (e.g., 13+, 16+, R, PG-13, etc.).
-	duration: Specifies the length of movies (in minutes) or the number of seasons for TV shows.
-	listed_in: Categories or genres the content belongs to (e.g., Drama, Comedy, Documentary).
-	description: A summary of the movie or TV show’s storyline.

### Data Source
Amazon Prime Movies and TV Shows dataset from Kaggle [Download Here](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)

### Tools and Techniques Used
-	Power BI for data visualization
-	Data aggregation and filtering
-	Bar charts, pie charts, and maps for representation
-	Time series analysis for trends over the years

### Type of Analysis Used
Exploratory Data Analysis (EDA) was conducted to identify trends and patterns. The following techniques were applied:
-	Descriptive Statistics: Summary of total titles, ratings, genres, and directors.
-	Distribution Analysis: Charts representing content distribution across ratings and countries.
-	Comparative Analysis: Bar charts comparing genres and ratings to understand preferences.
-	Time Series Analysis: Evaluating content growth trends by release year.

### Key Performance Indicators
-	Total number of titles, genres, and directors.
-	Ratings distribution and their impact on content accessibility.
-	Genre trends and content preferences.
-	Geographical distribution of shows.
-	Growth trends in content over the years.

### Key Insights
1.	Content Dominance: The platform hosts 9,655 titles, with movies making up nearly 80% of the catalog.
2.	Popular Genres: Drama (986 titles) and Comedy (536 titles) are the leading genres.
3.	Diverse Ratings: Most content is categorized under 13+ and 16+, making it suitable for a broad audience.
4.	Global Availability: The platform distributes content across multiple countries, with a significant presence in North America and Europe.
5.	Growth Over Time: Content releases have sharply risen in recent years, indicating increased production and licensing.

### Recommendations
-	Amazon Prime could explore more diverse genres to cater to niche audiences.
-	The platform may invest in localized content production to expand its regional presence.
-	Analysis of rating-based engagement can guide content curation to improve user satisfaction.
-	Continued content expansion can align with streaming trends and audience demand.






