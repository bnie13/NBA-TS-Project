NBA True Shooting Percentage (TS%) Analysis

This notebook explores what factors most strongly influence a player’s True Shooting Percentage (TS%), an advanced efficiency metric that incorporates field goals, 3-pointers, and free throws. The analysis examines player usage rate, shot attempts, minutes played, and age to understand their relationships to scoring efficiency across multiple NBA seasons.

Objectives

Investigate how player characteristics (age, minutes played, usage rate, etc.) affect TS%

Visualize trends and correlations between shooting efficiency and play style

Identify which variables contribute most to efficient scoring

Tools and Libraries

Python

Pandas for data processing and cleaning

Matplotlib / Seaborn for data visualization

NumPy for numerical operations

Data Description

The dataset contains player-level NBA statistics across multiple seasons, including:

ts_pct: True Shooting Percentage

usg_pct: Usage Rate

age: Player age

mp: Minutes played

fg3a_per_g: 3-point attempts per game

fta_per_g: Free throw attempts per game

Only players who appeared in at least 30 games per season were included to maintain statistical relevance.

Key Findings

Usage Rate vs. TS%: Moderate-usage players tend to have the highest efficiency, suggesting diminishing returns for heavy ball-dominant roles.

3-Point Attempts: Players attempting more 3-pointers per game generally achieve higher TS%.

Age: Efficiency peaks for players in their mid-to-late 20s, with slight declines afterward.

Minutes Played: More minutes correlate with higher TS% up to a point, then plateau.

Example Visualizations

Scatter plots showing usg_pct vs ts_pct to visualize efficiency trends

Histograms showing TS% distribution by age group

Line plots comparing average TS% over time

Correlation matrix illustrating relationships between variables

How to Run

Clone or download this repository.

Open MidtermProject_Nie_Bruce.ipynb in Jupyter Notebook or VS Code.

Run all cells to reproduce the full analysis and figures.

Author

Bruce Nie
Data Science Major @ UC San Diego
