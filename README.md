# The League Lab — Part 1: Which League Scores the Most?

**Series:** The League Lab — Dissecting the Top 5 European Leagues with Data  
**Part:** 1 of 6  
**Season:** 2024/25  
**Author:** Antwan Makramallah

---

## Central Question

Which of the Top 5 European leagues produces the highest average goals per 90 minutes among outfield players and is the gap driven by a few elite strikers or consistent across the whole squad?

---

## Key Finding

**The Bundesliga, not the Premier League, leads the Top 5 leagues 
in average goals per 90 minutes.**

Bundesliga averaged 0.1593 goals per 90, 20% higher than the 
lowest-ranked Serie A (0.1264). The Premier League ranked 3th.

---

## Charts

### Average Goals per 90 by League
![Chart 1](outputs/figures/01_avg_goals_p90_by_league.png)

### Full Distribution — Box Plot
![Chart 2](outputs/figures/02_goals_distribution_boxplot.png)

### Top 5 Scorers per League
![Chart 3](outputs/figures/03_top5_scorers_per_league.png)

### Non-Penalty Goals per 90
![Chart 4](outputs/figures/04_non_penalty_goals_p90.png)

---

## Data Source

- **Dataset:** Football Players Stats 2024/25 — Big 5 European Leagues  
- **Source:** Kaggle — hubertsidorowicz  
- **Filters applied:** Outfield players only | Minimum 900 minutes played

---

## Tools Used

Python · pandas · matplotlib · seaborn · Jupyter Notebook

---

## How to Run

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook notebooks/which-league-scores-the-most.ipynb
```

---

## Series Navigation

| Part | Question | Status |
|---|---|---|
| Part 1 | Which league scores the most? | ✅ Complete |
| Part 2 | Which league creates the best chances? | 🔜 Coming |
| Part 3 | Which league converts chances best? | 🔜 Coming |
| Part 4 | Which league has the most creative players? | 🔜 Coming |
| Part 5 | Who are the top performers across all leagues? | 🔜 Coming |
| Part 6 | The full picture — final league rankings | 🔜 Coming |
