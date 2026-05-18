# gutenberg-books-classification-using-nlp

https://www.gutenberg.org/

## Genre Identification on (a sub-set of) Gutenberg Corpus

Consider this set of books belonging to the 19th Century English Fiction1. The data set is created from Project Gutenberg2. The data set consists of about 1000 books and roughly 10 genres. The task here consists of detection (i.e. classification) of genre3 of a book. Each
data-point in this classification task is a fiction book with a label (genre).

## ML techniques used

1. Stopword removal using NLTK
2. Bag of Words
3. PCA
4. Word Cloud
5. Emotion Analysis - NRC word lexicon
6. Sentiment Analysis - Valence Aware Dictionary and sentiment Reasoned
7. TF-IDF Vectorizer
8. K-Fold Cross Validantion
9. Oversampling - random oversampling, SMOTE-NC and Adaptive Synthetic Sampling (ADASYN)
10. SVM, Logistic Regression, SGD Classifier, KNN, Decision Tree, Gaussian NB, Random Forest


