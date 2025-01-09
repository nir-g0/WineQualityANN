# ANN with MLFlow Integration to Predict Wine Quality

This project demonstrates the use of an Artificial Neural Network (ANN) with MLFlow integration for predicting wine quality. It includes data preparation, model training, hyperparameter optimization, tracking, and deployment.

## Features and Workflow

1. **Data Preparation**  
   - Utilized data from the Keras Data Lake.  
   - Prepared and preprocessed the dataset for model training and evaluation.

2. **Model Training**  
   - Split the dataset into training, validation, and testing subsets.  
   - Employed a secondary training set split for fine-tuning, reserving the first split for data validation.

3. **Tracking Progress**  
   - Integrated MLFlow to log and track model performance metrics, parameters, and artifacts during training.  

4. **Hyperparameter Optimization**  
   - Utilized the `hyperopt` library for efficient hyperparameter tuning to optimize the ANN architecture.  

5. **Model Evaluation and Selection**  
   - Evaluated models using relevant metrics and hyperparameters to select the best-performing model.

6. **Deployment**  
   - Deployed the selected model as a REST API.  
   - Hosted and monitored the API via a containerized environment on a cloud platform.

## Tools and Technologies
- **Frameworks:** Keras, MLFlow  
- **Hyperparameter Optimization:** Hyperopt  
- **Deployment:** REST API, Cloud-based container platform  

## Highlights
- Streamlined integration of MLFlow for efficient experiment tracking.  
- Scalable deployment solution using cloud infrastructure and containerization.  
- Reproducible model training and evaluation with robust hyperparameter tuning.  
