# Module-4-Process-of-solving-any-machine-learning-problem
Introduction to machine learning (intro) - general questions on article
 
Scikit-learn
Installed! (in terminal, like usual - correct?)

1. "Creating artificial datasets"
* Essentially just created to try out algorithms and models?

2. "Features scaling"
* By "features" we're talking about "attributes"? (the x and y)

3. "Feature selection"
* "Discarding low variance" Is this just study-dependent? "Discarding" features makes me nervous!

4. "Data Splitting"
* Train and test group split? Always 80/20 split? Why?

5."High-level overview of using scikit-learn" 
(Core steps for building and evaluating models)
* Are all the algorithms we use un machine learning essentially learning algorithms? (and there are many different ones?)
* Using this alogorithm in scikit-learn we follow the 5 steps:
from sklearn.modulename import EstimatorName      # 0. Import
model = EstimatorName()                           # 1. Instantiate
model.fit(X_train, y_train)                       # 2. Fit
model.predict(X_test)                             # 3. Predict
model.score(X_test, y_test)                       # 4. Score
* So, this learning algorithm (using actual algorithm details) is used and it is what we then call the "model"?
* "estimatorname" is the specific algorithm name?
* Is this also the "instantiate"?
* The training is initiated with training function (fit())... the "trained" dataset came from before?

6. "Hyperparameter tuning"
* What exactly is a "hyperparameter"? (fine tuning?)
* When "workflow" is mentioned (often) - are they referring to the "model building" being in place?
* Performing the Hyperparameter tuning...code block - bit confusing.