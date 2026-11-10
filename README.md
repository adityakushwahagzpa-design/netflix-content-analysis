# Netflix Content Analysis | Python

Analysis of the Netflix titles dataset – **6,234 movies and TV shows** added between 2008 and January 2020 – in Python. Covers data loading, quality checks, cleaning and feature engineering, and 10 questions on content mix, growth, countries, genres, ratings, duration and content age.

## Data cleaning
- Missing director (31.6%), cast and country filled with "Unknown" rather than dropping rows
- Rows with no date added or rating dropped (under 0.4%); 3 duplicate title + type + year rows removed
- New features: year and month added, content age, duration value and unit

## Key findings
- **6,202 titles** after cleaning; **68.6% movies**
- Top country: United States; top genre: International Movies; most common rating: TV-MA
- Median movie length **98 minutes**; **67.5% of TV shows** have only one season
- 34.5% of titles were added in the same year they were released
- December is the busiest month for new titles (690) and February the quietest (377)

## Files
- `Netflix_Content_Analysis.pdf`

## Tools
Python · Pandas · NumPy · Matplotlib · Seaborn

## Author
**Aditya Kushwaha** · [LinkedIn](https://www.linkedin.com/in/aditya-kushwaha16)
