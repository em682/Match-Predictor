# Match-Predictor

## Motivation
So I became interested in machine learning... After spending hours reading articles on Medium, I decided to just throw myself into doing a basic project and see how it works. I also decided to sign up for an online course, cause why not?

## Plans
Use Reddit API to get comments of past 10 (~10000 comments) win post-game threads and 10 (~10000 comments)loss post-game threads. Classify each comment as win or lose based on the thread they are in. Analyze comments of win threads and loss threads to create the model. Then we predict by testing the model for next games. Each comment in each post-game thread will be classified as win or lose, with values set as 1 for win and 0 for lose. The values are then averaged and if > 0.5 the game would be predicted as a win. The model we come up with will be tested on threads with pre-determined outcomes. If the idea works, I would test it during real-time comments in the game thread and see if it can accurately predict.

Models that will be tested:
Naive Bayes. Logistic regression (MaxEnt), SVMs, and random forest.

## Reasoning
Rather than look at game stats and past matchups which is a great way to predict game outcomes, I decided to explore the idea of sentiment analysis and if that comments would be able to accuratelly predict outcomes.
