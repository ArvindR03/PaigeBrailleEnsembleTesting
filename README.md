# Ensemble Method Analysis

Conclusion: for the given use case of autoprediction for Braille users, it was important to choose a method that was simple to optimise and run, but also gave effective results.

As such the following method was chosen: Run a Random Forest Classifier to choose between an LSTM of length 5 and the fivegram model predictions.
