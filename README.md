Fine tuning the BERT LLM for essay grading.

I take a neural network based ordinal regression approach to the problem, and add a classifier at the end of the LLM to fintune.

The metric is [Quadratic Weighted Kappa](https://www.kaggle.com/code/prashant111/simple-explanation-of-quadratic-weighted-kappa) and I achieved a score of 0.78 on the test set. 
