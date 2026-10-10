# Email Spam Classifier 📧

## Project Overview
Developed an Email Spam Classifier using Machine Learning and Natural Language Processing (NLP) to classify messages as **Spam** or **Not Spam**. The application provides a simple, interactive interface built with Streamlit, allowing users to enter a message and receive an instant prediction.

## Technologies Used
- **Python** – Core programming language
- **Streamlit** – Interactive web application
- **NLTK** – Text preprocessing and stemming
- **Scikit-learn** – TF-IDF vectorization and machine learning prediction
- **Pickle** – Saving and loading the trained model and vectorizer

## Key Features
- Accepts user-input messages for classification
- Converts text to lowercase and tokenizes it
- Removes non-alphanumeric tokens and English stopwords
- Applies Porter Stemming to normalize words
- Converts text into numerical features using TF-IDF
- Predicts whether a message is spam or not spam
- Displays results through a user-friendly Streamlit interface

## How It Works
1. Enter a message in the text area.
2. The application preprocesses the message using NLP techniques.
3. The TF-IDF vectorizer converts the processed text into numerical features.
4. The trained machine learning model predicts the category.
5. The result is displayed as **Spam** or **Not Spam**.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Navigate to the project folder:
   ```bash
   cd YOUR_PROJECT_FOLDER
   ```

3. Install the required libraries:
   ```bash
   pip install streamlit nltk scikit-learn
   ```

4. Ensure the trained model and TF-IDF vectorizer pickle files are available in the project directory.

5. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Learning Outcomes
- Practical experience with NLP text preprocessing
- Understanding TF-IDF feature extraction
- Integrating a trained machine learning model into a web application
- Building an interactive application using Streamlit

## Project Goal
To demonstrate how machine learning and NLP can be used to identify spam messages and support safer digital communication.
