# Beatport Data Analysis: Danceability Score Focus

This project analyzes Beatport's electronic music catalogue by integrating Spotify's **Danceability Scores** (ranging from 0.0-1.0). The goal is to uncover genre-specific trends and derive insights that may support optimization strategies for further enhancing the music collection.

## Key Features
- Combined Beatport (CSV) and Spotify(SQLite) datasets using Python and SQL
- Enriched Beatport tracks with Spotify audio features - focusing on danceability
- Managed ~30% unmatched entries (no Spotify match); analysis was conducted only on matched entries
- Performed:
   - Exploratory Data Analysis (EDA) with visualizations
   - Basic regression modeling (R² = 0.55, RMSE = 0.05)
- Insights: genre distribution, and average danceability score per genre

## Tools&Libraries
- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `pickle`
- **Database**: SQLite
- **Environment**: Jupyter Notebook

## Installation & Usage

Note: This notebook was created using data from Spotify and Beatport, which is **not included** in this repository to avoid potential licensing or usage restrictions. As a result, the code cells may not run unless you obtain similar data separately.
 
1. Download the required data (CSV files and `spotify.db`)
2. Open the notebook file (.ipyn) in Jupyter or another IDE
3. Run the cells to explore the analysis

## Future Work:
- Improve predictive modeling using advanced ML techniques (e.g. `RandomForest`)
- Feature selection to identify key factors influencing danceability
- Create a custom "Beatport Danceability Score" using user preferences and internal metrics 

## Limitations

- Dataset covers only a subset of Beatport's catalog
- ~30% of tracks had no match in Spotify, affecting the completeness of the danceability   analysis
- Danceability is subjective and is here based on Spotify's own internal algorithm

*Please note that this was my first hands-on experience with data science. The goal was primarily about learning and exploration, rather than producing a polished, professional analysis or highly accurate model. As such, the methods used are intentionally simple, and some assumptions may not hold under more rigorous scrutiny. 
*That said, I had a lot of fun creating this project and hope you enjoy exploring it just as much!*


## Author
Denise Rappold, Data Science Student at University of Stuttgart

## Acknowledgements

All data and accompanying documentation (PDF files) were provided as part of *Data Science with Python* at *University of Stuttgart*.
*The observations made about Beatport and Spotify reflect the data used and do not intend to endorse or criticize any platform.*
