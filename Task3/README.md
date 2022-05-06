Based on your insights from the data exploration phase, and using the same training data, perform systematic classification experiments in your team. (At the start of this phase, we will give you the definite 4-class labels for the training examples)

Focus on predicting the 4 emotion classes from the audio features (or a well-chosen subset of these). In your team, we want you to focus on the following aspects:

1. How was the cross-validation split done, and why? Decide how to split up the data into folds, based on what you know about the data.

2. Which subset of features was selected or which preprocessing was applied, and why?

3. What would be an appropriate evaluation criterion to compare parameter settings and algorithms?

4. Apply at least four different learning algorithms (from different major groups: Support Vector Machines, Neural Networks, Nearest Neighbor Classifiers, Naive Bayes, Decision Trees, Generalized Linear Models, Linear and Quadratic Discriminant Analysis... maybe also an "ensemble method" such as a Random Forest). For each algorithm perform a systematic evaluation of different parameter settings, and focus on two aspects:

  * investigate whether overfitting occurs, and to what extent, as well as which parameter control the overfitting behavior.

  * How do classification results change when varying the parameters?

5. BONUS: Train at least one classifier on predicting (a relevant subset of) the 9 items in the GEMS and 5 items in the GEMMES (i.e., treat each of these features as independent binary classification problems). This may come handy for the challenge! Note that these features will not be provided for the test set.
