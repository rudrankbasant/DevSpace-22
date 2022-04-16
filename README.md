 <h1 align="center">IPL CASE STUDY 2022</h1>
 <p align="center">
  <img src="https://user-images.githubusercontent.com/85751479/163662303-3d51d3e7-bfe4-4e80-b27f-323bd3973aa4.png" width="350" height="250">
</p>

## Problem Statements
Your team has been hired by an IPL franchise (a team of your choice) to enable the team with all necessary Data & AI assistance. They have the following questions being asked now for which the answers need to be based on the past data (IPL related data till 2021) and hidden insights/trends.</br>


1.Which teams would qualify for play-offs in the Tata IPL 2022 (assume that this is start of Tata IPL 2022 and no matches have been played till date for this season. Please follow the same assumption for further questions unless otherwise specified)</br>
2.Which team would win the trophy in the Tata IPL 2022? </br>
3.Who will win the orange cap and purple cap?</br>
4.Who will be the critical player/players for winning team and why?</br>
5.What strategies/tactics could help the team batting first to win?</br>
6.What strategies/tactics could help the team bowling first to win?</br>


## Approach
Our team will use Pandas module for Python to create a data-frame of the ball-by-ball dataset provided on Kaggle. The data will be cleaned and iterated through to generate the following season based statistics:</br>
1. Runs scored by a batsman (used to derive the strike rate)
2. Balls bowled per wicket for a bowler and runs conceded (used to derive the economy of the bowler)
3. Win percentage of each team and player
4. Performance in various game phases - such as the powerplay, middle overs and death overs.</br>

Using regression models, the above season-by-season statistics will be extrapolated to the current season and used for further predictions. External factors like form/fitness are not taken into account unless insights are visible in the dataset.</br>

The above statistics will be compiled to give each player in the current tournament a relative score out of 100. Greater the score, the “better” a player’s contribution to his team. The score of a team will thus be calculated as the sum of the scores of the playing 11.</br>

Using the cumulative scores of the teams the final standings of the tournament are predicted. Critical players are identified as those who generate a large impact on a game - such as an accelerated run-rate or a multi-wicket spell.</br>

Chasing and defending teams are benefited by the presence of these critical players.

## Implementation
We have used the libraries <b>numpy</b>, <b>pandas</b>, <b>matplotlib</b> and <b>seaborn</b>.
<p align="left">
  <img src="https://user-images.githubusercontent.com/85751479/163663137-840a94c5-2bb3-4e1b-9e2d-843b8f1e1368.png">
</p>
<p align="right">
  <img src="https://user-images.githubusercontent.com/85751479/163662982-5f8b1339-e2cb-4165-b550-7b1fe5bf59a3.png" >
</p>

## Website
We have created a [<b>website</b>](https://peaceful-taiga-69267.herokuapp.com/) to present our findings. Login/SignUp to see the predictions.

![image](https://user-images.githubusercontent.com/85751479/163663607-c6fa493c-0653-40b6-b886-c525980fd448.png)


