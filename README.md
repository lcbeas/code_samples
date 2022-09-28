# code_samples

1_create_syn_data - creates synthetic data that can be plugged in to replace real data. We use this synthetic data to analyze how well our model converges to "true" values, given data with the distribution we hypothesize.
2_preprocessing - creates player and course weights to be used in the modeling process

Two Model Versions:

1. pymc3_model - using pymc3, Bayesian approach -> model both benchmark (nodsr) and new hypothesis (dsr)

2. julia_model - using Julia optimizer -> model both benchmark (nodsr) and new hypothesis (dsr)

5_measurement - this script is used to determine how well the different model iterations perform on training set and test set. 
