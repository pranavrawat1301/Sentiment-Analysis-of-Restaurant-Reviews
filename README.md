# Sentiment-Analysis-of-Restaurant-Reviews
This NLP project analyzes restaurant reviews using the Bag of Words model. It preprocesses text data, implements the Bag of Words technique, and employs a Naive Bayes classifier for sentiment analysis. The accuracy and confusion matrix provide insights into the model's performance.

**Overview:**
This Natural Language Processing (NLP) project focuses on sentiment analysis of restaurant reviews. The code employs the Bag of Words model and utilizes the Natural Language Toolkit (NLTK) for text preprocessing. A Gaussian Naive Bayes classifier is trained on the processed data to categorize sentiments into positive or negative, and the model's accuracy is evaluated.

**Key Techniques:**
1. **Bag of Words (BoW) Model:**
   - Implements the BoW model for text representation, treating each document as an unordered set of words.
   - Converts the text data into a sparse matrix, capturing the frequency of each word across all documents.

2. **Natural Language Toolkit (NLTK):**
   - Utilizes NLTK for robust text preprocessing, including tokenization, stemming, and stopwords removal.
   - Enhances the quality of text data by removing non-informative words and reducing words to their root form.

3. **Naive Bayes Classification:**
   - Applies the Gaussian Naive Bayes classifier for sentiment analysis, a probabilistic model suitable for text categorization.
   - Trains the classifier on the BoW representation of reviews for sentiment categorization.

**Metrics and Evaluation:**
- **Confusion Matrix:** Evaluates the model's performance through correct and incorrect predictions breakdown.
- **Accuracy Score:** Quantifies the overall predictive accuracy of the model on the test set.

**Usage:**
1. **Text Preprocessing:**
   - NLTK is employed for tokenization, stemming, and stopwords removal.
   - BoW representation is generated, capturing the frequency of words across reviews.

2. **Classification:**
   - The Gaussian Naive Bayes classifier is trained on the BoW representation for sentiment analysis.
   - Predictions are made on a test set, and model accuracy is assessed.

**Contributions:**
Contributions are welcome, encompassing suggestions, improvements, and bug fixes. Engage through issues, feedback, or pull requests.

**Tools and Libraries:**
- Python, NumPy, Pandas, Matplotlib, scikit-learn, NLTK
