# ILP_score_prediction

 

‘IPL SCORE PREDICTION PROJECT’ is the project we are working upon which falls under the IPL(Indian premier league)  T-20 . It contains all the data from regarding venues, teams, wickets, runs etc…. through 2008-2020. The primary purpose of working on this project is to predict the score based on the actual, whether the actual and the predicted were similar or not by training the past data. In simple terms, regression is a technique used to predict the unknown value of an object, using the characteristics of the object and by having some information about other similar objects for which we know the value.
 
 Need of the Study 
In this project, the main purpose is to predict the score ,by using the past data and which algorithms predicts well and This algorithm then outputs the winner of two teams using the team rating points that the machine learning algorithm had predicted. Given the player statistics to a machine learning model, the model outputs the rating points for that player based on his statistics. In the final stage, we are left with top two teams. We call the algorithm for one last time and it outputs the Final Winner

 Data Sources 

IPL score prediction- Data contains the information about the all the past data from past 12 years. The dataset contains the information like runs, venues, batsman , teams , wickets…etc
 
 
 #### Dataset Description
 
 Contains  rows 76014 and 8 columns 
 
• mid: Unique match id.

• date: Date on which the match was played.

• venue: Stadium where match was played.

• battingteam: Batting team name.

• bowlingteam: Bowling team name.

• batsman: Batsman who faced that particular ball.

• bowler: Bowler who bowled that particular ball.

• runs: Runs scored by team till that point of instance.

• wickets: Number of Wickets fallen of the team till that point of instance.

• overs: Number of Overs bowled till that point of instance.

• runslast5: Runs scored in previous 5 overs.

• wicketslast5: Number of Wickets that fell in previous 5 overs.

• striker: max(runs scored by striker, runs scored by non-striker).

• non-striker: min(runs scored by striker, runs scored by non-striker).

• total: Total runs scored by batting team at the end of first innings.

## Algorithms Used
- *Decision Tree Regressor*
- *Linear Regression*
- *Random Forest Regression*
- *Lasso Regression*
- *Support Vector Machine Regression*
- *Neural Network Regression*

