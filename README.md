This dataset comprises of all the information about eleven different soccer leagues played across eleven different countries. We acquired European soccer database from Kaggle, which was in “*.sqlite” format. We explored the dataset in R using “RSQLite” library. Our dataset had 7 tables, out of which we identified Match as our primary data source and Playerstats as our secondary data source. 

Our analysis included the below points:
•	We merged the data from player to player stats and team to match dataset.
•	We constructed Points Table for each team during each season across all leagues from the match dataset using R functions and excel. This later became our primary dataset which is linked to player stats using a team id.
•	We developed five major insights, the first being finding those teams which played well consistently in the top division leagues of 11 Europe countries for 8 seasons from 2008 to 2016.
•	Based on our observation from insight 1, we focused on EPL since it had the most dominating teams in the league and observed that 3 teams were dominant in comparison to others.
•	We decided to further drill down and focused on Manchester United as there was a dip in their performance in the past few years.
•	Insight 3 focused on Manchester United, we compared the team of Manchester United in 2013(Champions) to the team in 2016(finished 5th) 
•	Insight 4 focuses on scouting players from other leagues so as to improve Manchester United.
•	Star players and potential players were identified using player stats which summarizes insight 5.
•	We concluded by comparing our analysis with actual decisions made by Manchester united in 2016.
