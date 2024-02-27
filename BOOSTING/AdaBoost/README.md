# AdaBoost (Adaptive Boosting)

- AdaBoost is an Ensemble Learning Algorithm.
- It uses Boosting method.
- It is a Supervised machine-learning algo.
- AdaBoost Combines the Prediction from Multiple(Weak-Learners) to build a (Strong-Learner).

#### Working
- It creates Decision-STUMPS (decision-trees with only 1-depth).
- There can be multiple STUMPS created, based on the no.of columns.
- STUMPS (it is like a Root-Node) & in stump, there will be the columns choosen whose Entropy is least.
# 
- Step1 - Assigns Equal weight to all the training examples.
- Step2 - Train the weak-learners Sequentially.
- Step3 - Calculate the weighted-error made by the weak-learners.
- Step4 - Adust the weights of Training examples, Increase the weights of wrongly-predicted examples, so that they become more-important fot the next model. Decrease the weights of correctly-predicted examples.
- Step5 - The next Model will Decrease the weights of the wrongly-predicted examples.
- Step6 - After all the weak-learners had done with their prediction. AdaBoost combines the prediction from the (weak-learners) to build (Strong-Classifier).
