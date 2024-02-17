# MLB Playoff Win Percentage Analysis
Investigating the relationship between regular season metrics and playoff win percentage in the MLB

## Created by Justin Chambers, Andrew Friberg, Andrew Odnoralov, and Victor King

In this project, the differentials (for and against) per plate appearance between: 

_Homeruns (HR), Singles (S), Unintentional Bases on Balls (UBB), Strikeouts (SO), and On-base Plus Slugging (OPS) are the primary focus._

`MLB_Playoff_WP_Models.Rmd`
Includes code to model MLB 2012-2023 regular season team metrics to estimate team playoff win percentage.

`Runs_Playoffs.csv`
Includes all Runs, Runs Against, Wins, and Losses for each team from 2012-2023 in the MLB.

`Model Outputs`
Contains the summary output of each linear regression model in which each chosen metric is used to indicate playoff win percentage.

`Visualizations`
Contains scatter plots showing the relationship between each metric and playoff win percentage as well as residual plots for each model.
