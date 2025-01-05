# Amazon Product Reviews Classification

This project is a machine learning-based web application for classifying Amazon product reviews into positive or negative sentiments. It uses natural language processing techniques and a Logistic Regression model for sentiment analysis.

## Features
- **Sentiment Analysis**: Predicts whether a given product review is positive or negative.
- **Interactive Web Interface**: A user-friendly Flask-based interface for submitting and analyzing reviews.
- **Pretrained Model**: Includes a trained Logistic Regression model using TF-IDF vectorization.

## Files in the Repository
- **analysis.py**: Preprocesses the dataset, trains the sentiment analysis model, and saves the model and vectorizer.
- **model.py**: Defines functions for cleaning, lemmatizing, and predicting sentiment using the trained model.
- **app.py**: Flask application to serve the web interface and handle predictions.
- **templates/index.html**: The front-end HTML for user input and displaying predictions.

## Dataset
The dataset used for training is not included in the repository due to its size. You can download it from the following link:  
[Reviews.csv](https://drive.google.com/file/d/1KHGp1Kzdo7jP0DE7Dt4T78EaBTZ5Xolo/view?usp=drive_link)

## How to Run the Application
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Download the dataset and place it in the repository.
4. Run `analysis.py` to preprocess the dataset and train the model.
5. Start the Flask application using `python app.py`.
6. Open your browser and navigate to `http://127.0.0.1:5000/`.

## Requirements
- Python 3.x
- Flask
- Scikit-learn
- NLTK
- Pandas
- Joblib

## Author
**Bhavya Gajjarapu**  
This project demonstrates skills in natural language processing, machine learning, and Flask web development.
