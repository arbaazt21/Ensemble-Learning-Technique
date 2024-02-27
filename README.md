# Ensemble-Learning-Technique
Ensemble:- Combining multiple models
- It uses Multiple Learning Algorithms, so that it can make better Prediction and Accuracy.

## Methods of Ensemble Learning Technique:-
- BAGGING (Booststrap - Aggregation)
- BOOSTING

#### 1) BAGGING 
- Works Parallelly.
<img align="center" alt="Coding" width="400" src="https://miro.medium.com/v2/resize:fit:1050/1*a6hnuJ8WM37mLimHfMORmQ.png">

- Training Dataset is divded(Bootstraping) into multiple subsets(sample-data).
- Sample-data is distributed to Multiple Weak-learners(Models).
- Weak-learners train the data and makes Prediction(Classifies).
- Predictions from multiple weaklearners is Combined(Aggregation) together.
- Now, VOTING CLASSIFIER is present in the Bagging method,
- It does Majority Voting, It chooses the Output with Max-Votes.
- Ex:- (Random-Forest)

  # 

#### 2) BOOSTING
- Works Sequentially.
- Boosting is used to build Strong-Classifier from the no. of Weak-learner.
<img align="center" alt="Coding" width="400" src="https://miro.medium.com/v2/resize:fit:1400/1*jbncjeM4CfpobEnDO0ZTjw.png">

- w = Weighted-Error (wrong-predictions)
- Model-1 is built(makes Predictions) from Training-Data, (it makes some wrong-predictions)
- This wrong-predictions made by Model-1 are sent to the Model-2 (as weigted-error), so that it can pay more attention to it, and make it correct.
- Model-2 is built(makes Predictions) from Training-Data, (it makes some wrong-predictions)
- This wrong-predictions made by Model-2 are sent to the Model-3 (as weigted-error), so that it can pay more attention to it, and make it correct.
- This Process Continues and Multiple Models are added until the Correct-Predictions are made.
- Now it becomes a Strong-Classifier.
- Ex:- (AdaBoost, Gradient Boosting, XgBoost, CatBoost)
