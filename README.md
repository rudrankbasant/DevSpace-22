# DevSpace-22
## IPL CASE STUDY 2022
### Approach
Our team will use Pandas module for Python to create a data-frame of the ball-by-ball dataset provided on Kaggle. The data will be cleaned and iterated through to generate the following season based statistics:</br>
1. Runs scored by a batsman (used to derive the strike rate)
2. Balls bowled per wicket for a bowler and runs conceded (used to derive the economy of the bowler)
3. Win percentage of each team and player
4. Performance in various game phases - such as the powerplay, middle overs and death overs.</br>
5. 
Using regression models, the above season-by-season statistics will be extrapolated to the current season and used for further predictions. External factors like form/fitness are not taken into account unless insights are visible in the dataset.</br>

The above statistics will be compiled to give each player in the current tournament a relative score out of 100. Greater the score, the “better” a player’s contribution to his team. The score of a team will thus be calculated as the sum of the scores of the playing 11.</br>

Using the cumulative scores of the teams the final standings of the tournament are predicted. Critical players are identified as those who generate a large impact on a game - such as an accelerated run-rate or a multi-wicket spell.</br>

Chasing and defending teams are benefited by the presence of these critical players.
