## Project Goal:
Predict the outcome of games at the end of each play using only in-game statistics like shots,
points, rebounds, etc. We are explicitly ignoring which teams and players are playing 
and their historical performance.


## Sourcing the Data
Find the NBA play by play data through the Kaggle link below
* https://www.kaggle.com/datasets/schmadam97/nba-playbyplay-data-20182019

## Files:
* data_exploration_eda.ipynb: initial lightweight eda
* data_preprocessing.ipynb: convert data to 'stacked' dataset where each row contains data for only
one team + game
* model_selection_and_validation.ipynb: contains the model classes and relevant training
and testing code
* results/results.csv: text file containing results from each model run (both cross-validation
and validation results)
