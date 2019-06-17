# nba_players_clustering

This model aims to analyze and explore the NBA player performance, how different the players are from each other and how the players can be grouped together based on common characteristics.

Point guards play one of the most crucial roles on a team because their primary responsibility is to create scoring opportunities for the team. Machine learning technique K-Means clustering will allows us to visualize the types of point guards as well as group similar point guards together. Using 2 features(Assist to Turnover ratio & Points Per Game) allows us to easily visualize the players and will also make it easier to grasp how clustering works. For point guards, it's widely accepted that the Assist to Turnover Ratio is a good indicator for performance in games as it quantifies the number of scoring opportunities that player created. We will also use Points Per Game, since effective Point Guards not only set up scoring opportunities but also take a lot of the shots themselves.

Some of the selected columns are described below (dataset belongs to 2013 - 2014 season):

* player -- name of the player
* pos -- the position of the player
* g -- number of games the player was in
* pts -- total points the player scored
* fg. -- field goal percentage
* ft. -- free throw percentage
