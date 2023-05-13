# Classification Of Talent Hunting With Machine Learning

# Business Problem
The goal is to predict whether football players are in the "average" or "highlighted" class based on the scores assigned by scouts to their various characteristics.

# Story of Data Set
The dataset contains data provided by Scoutium, which comprises the scores and features of football players assessed by scouts based on the players' characteristics observed during matches.

The attributes refer to the scores assigned by evaluators to the characteristics of each player they observe and evaluate in a match. (These scores are the independent variables in the dataset.)

potential_labels: Contains potential tags from users who rate players, with their final opinions about the players in each match. (target variable)

In this data set, we have 9 Variables, 10730 Observations, 0.65 mb

# Variables Description
The following contains information about a scout's evaluations of all players on a team's roster in a match.

-task_response_id : The set of a scout's evaluations of all players on a team's roster in a match

-match_id : The id of the corresponding match

- evaluator_id : The id of the evaluator(scout)

- player_id : The id of the respective player 

- position_id : The id of the position that the relevant player played in that match (1=Goalkeeper, 2=Stopper, 3=Right back, 4=Left back, 5=Defensive midfielder, 6=Central midfielder, 7=Right wing, 8=Left wing, 9=Offensive midfielder, 10=Striker)

- analysis_id : The set of a scout's attribute evaluations of a player in a match

- attribute_id : 	The id of each attribute that players were evaluated for

- attribute_value : The value (points) given to a player's attribute by a scout

- potential_label : Label that indicates the final decision of a scout regarding a player's potential in a match (target variable)


The position_id indicates the position that the player played in that match. The following are the mappings for each position_id:
- Goalkeeper
- Stopper
- Right back
- Left back
- Defensive midfielder
- Central midfielder
- Right wing
- Left wing
- Offensive midfielder
- Striker

The potential_label column represents the ultimate evaluation made by the scout regarding a player's potential, and serves as the target variable for predictive modeling tasks.

# TASKS





