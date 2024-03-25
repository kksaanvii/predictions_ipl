# Preditions for IPL score
Dataset Description

• mid: Unique match id.

• date: Date on which the match was played.

• venue: Stadium where match was played.

• battingteam: Batting team name.

• bowlingteam: Bowling team name.

• batsman: Batsman who faced that particular ball.

• bowler: Bowler who bowled that particular ball.

• runs: Runs scored by team till that point of instance.

• wickets: Number of Wickets fallen of the team till that point of instance.

• overs: Number of Overs bowled till that point of instance.

• runslast5: Runs scored in previous 5 overs.

• wicketslast5: Number of Wickets that fell in previous 5 overs.

• striker: max(runs scored by striker, runs scored by non-striker).

• non-striker: min(runs scored by striker, runs scored by non-striker).

• total: Total runs scored by batting team at the end of first innings.

Algorithms Used
Decision Tree Regressor
Linear Regression
Random Forest Regression
Lasso Regression
Support Vector Machine Regression
Neural Network Regression
