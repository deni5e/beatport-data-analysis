# Beatport-Datenanalysis (Danceability Score Focus)

This project analyzes Beatport's electronic music catalogue by integrating Spotify's Danceability Scores (ranging from 0.0-1.0). The goal is to uncover genre-specific trends and derive insights that may support optimization strategies for further enhancing the music collection.

## Installation
1. Download the data (CSV files and 'spotify.db')
2. Open the Jupyter Notebook (.ipyn file) in your environment

## Usage
inlucing required environment

## Key Features
- Integration of data from Beatport (CSV) and Spotify (SQLite database) using Pythonand SQL
- Enrichment of Beatport tracks with Spotify audio features, focusing on danceability
- Handling missing data: ~30% of tracks had no Spotify match; analysis was conducted only on matched entries
- Exploratory data analysis and visualizations on daceability trends by genre and release year
- Feature engineering: scaling, standardization
- Basic regression modeling to explore predictive trends (R² = 0.55, RMSE = 0.05)
- Insights include genre distribution, and average danceability score per genre

## Tools&Libraries
- **Python**: 'pandas', 'numPy', 'matplotlib', 'seaborn','Scikit-learn', 'pckle'
- **Database**: SQLite
- **Environment**: Jupyter Notebook

## Future Work:
- Improve predictive modeling using advanced ML techniques (e.g. RandomForest)
- Identify audio features most relevant to danceability key features influencing danceabiltiy
- Develop a costum Beatport danceabilty score using internal metrics and user preferences

## Limitations

- The dataset used includes approximately ~xxxx tracks, which likely represents only a subset of the full Beatport catalogue. Therefore, findings may not fully reflect all genres or the platform's complete offering.
 Roughly 30% of the tracks could not be matched with Spotify entries, reflecting Beatport's specialization in electronical dance music and its inclusion of many niche or exclusive selections within this genre. This might also indicate that the Spotify database used was not fully comprehensive for this particular music segment. Either way, this limitation affects the completeness of the danceabiltiy analysis.
- Danceabilty is a subjective metric, and assessment may vary from personal impression.

*Please note that this was my first hands-on experience with data science. The goal was primarily about learning and exploration, rather than producing a* *polished, professional analysis or highly accurate model. As such, the methods used are intentionally simple, and some assumptions may not hold under more* *rigorous scrutiny.* 
*That said, I had a lot of fun creating this project and hope you enjoy exploring it just as much!*


## Author
Denise Rappold, Data Science Student at Universiy of Stuttgart

*Disclaimer: The observations made about Beatport and Spotify relfect the data used and do not intend to endorse or critize any platform.*
