# IMDB-Movie-Release-Timing-Analysis
This project analyses an IMDB movie dataset to identify the optimal time of year to release a film in order to maximise box office revenue. The analysis is designed from an investor perspective, using historical data to uncover seasonal trends in movie performance.
Objectives
Analyse how movie revenue varies across different months of the year
Identify the best release window for maximising financial returns
Explore genre-specific seasonal trends
Provide data-driven recommendations for investors and studios

Dataset
Source: Kaggle IMDB Movies Dataset
Size: ~10,000 films
Key features:
raw_release_date — original release date (DD/MM/YYYY)
revenue — box office revenue
budget — production budget
genre — movie genres
genre_first — primary genre (derived)

Technologies Used
Python
pandas — data cleaning and transformation
NumPy — numerical operations
Matplotlib — data visualisation
Seaborn — advanced plotting
Jupyter Notebook — analysis and presentation

Methodology
1. Data Cleaning & Preparation
Converted raw_release_date into datetime format
Extracted:
month (1–12)
year
Handled missing values
Created derived features:
profit = revenue - budget
roi = revenue / budget
2. Feature Engineering
Extracted primary genre (genre_first)
Structured dataset for seasonal analysis
Grouped films by release month
3. Analysis
Calculated median revenue by month
Used median instead of mean to reduce the impact of outliers
Analysed genre-specific trends across months
4. Visualisation
Bar chart: Median Revenue by Month
Line plot: Revenue Trends by Genre and Month

Key Findings
March is the strongest month for film releases based on median revenue
January and February perform better than expected
Summer months (June–August) show stable, strong performance
December underperforms on average, despite some blockbuster successes
Genre-specific trends:
Horror peaks in October
Action/Sci-Fi perform best in summer
💡 Conclusion

The analysis suggests that March is the optimal release month for maximising typical box office performance.
