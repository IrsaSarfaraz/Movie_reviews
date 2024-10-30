## Sentiment Analysis on IMDB Reviews 
Overview
This project applies NLP techniques to analyze movie reviews from the IMDB dataset, classifying them as positive or negative using Logistic Regression.

### Technologies Used
Python (Pandas, NLTK, Scikit-learn)
Google Colab for execution
### Dataset
IMDB 50K Movie Reviews
### Steps
### Preprocessing: Tokenization, lowercasing, stopword removal
TF-IDF Vectorization: Extract features from text
Training: Logistic Regression
Evaluation: Achieved 85% accuracy
### Usage
Run the notebook on Google Colab:
Upload the dataset
Run preprocessing and training steps
### Test with new reviews:
new_reviews = ["Amazing movie!", "Terrible film."]
predictions = model.predict(vectorizer.transform(new_reviews))
print(predictions)
### Future Improvements
Use advanced models (SVM, RandomForest)
Add bigrams/trigrams in TF-IDF
Experiment with word embeddings (GloVe, Word2Vec)
