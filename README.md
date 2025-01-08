🔍 An exciting project combining professional basketball and data, whose mission was to optimize on-court strategies thanks to the analysis of a basketball team's lineups 🏀 

## Objectives : 

Assess the profitability of different compositions for the Le Mans Sarthe Basket Pro A team during the 2024-2025 season, and provide the coach with a decision-making tool to adjust game strategies based on data and player performance. 

Project stages:
- Discovery of key basketball concepts
- Exploration of available data, retrieved thanks to a professional tool made available to basketball professionals and updated after games.
- Webscraping to enrich the analysis with key information such as the rankings of Pro A basketball teams in France, player socio-demographic data, etc.
- Statistical analysis to better understand team compositions, strengths and weaknesses
- Creation of metrics to identify the most profitable and successful lineups 
- Creation of a decision-making tool to guide the coach's strategic choices
- Recommendations based on the analyses made possible by the study's data and measurements.

Tools used:
🐍 Python for data processing and webscraping.
📊 Power BI to visualize performance and generate decision-making insights.

## Files descriptions : 

Data retrieved from the professional platform : 
- statistical data for each of the lineups for each of the 16 Pro A Basketball teams in France. Includes the following information: player composition, total points scored, total points conceded, plus/minus, game time, field goals made and attempted, free throws made and attempted, rebounds, turnovers, fouls, possessions. 
- statistical data for all players on all 16 teams. Including the following information: game time, number of games played, number of points scored, field goals made and attempted, free throw made and attempted, rebounds, assists, steals, turnovers, blocks, fouls, plus/minus.
- statistical data for each team. Including the following information: playing time, number of games played, number of points scored, field goals made and attempted, free throw made and attempted, rebounds, assists, steals, turnovers, blocks, fouls, plus/minus.

Data recovered by webscraping on the L'Equipe website and on the website of the national basketball league: Betclic : 
- socio-demographic data for each player: age, height, position
- general league data: team rankings by points, true shooting by team

Creation of 19 files : 
- Lineup files: one file per team (16 in total) containing data from the professional platform and the calculation of new sports profitability measures defined during our initial analysis.
- Lineup profitability file: containing all profitability data for all lineups (16 previous files)
- Team file: containing player data from the professional platform and webscraping
- Player file: containing player data from the professional platform and webscraping

## Challenges : 

We were faced with the following technical challenges: 
- webscraping data recovery
- data cleansing
- creation of join keys to assemble the data
- creation of EDA Python visuals to establish an initial orientation for our analyses

We also faced the following analysis challenges: 
- creation of new relevant measures based on existing data
- extrapolating these data to predict future actions (small data samples due to analysis at the start of the 2024-2025 season)
- creation of an easy-to-use tool for coaches, enabling them to easily visualize, understand and update data

## Analysis and Recommandations : 

We were able to identify the strengths and weaknesses of the Basket Sarthe Le Mans team: 
+ among the best time-returns on the line, as it is one of the teams whose lineups get the most possessions during games
- need to improve profitability per possession (due to poor shot selection, poorly executed attacks or too many lost balls).

We were able to analyze that there was a strong correlation between profitability per possession and the offensive level. This means that a team that maximizes its possessions scores more points.  

## Link : 
[Analyse de rentabilité par lineup](https://msblineuprentabilite.streamlit.app/)
