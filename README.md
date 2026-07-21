# chelsea-season-comparison

A data analysis comparing Chelsea FC's performance under two managers: **Mauricio Pochettino (2023/24)** and **Enzo Maresca (2024/25)**.

## Background
Pochettino's 2023/24 season was billed as the true start of the Clearlake ownership era at Chelsea  unlike his predecessors, who were sacked within months, he was given a full season to build the squad. Despite heavy spending and no European football to juggle, expectations were to finish high enough for Champions League or Europa League qualification. Instead, Chelsea finished 6th and qualified only for the Conference League  an underwhelming return given the investment and lack of distractions. Pochettino departed at the end of the season, and Enzo Maresca took over for 2024/25. The results, as this analysis shows, speak for themselves.


## What this is
This project uses player-level statistics from both seasons to compare squad performance across the two managerial eras  goal contributions, team totals, per-90 efficiency, and (where available) expected goals (xG/xAG).

## Data
- `pl2324.csv` — Premier League player stats, 2023/24 season (Pochettino)
- `pl2425.csv` — Premier League player stats, 2024/25 season (Maresca)

**Note:** the two datasets come from different sources and don't share identical columns. The 2024/25 dataset does not include expected goals (xG) or expected assists (xAG), so the xG/xAG breakdown further down only covers the 2023/24 season  it's not available for 2024/25.

## What's inside the notebook

`poch vs maresca.ipynb` walks through:
1. Loading and cleaning both seasons' data
2. Filtering to Chelsea players only
3. **Goal Contributions** (Goals + Assists)  top 10 per season, compared side by side
4. **Team totals** — goals, assists, and contributions across the full squad
5. **Season summary** — league position, goals conceded, and other headline stats
6. **Goals per 90** — efficiency among players with 500+ minutes played
7. **xG / xAG** — expected goals and assists for the 2023/24 top scorers

## Key takeaways

- Maresca's 2024/25 side scored fewer total goals than Pochettino's 2023/24 side, but conceded far fewer  a much tighter defensive record.
- Pochettino's squad produced more total goal contributions, but Maresca's finished higher in the league table (4th vs 6th) and qualified for the Champions League.

## Requirements

```
pandas
matplotlib
```

## Running it
Open the notebook in Jupyter and run all cells top to bottom.
