# IMDb Top 1000 Movies Analysis

A comprehensive Exploratory Data Analysis (EDA) project examining the top 1000 IMDb movies to uncover patterns, trends, and business insights about what makes movies successful.

## Project Overview

This project analyzes a dataset of the top 1000 IMDb movies to extract actionable business insights for stakeholders in the entertainment industry. Through data cleaning, visualization, and statistical analysis, we explore relationships between movie attributes such as ratings, genres, gross, director performance, and audience engagement.

**Key Questions Explored:**
- Which genres dominate the top-rated movies?
- Is there a correlation between a movie's rating and voted?
- How do high ratings translate to audience engagement (votes)?
- Who are the most prolific and successful directors in the top 1000 list?

## Key Findings

### Genre Dominance
- **Drama** appears in **28.9%** of top 1000 movies
- **Comedy** follows with **15.5%** of appearances
- Top 3 genres account for over 35% of all genre tags

### The Blockbuster Paradox
- Highest grossing movie: *Star Wars: Episode VII - The Force Awakens* ($936.7M)
- Its rating (7.9) is actually below the dataset average (7.95)
- **Insight:** High budget ≠ guaranteed critical acclaim

### Audience Engagement
- **Positive correlation (0.495)** between IMDB rating and number of votes
- Movies rated >8.5 average **1.2M** votes
- Movies rated <7.8 average only **0.2M** votes
- **Insight:** High ratings drive 3x more audience interaction

### Director Performance
- **Alfred Hitchcock** leads with 14 movies in the top 1000
- **Steven Spielberg** follows closely with 13 movies
- Top 3 directors (Hitchcock, Spielberg, Miyazaki) represent **37.6%** of the top 10 directors' contributions

## Business Recommendations

Based on the analysis, here are actionable recommendations:

1. **Content Strategy:** Prioritize Drama content acquisition and highlight dramatic elements in marketing, even for mixed-genre films
2. **Portfolio Balance:** Allocate approximately 70% to commercial projects and 30% to critically-oriented films
3. **Engagement Focus:** Leverage highly-rated films (8.5+) to drive platform engagement and encourage user reviews
4. **Talent Investment:** Build relationships with proven directors who consistently deliver high-quality content

## Technologies Used

- **Python 3.13+**
- **Pandas** - Data manipulation and cleaning
- **Matplotlib** - Data visualization
- **Jupyter Notebook** - Interactive development environment

## Project Structure
IMDb-Movie-Analysis/
│
├── movies_rating_analysis.ipynb # Main analysis notebook
├── movie-data.csv # Dataset
├── README.md # Project documentation
├── requirements.txt # Python dependencies
└── .gitignore # Git ignore file

## Future Enhancements

Analyze the impact of runtime on movie ratings

Investigate successful genre combinations

Create interactive visualizations with Plotly

Build a predictive model for movie success

Add analysis of actor/director collaborations

## Contributions

Contributions are welcome! If you have any suggestions for improvements or would like to collaborate, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License