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

-evaluator_id : The id of the evaluator(scout)

-player_id : The id of the respective player 

-position_id : The id of the position that the relevant player played in that match (1=Goalkeeper, 2=Stopper, 3=Right back, 4=Left back, 5=Defensive midfielder, 6=Central midfielder, 7=Right wing, 8=Left wing, 9=Offensive midfielder, 10=Striker)

-analysis_id : The set of a scout's attribute evaluations of a player in a match

-attribute_id : 	The id of each attribute that players were evaluated for

-attribute_value : The value (points) given to a player's attribute by a scout

-potential_label : Label that indicates the final decision of a scout regarding a player's potential in a match (target variable)


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

# Tasks

Step 1: scoutium_attributes.csv and scoutium_potential_labels.read the csv files

Step 2: Combine the csv files we have read using the merge function.("task_response_id", 'match_id', 'evaluator_id' "player_id" Perform the merge operation over 4 variables.)

Step 3: Remove the Keeper (1) class in position_id from the dataset.

Step 4: Remove the below_average class in potential_label from the dataset.(the below_average class makes up 1% of the entire data set)

Step 5: Create a table from the dataset you have created using the “pivot_table” function. One player per row in this pivot table
make manipulation in a way that it will be.

Step 6: Express the ”potential_label" categories (average, highlighted) numerically using the Label Encoder function

Step 7: Assign the numeric variable columns to a list with the name ”num_cols"

Step 8: Apply StandardScaler to scale the data in all the “num_cols” variables that you have saved.

Step 9: A machine learning model that predicts the potential tags of football players with minimal error over the data set we have
develop it. (Print the roc_auc, f1, precision, recall, accuracy metrics.)

Step 10: Draw the ranking of the properties using the feature_importance function, which specifies the level of importance of the variables






