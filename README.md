# Machine Learning (City Block Failure Risk Prediction)
This repository contains the code and experiments for a machine learning project that predicts failure risk for city blocks using logistic regression and related methods. The goal is to help prioritise blocks that may be at higher risk, rather than to guarantee that no failures will occur.


## Project overview
- Load and preprocess the city-block dataset (feature cleaning, encoding, train/validation/test split).
- Train and evaluate models (logistic regression, tree-based methods, neural networks where relevant).
- Assess performance with accuracy, confusion matrices, and cross‑validation.
- Interpret the model to discuss limitations, especially missed failures and false alarms.
  
### Model 
Logistic regression was used to predict whether a city block would experience a failure, based on features such as historical incidents and block characteristics. The model was trained on a labelled dataset using train/validation/test splits and cross‑validation to select the regularisation strength and reduce overfitting. Model performance was evaluated with accuracy scores, confusion matrices, and predicted probabilities, focusing on how well it separates higher‑risk from lower‑risk blocks.

