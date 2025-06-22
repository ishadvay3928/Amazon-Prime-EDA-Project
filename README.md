# Amazon-Prime-EDA-Project

Amazon Prime is a paid subscription service of Amazon which is available in many countries and gives users access to additional services otherwise unavailable or available at a premium to other Amazon customers.

This project involved an extensive Exploratory Data Analysis (EDA) of the Amazon Prime Video content dataset, aiming to uncover key insights into content trends, genre distributions, ratings, and country contributions. The primary objective was to support strategic decision-making for content planning and marketing on the platform.

The analysis began with a thorough understanding of the dataset, which comprised two main files: titles.csv (containing metadata about movies and TV shows) and credits.csv (detailing cast and crew information). Initial data inspection revealed that the titles dataset had 9871 rows and 15 columns, with significant missing values in seasons, age_certification, and tmdb_score. The credits dataset, with 124235 rows and 5 columns, primarily had missing values in the character column.

Data wrangling was a crucial step, involving several key manipulations to ensure data quality and prepare for analysis. Duplicate records were removed from both datasets. Subsequently, df_titles and df_credits were merged on a common 'id' column, creating a unified dataset for comprehensive analysis. Numerical columns such as imdb_score, imdb_votes, tmdb_score, and tmdb_popularity were converted to appropriate numeric types, while type (Movie/Show) and age_certification were converted to categorical types for efficient processing and analysis. These manipulations ensured the data was clean, correctly formatted, and ready for visualization.

The data visualization phase involved creating various charts to understand relationships between variables and extract actionable insights:

- **Content Type Distribution**: A pie chart revealed that movies significantly outnumber TV shows on Amazon Prime, indicating a heavier investment in film content.
- **Top 10 Countries by Content Production:** A horizontal bar chart clearly showed that the United States dominates content production, followed by the United Kingdom, and then India, highlighting key content sourcing regions.
- **Top 10 highest-Rated Shows:** A horizontal bar chart clearly showed the top 10 Shows having maximum ratings.
- **Top Directors and Actors:** Bar charts identified frequently featured directors and actors, suggesting Amazon Prime's reliance on established talent. While this ensures reliable production, it also poses a risk of limited content variety.
- **Popular Topics (Word Cloud):** A word cloud indicated that themes like "life," "love," and "find" are prevalent in content descriptions, reflecting common narrative focuses.
- **Top 10 Genres:** A bar chart confirmed that Drama, Comedy, and Thriller are the most common genres, suggesting high user demand in these categories.
- **Age Certification Distribution:** A bar chart showed that "R" is the most common age certification, followed by "PG-13" and "PG," indicating a significant portion of content targets mature audiences.
- **IMDb Rating Distribution:** A histogram revealed that most IMDb scores fall between 5.5 and 7.5, with a peak around 6.0-6.5, suggesting that the majority of content is perceived as "average to good."
- **Content Release Year Distribution:** A line chart illustrated a sharp surge in content releases peaking around 2019-2020, followed by a noticeable decline in recent years.
- **Content Type over Runtime and IMDb Score:** Scatter plots indicated that movies generally have longer runtimes and a wider range of IMDb scores, while shows are typically shorter with consistently higher scores (mostly between 5.5 and 9).
- **TMDB Popularity vs. Runtime with IMDb Score:** This bubble chart highlighted that highly popular content often includes shorter shows and medium-length movies, frequently boasting high IMDb scores.
