
# IPL Match & Player Performance Analysis

## Project Overview

This project analyzes IPL match and ball-by-ball data to understand team performance, player performance, toss outcomes, scoring patterns, and venue trends.

The analysis is performed using Python and its data analysis and visualization libraries. The project includes data cleaning, exploratory data analysis, aggregation, ranking, and visualization.

## Project Objective

The main objectives of this project are:

- Analyze IPL matches across different seasons
- Compare team performance using match wins and total runs
- Analyze toss decisions and their relationship with match results
- Identify top run-scoring players
- Analyze player strike rates
- Analyze bowling performance using wickets
- Compare total runs scored by teams
- Analyze IPL matches played at different venues
- Understand the distribution of innings scores
- Apply advanced Pandas operations for data analysis

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Dataset

The project uses two IPL datasets:

- `matches.csv` – Contains match-level information such as season, teams, winner, toss decision, toss winner, venue, and other match details.
- `deliveries.csv` – Contains ball-by-ball information such as batter, bowler, runs, wickets, batting team, and innings.

Both datasets are required to run the complete notebook.

## Project Workflow

1. Import Python libraries
2. Upload and load IPL datasets
3. Explore the datasets
4. Check columns and dataset structure
5. Remove duplicate records
6. Convert date columns where available
7. Check missing values
8. Analyze matches by season
9. Analyze team performance
10. Analyze toss decisions
11. Analyze player batting performance
12. Calculate player strike rates
13. Analyze bowling performance
14. Analyze team scoring
15. Analyze venues
16. Analyze innings score distribution
17. Perform advanced Pandas analysis
18. Generate tables and visualizations
19. Summarize the key findings

## Analysis Performed

### 1. Season and Match Analysis

The number of IPL matches played in each season was calculated and visualized using a line chart.

### 2. Team Performance

Teams were compared based on the number of matches they won.

A bar chart was created to show teams with the highest number of wins.

### 3. Toss Analysis

The project analyzes:

- Toss decisions
- Toss winner and match winner relationship

The analysis helps understand how teams approached the toss and whether the toss winner also won the match.

### 4. Player Batting Performance

Player batting performance was analyzed using total runs scored.

The top run scorers were identified from the ball-by-ball data.

### 5. Strike Rate Analysis

Strike rate was calculated using:

`Strike Rate = (Runs / Balls) × 100`

Only players who faced at least 100 balls were considered for this comparison to make the analysis more meaningful.

### 6. Bowling Performance

Bowling performance was analyzed using the number of wickets taken by each bowler.

Run-outs and other dismissals that are not credited to the bowler were excluded when dismissal information was available.

### 7. Team Run Analysis

The total runs scored by each team were calculated using the ball-by-ball dataset.

The results were visualized using a bar chart.

### 8. Venue Analysis

The number of IPL matches played at different venues was analyzed.

This helps understand which venues hosted IPL matches most frequently.

### 9. Score Distribution

The total score of each innings was calculated and displayed using a histogram.

This was used to understand the distribution and pattern of IPL innings scores.

### 10. Advanced Pandas Analysis

Advanced Pandas operations were used throughout the project, including:

- GroupBy
- Aggregation
- Filtering
- Ranking
- Pivot Tables
- Sorting
- Data transformation

Team rankings based on total runs and season-wise team wins were also analyzed.

## Visualizations

The project includes visualizations such as:

- Number of IPL matches by season
- Teams with most match wins
- Toss decision distribution
- Top run scorers
- Top wicket takers
- Total runs scored by teams
- Venues with most IPL matches
- Distribution of innings scores

## Key Insights

The project analyzes IPL performance from different perspectives:

- Team performance was compared using total wins and total runs.
- Toss decisions and the relationship between toss winners and match winners were analyzed.
- Player performance was evaluated using total runs, strike rate, and wickets.
- Venue-level match counts were analyzed.
- Innings score distribution was used to understand scoring patterns.
- Advanced Pandas techniques were applied to extract meaningful information from the data.

The exact numerical findings can be obtained by running the notebook with the required IPL datasets.

## Skills Demonstrated

- Python Data Analysis
- Pandas
- NumPy
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Aggregation
- GroupBy
- Pivot Tables
- Ranking
- Data Filtering
- Data Visualization
- Matplotlib
- Seaborn
- Cricket Data Analysis
- Business-style Data Interpretation

## Project Structure

```text
ipl_player_performance_Analysis/
│
├── IPL_Match_Player_Performance_Analysis_Colab.ipynb
├── matches.csv
├── deliveries.csv
└── README.md
