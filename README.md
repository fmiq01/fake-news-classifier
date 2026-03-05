
# Fake News Tweet Classifier

This project implements a machine learning pipeline for detecting fake vs real tweets using natural language processing and a neural network classifier.

The dataset consists of multiple CSV files containing tweets labelled as either fake or real. The data is combined, preprocessed, converted into numerical features using bag-of-words vectorization, and used to train a neural network model.

## Pipeline

1. Load multiple CSV datasets containing fake and real tweets
2. Combine datasets into a single dataframe
3. Preprocess tweet text:
   - Remove hyperlinks
   - Remove punctuation
   - Convert text to lowercase
   - Tokenize words
   - Apply stemming
   - Remove stopwords
4. Convert text into numerical features using `CountVectorizer`
5. Split the dataset into training and testing sets
6. Train a neural network classifier using TensorFlow/Keras
7. Evaluate model performance using accuracy and a confusion matrix

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn


