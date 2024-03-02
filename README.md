# DataMining

Product Review Classification
Implemented a logistic regression classifier to predict sentiment for 18,506 reviews of baby products with an accuracy of 0.85. Preprocessed the data by cleaning and converting it into lowercase, removing numbers and special characters, and applying lemmatization. Stopwords were removed and created a vector of TF-IDF features using sklearn's TfidfVectorizer with a max_features of 1000 and an ngram range of (1,2).

Image Data Classification
• Implemented K-means clustering algorithm & evaluated the Iris dataset with 95% accuracy.
• Explored the algorithm with Image data handwritten digits (0-9) data sets and applied dimensionality reduction using PCA;T-SNE and improved error rate by 25%.
• Engineered internal evaluation metric for comparing solutions of clustering algorithm on Iris and Image datasets, providing quantitative feedback on individual clusters & entire solutions increasing accuracy by 20%.

Heart Rate Disease Prediction
• Implemented Gradient Descent Algorithm from scratch and successfully trained Logistic Regression model for the Cleveland Dataset, resulting in 81.38% correct classification of the heart disease result.
• Developed cross-entropy error, training set error, and test set errors to accurately calculate generalization and compared results with the Sklearn Logistic Regression model with an accuracy rating of 85%.

Bias in Language Models
Explored the implicit bias encoded in natural language word embedding using GloVe based word embedding models trained on large data sets of examples of human language like Wikipedia (50d,100d,200d,300d) and Twitter(25d,50d,100d,200d).
Observed the learnings of computers of the underlying meaning of the human understandings of fairly similar words through assigning similar vector values using word2vec.
