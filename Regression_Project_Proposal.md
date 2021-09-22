# Regression Project Proposal

## Question/need:
### What is the framing question of your analysis, or the purpose of the model/system you plan to build?
+ Can I predict the average amount of points (goals + assists) per 60 minutes of "on-ice" time that an NHL hockey player will generate during the regular season?

### Who benefits from exploring this question or building this model/system?
+ NHL teams trying to identify the most efficient point scorers for potential player trades/acquisitions.
+ Broadcasting networks that want to televise games that have higher scoring, hence teams with highest average points per 60 minutes of on-ice time per player.

### Data Description:
What dataset(s) do you plan to use, and how will you obtain the data?
+ I plan to use individual player statistics from the past two NHL seasons. For my dataset, I will use players that had a minimum of 60 minutes of "on-ice" time for a given season (e.g. 10 minutes "on-ice" time across 6 games = 60 minutes total "on-ice" time).
+ I will use Beautiful Soup to scrape data from multiple different pages on hockey-reference.com.

### What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?
+ An individual unit of analysis would be one NHL hockey player's season stats for the 2020-2021.
+ Attributes I plan to explore: shots on goal, total shots attempted, average time spent on ice per game, # of penalty minutes, # of blocks, # of hits, age of player, # years of experience, salary of player, nationality of player, winning % of team that player is on, whether player shoots left-handed or right-handed, # of puck takeaways, # of puck giveaways, player's +/- (on ice when team scores goals (+) or on ice when opponent scores goal (-)), player position

### If modeling, what will you predict as your target?
+ I predict there the following attributes will have a positive linear relationship with the average points per 60 minutes of "on-ice" time for an NHL player: shots on goal, total shots attempted, salary, player's +/- and player position.

### Tools:
How do you intend to meet the tools requirement of the project?
+ Beautiful Soup for scraping.
+ Linear Regression Python package.

### Are you planning in advance to need or use additional tools beyond those required?
+ No I am not.

### MVP Goal:
What would a minimum viable product (MVP) look like for this project?
+ Providing a linear regression plot that shows (hopefully) there is a positive linear correlation between the number of shot attempts and a player's points per 60 minutes of ice time.


```python

```
