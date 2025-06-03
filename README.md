Predicting Applicant Success for Alphabet Soup

Project Overview

This project builds a binary classification model to help Alphabet Soup determine which applicants have the highest likelihood of success if funded. Using machine learning and deep neural networks, we preprocess the dataset, design an optimized model, and evaluate its performance to ensure accurate predictions.

First, we loaded and preprocessed the dataset by removing non-beneficial columns (EIN, NAME, etc.) and encoding categorical data with pd.get_dummies().  After preprocessing, we split the data into training and testing sets using train_test_split().

Next, I designed a deep neural network (DNN) with 2 hidden layers.The architecture included LeakyReLU activations. I Then compiled the model using the Adam optimizer with binary_crossentropy as the loss function and trained it for various epochs with a batch sizes

After training, we evaluated the model’s performance using accuracy and loss metrics. Initially, accuracy hovered around 53.5%, indicating room for improvement. To enhance performance, we refined hyperparameters, adjusted layer sizes, modified activation functions, and fine-tuned dropout rates. We also visualized model accuracy over epochs to identify training trends.However after all that I reverted to my orginal model as had the highest degree of accuracy. I still 

While the deep learning model provides valuable predictions, I thought of alternative models such as XGBoost and Deep Forest, which might be better suited for structured data. These models offer higher interpretability and require less fine-tuning compared to neural networks. With othe the model there are using the right one for the right task can be a challenge.


