# 📱 Social Media Usage & Emotional Well-Being Prediction

This project predicts a user’s dominant emotional state based on their social media usage patterns using Machine Learning and Deep Learning models.
It includes an interactive Streamlit web app where users can input their details and get real-time emotion predictions.

# 🚀 Features

Predicts Dominant Emotion from social media activity

Uses both Machine Learning (Random Forest) and Deep Learning (Neural Network)

Interactive Streamlit UI

Real-time user input and prediction

One-hot encoding and label encoding for categorical data

# 🧠 Models Used

1️⃣ Machine Learning Model

Random Forest Classifier

Handles non-linear relationships well

Robust to noise and overfitting

2️⃣ Deep Learning Model

Neural Network (Keras Sequential Model)

Dense layers with ReLU activation

Softmax output layer for multi-class emotion classification

# 📊 Dataset Description

The dataset contains social media usage information such as:

Age

Gender

Platform

Daily Usage Time (minutes)

Posts Per Day

Likes Received Per Day

Comments Received Per Day

Messages Sent Per Day

Dominant Emotion (Target Variable)

Files included:

train.csv

val.csv

test.csv

# 🛠️ Tech Stack

Python

Pandas & NumPy

Scikit-learn

TensorFlow / Keras

Streamlit


# ▶️ How to Run the Project

1️⃣ Clone the Repository
git clone https://github.com/Chaviverma/Social-Media-usage-and-Emotional-Wellbeing

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Streamlit App
streamlit run app.py

# 🎯 Output

Displays ML Prediction (Random Forest)

Displays DL Prediction (Neural Network)

Emotion results are shown instantly after clicking Predict Emotion


