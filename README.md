# A-B-Testing-Mobile-Game

A/B Testing Project: Impact of Gate Placement on Player Retention in Cookie Cats

Project Overview

This project aims to evaluate the effect of moving the first in-game gate from level 30 to level 40 on player retention metrics (1-day and 7-day retention) in the mobile puzzle game Cookie Cats.

Objective

Determine the optimal placement of the first in-game gate to maximize player retention.


Methodology

Data Collection

Dataset: 90,189 players
Variables: user ID, assigned gate level (30 or 40), total game rounds played in the first 14 days, 1-day retention, and 7-day retention indicators.
Sanity Check

Verified even distribution of players between gate_30 and gate_40 groups.
Exploratory Data Analysis

Plotted the distribution of game rounds played to understand player engagement.
Retention Analysis

1-Day Retention:
Calculated overall retention.
Compared retention rates between the two groups.
Statistical Validation:
Applied bootstrapping to estimate the certainty of differences in retention rates.
Found a 95% probability that 1-day retention is higher at level 30.
7-Day Retention:
Calculated and compared retention rates for both groups.
Performed bootstrapping for 7-day retention.
Indicated a 100% probability that 7-day retention is better with the gate at level 30.
Results

1-Day Retention: Slight decrease when the gate is at level 40 compared to level 30.
7-Day Retention: Greater decrease when the gate is at level 40.
Bootstrapping Analysis:
95% probability that 1-day retention is higher at level 30.
100% probability that 7-day retention is higher at level 30.
Conclusion

To maximize player retention, the in-game gate should remain at level 30. Moving the gate to level 40 results in lower 1-day and 7-day retention rates.

Additional Notes

Further metrics, such as game rounds played and in-game purchases, could be analyzed for a more comprehensive evaluation.
The theory of hedonic adaptation may explain why earlier gate placement improves retention by preventing players from getting bored and quitting the game.
