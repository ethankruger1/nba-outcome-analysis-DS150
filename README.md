# NBA Game Outcome Analysis

Predicting NBA game outcomes using team performance data pulled directly from the NBA API across 5 seasons (2021–22 through 2025–26).

## Dataset

- **Source:** NBA API (`nba_api` Python package)
- **Files:** `data/all_games.csv`, `data/standings.csv`
- **Rows:** 12,300 game logs across all 30 teams
- **Key columns:** `WL`, `PTS`, `FG_PCT`, `FG3_PCT`, `REB`, `AST`, `TOV`, `PLUS_MINUS`, `SEASON`

## How to Run

1. Clone this repository
2. Install dependencies: `pip install nba_api pandas matplotlib seaborn scikit-learn`
3. Open `nba_analysis.ipynb` in Jupyter or VS Code
4. Run all cells from top to bottom

## Approach

- Pull game logs and standings data via NBA API
- Clean and explore the dataset (shape, nulls, dtypes)
- Analyze team performance trends across all 30 teams
- Case study: Minnesota Timberwolves deep dive
- Build a model to predict game outcomes (W/L)

## Key Questions

- Which stats best predict whether a team wins?
- How does the Timberwolves' performance compare league-wide?
- What patterns emerge across 5 seasons of game data?
