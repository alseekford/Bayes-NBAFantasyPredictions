# NBA Fantasy Basketball Predictions  
**Using a Hierarchical Framework to Model the Effects of Player Position on Predicted Fantasy Basketball Performance**  

DS6040: Bayesian Machine Learning Final Project  
Neil Antrassian, Noah Dunn, Anne Louise Seekford  



### Data


```RANK```: player rank  
```MIN%```: Minutes PercentagePercentage of team minutes used by a player while he was on the floor  
```USG%```: Usage RateUsage rate, a.k.a., usage percentage is an estimate of the percentage of team plays used by a player while he was on the floor  
```TO%```: Turnover RateA metric that estimates the number of turnovers a player commits per 100 possession  
```eFG%```: Effective Shooting PercentageWith eFG%, three-point shots made are worth 50% more than two-point shots made. eFG% Formula=(FGM+ (0.5 x 3PM))/FGA  
```TS%```: True Shooting PercentageTrue shooting percentage is a measure of shooting efficiency that takes into account field goals, 3-point field goals, and free throws  
```PPG```: PointsPoints per game  
```RPG```: ReboundsRebounds per game  
```TRB%```: Total Rebound PercentageTotal rebound percentage is estimated percentage of available rebounds grabbed by the player while the player is on the court  
```APG```: AssistsAssists per game  
```AST%```: Assist PercentageAssist percentage is an estimated percentage of teammate field goals a player assisted while the player is on the court  
```SPG```: StealsSteals per game  
```BPG```: BlocksBlocks per game  
```TOPG```: TurnoversTurnovers per game  
```VI```: Versatility Index = Versatility index is a metric that measures a player’s ability to produce in points, assists, and rebounds. The average player will score around a five on the index, while top players score above 10  
```ORTG```: Offensive RatingIndividual offensive rating is the number of points produced by a player per 100 total individual possessions  
```DRTG```: Defensive RatingIndividual defensive rating estimates how many points the player allowed per 100 possessions he individually faced while staying on the court  



### Using the Files

#### Data Files:

```20-21BoxMetrics.xlsx```: 2021-2022 season average box score stats for NBA players 

```21reg_season.xlsx```: 2021-2022 season average box score stats for NBA players

```Use_This_WithPM.csv```: Game-by-Game player statistics - most recent/updated version

``Use_This.csv```: Game-by-Game player statistics - older/redundant version

```all-player_game_stats.csv```: 2021-2022 season average box score stats for NBA players

```game1.csv```: Table for matching game_id from player_game1 and players, in order to look at player statistics on a game-by-game basis

```kaggleactive_players_2.csv```: Table of active NBA players, used to match player_id to actual player names and determine which teams each player played for

```kaggleplayers.csv```: Table of all NBA players, used to match player_id to actual player names and determine which teams each player played for

```player_game1```: Table with individual player performance statistics in each game during 2021

```player_game_stats.csv```: 2021-2022 season average box score stats for NBA players

```players.csv```: Table for matching player_id in player_game1 with their actual names in game1



#### Notebook Files:

```FinalProject copy.ipynb```: A notebook used for cleaning and adjusting NBA player data - not useful now that final CSV files have been created

```Hierarchical_Model.ipynb```: The first iteration of this notebook - used for exploratory analysis between datasets, model types, predictor variables, and computation methods

```Hierarchical_Model_1.ipynb```: The second iteration of this notebook - used for exploratory analysis between datasets, model types, predictor variables, and computation methods

```SaturdayModel.ipynb```: Used for exploratory data analysis, dataset cleaning, and model selection

```NormalPreds.ipynb```: This is the final notebook, containing the final datasets being used and the final hierarchical pymc model. This is the notebook that will be used in order to inspect final model outputs. In order to use this file, simply load the notebook in the same folder as the data files in the Data folder.






