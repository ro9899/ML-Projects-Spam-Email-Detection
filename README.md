# Machine Learning-Projects-Spam-Email-Detection
AI-powered spam email classification using TensorFlow and LSTM.
# AI-Powered Spam Email Classification Using TensorFlow

## Problem Statement

Spam emails are unwanted messages that are often sent in large numbers and may contain advertisements, scams, or potentially harmful content. Identifying these emails manually can be difficult and time-consuming.

This project aims to develop an AI-based spam email classification system using Python and TensorFlow. The model analyzes email content and classifies each message into two categories: **Spam** or **Ham (Not Spam)**.

## Technologies Used

- Python
- TensorFlow
- Pandas
- NumPy
- NLTK
- Matplotlib
- WordCloud
- Scikit-learn

## Project Workflow

1. Import Required Libraries
2. Load the Dataset
3. Balance the Dataset
4. Clean the Text
5. Visualize Data Using Word Cloud
6. Tokenization and Padding
7. Define the Deep Learning Model
8. Train the Model
9. Evaluate the Model

## Model Architecture

The model uses a Sequential deep learning architecture consisting of:

- **Embedding Layer** – Converts words into numerical vector representations.
- **LSTM Layer** – Learns patterns and relationships between words.
- **Fully Connected Layer** – Extracts useful features for classification.
- **Output Layer** – Classifies the email as Spam or Ham.

## Model Training

The model is trained using TensorFlow with **EarlyStopping** and **ReduceLROnPlateau** callbacks.

These callbacks help prevent unnecessary training and adjust the learning rate when the model's performance stops improving.

## Model Performance

The trained model was evaluated on unseen test data.

- **Test Accuracy:** 96.50%
- **Test Loss:** 0.1663

The results show that the model performs well in distinguishing between Spam and Ham emails.

## Conclusion

This project successfully demonstrates how deep learning and natural language processing can be used to automatically detect spam emails.

With further improvements in preprocessing, model architecture, and hyperparameter tuning, the model's performance could potentially be improved further.

## Project Notebook

The complete implementation is available in the Jupyter Notebook:

`ML-Projects-Spam-Email-Detection.ipynb`
