# 🧠 Customer Churn Prediction using Deep Learning

Predicting customer churn is crucial for businesses to retain valuable customers and reduce loss. This project uses a deep learning model built with **Keras and TensorFlow** to classify whether a customer is likely to leave a service based on historical data.


# Project Highlights

-  Binary classification model using a feedforward neural network
-  Achieved **86.44% accuracy** on test data
-  Data preprocessing, feature scaling, and one-hot encoding
-  Model training, evaluation, and prediction visualization


# Behind the Dataset

This dataset captures real-world customer behavior from a subscription-based service. Each row represents a customer and includes:

-  Tenure
-  Payment Method
-  Internet Service
-  Contract Type
-  Monthly Charges & Total Charges
-  Demographics (e.g., gender, senior citizen status)

> What makes this dataset interesting is its reflection of **real human decisions**—why people stay loyal or why they leave. These insights can help businesses improve customer service, personalize offers, and build long-term relationships.



# Model Performance

 Metric           Value     

 Accuracy        | **0.8644** 
 Loss Function   | Binary Crossentropy
 Optimizer       | Adam      
 Output Layer    | Sigmoid Activation 
 Epochs Trained  | 10        

---

# Tech Stack

- Python 
- TensorFlow & Keras 
- Pandas & NumPy 
- Scikit-learn 
- Matplotlib & Seaborn 


# Features

-  Cleaned and preprocessed data
-  Feature encoding and scaling
-  Built and trained a deep neural network
-  Tracked model accuracy and loss over epochs
-  Predicted churn on test data
-  Optional: Confusion matrix and classification report


#Sample Output

```python
Test Accuracy: 86.44%
