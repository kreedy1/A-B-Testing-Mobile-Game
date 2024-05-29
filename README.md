# A-B-Testing-Mobile-Game

A/B Testing Project: Analyzing the Impact of Gate Placement on Player Retention in Cookie Cats

Objective: To evaluate the effect of moving the first in-game gate from level 30 to level 40 on player retention metrics (1-day and 7-day retention).

Methodology:

Data Collection: Collected data from 90,189 players, including user ID, assigned gate level (30 or 40), total game rounds played in the first 14 days, and 1-day and 7-day retention indicators.
Sanity Check: Ensured even distribution of players across the two groups.
Exploratory Data Analysis: Plotted the distribution of game rounds played.
Retention Analysis:
Calculated overall 1-day retention.
Compared 1-day retention rates between the two groups, finding a slight decrease when the gate was at level 40.
Statistical Validation: Used bootstrapping to assess the certainty of observed differences in 1-day retention, revealing a 95% probability that retention is higher at level 30.
7-Day Retention Analysis:
Calculated and compared 7-day retention rates, noting a greater decrease when the gate was at level 40.
Performed bootstrapping for 7-day retention, indicating a 100% probability that retention is better with the gate at level 30.
Conclusion: Both 1-day and 7-day retention are higher when the gate is placed at level 30. To maximize player retention, the gate should remain at level 30.
