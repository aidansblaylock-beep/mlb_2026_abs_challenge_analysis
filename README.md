# 2026 MLB Automated Ball-Strike (ABS) Challenge System Analysis

An exploratory data analysis of the inaugural year of Major League Baseball’s Automated Ball-Strike (ABS) challenge system. This project investigates which teams, player positions, and strategies mastered the system, and tests whether high challenge success correlated with winning games.

## Project Overview & Executive Dashboard
* **Executive Dashboard:** View the full analytical dashboard export (`MLB_2026_ABS_Challenge_Analysis - executive_dashboard.pdf`) directly in this repository.
* **Core Research Question:** *Which teams, players, and positions (catchers vs. batters) mastered the new ABS challenge system during its first year integrated, and did high challenge success actually correlate with winning games?*

## Key Findings & Summary
* **Position Mastery:** Elite catchers dominated the system with a league-wide overturn rate of **58.6%** (3,287 overturns / 5,613 challenges), outperforming batters who achieved **48.9%** (2,328 overturns / 4,765 challenges) due to catchers' impressive strikezone recognition.
* **Team Mastery:** The **Cincinnati Reds** led all teams in efficiency with a **61.6%** overturn rate, while the **Minnesota Twins** generated the highest net run value (`runs_above_average_total`) at **+8.66 runs**.
* **Winning Correlation:** Regression analysis revealed a moderate positive correlation (r ≈ approx 0.45, R² = 0.204) between challenge overturn success and team run value, proving that efficient challenge execution directly supported winning team outcomes by swinging critical ball-strike counts.

## Repository Structure
* `MLB_2026_ABS_Challenge_Analysis - executive_dashboard.pdf` - Visual summary and multi-tab analysis dashboard.
* `abs-challenges-2026-team-summary.csv` - Team-level ABS challenge and run-value dataset.
* `abs-challenges-2026-catcher.csv` - Catcher performance and challenge logs.
* `abs-challenges-2026-batter.csv` - Batter performance and challenge logs.
* `README.md` - Project documentation and summary.

## Tools Used
* **Google Sheets:** Data cleaning, conditional formatting, pivot aggregations, KPI scorecards, and advanced data visualization.
