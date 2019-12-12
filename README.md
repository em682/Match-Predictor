# Match-Predictor

## Plans
Use Reddit API to get comments of past 10 (~10000 comments) win post-game threads and 10 (~10000 comments)loss post-game threads. Classify each comment as win or lose based on the thread they are in. Analyze comments of win threads and loss threads to create ML classification model. Then we predict by testing the model for next games. Each comment in each post-game thread will be classified as win or lose, with values set as 1 for win and 0 for lose. The values are then averaged and if > 0.5 the game would be predicted as a win.

Models that will be tested:
Naive Bayes. Logistic regression (MaxEnt), SVMs, and random forest.
