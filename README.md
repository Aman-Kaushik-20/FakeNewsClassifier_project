# FakeNewsClassifier_project

**Project Description: Fake News Classification **

- **Data Preprocessing:** Conducted data cleaning tasks including removal of punctuations and conversion of text to lowercase to enhance the quality of the dataset for analysis. Null values were eliminated to ensure data integrity.

- **Feature Engineering:** Utilized techniques such as CountVectorizer and tfidf  to convert textual data (news articles) into numerical features, crucial for training machine learning models. Employed n-grams to capture contextual information and enhance feature representation.

- **Model Training and Evaluation:**
  - Implemented the Multinomial Naive Bayes classifier, suitable for handling text classification tasks with multiple categories of output. Achieved an accuracy score of [insert accuracy score here] on the test dataset.
  - Utilized the Passive Aggressive Classifier algorithm to further explore model performance, achieving an accuracy score of [insert accuracy score here]. Confusion matrices were employed to visualize model performance and identify areas for improvement.
  - Experimented with Multinomial Classifier with Hyperparameter tuning to optimize model performance. Varied alpha values were tested to identify the optimal configuration.

- **Feature Importance Analysis:** Conducted analysis to identify the most significant features (words) contributing to classification decisions. Words with higher probability values were considered more indicative of real news, while those with lower values were associated with fake news.
