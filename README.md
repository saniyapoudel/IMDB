 IMDB Movie Review Sentiment Analysis
Dataset & Problem:
The IMDB Dataset of 50K Movie Reviews contains movie reviews labeled as positive or negative. The goal of this project is to build an NLP model that automatically predicts the sentiment of a new movie review.

What I Did:
I loaded and inspected the dataset, performed EDA, checked missing values and duplicates, cleaned the review text, and converted sentiment labels into numerical values. I divided the data into training, validation, and testing sets. I used TF-IDF vectorization** to convert text into numerical features and trained **Logistic Regression and Naive Bayes** models.

Why I Made These Decisions:
Text cannot be directly used by traditional machine-learning models, so TF-IDF was selected to represent important words and word combinations numerically. Logistic Regression and Naive Bayes were selected because they are suitable and efficient for text classification. Validation data was used to compare the models, while the test data was kept separate for final evaluation.

How I Implemented It:
The project was implemented in Python using Pandas, Scikit-learn, Matplotlib, Seaborn, and Joblib. Models were evaluated using accuracy, precision, recall, F1-score, and a confusion matrix**. The final TF-IDF and trained model were saved as a single pipeline. A simple GUI prototype was created to allow users to enter a movie review and receive a sentiment prediction.

Key Results & Findings:
The project demonstrates that TF-IDF-based machine-learning models can effectively classify movie reviews into positive and negative sentiments. The two models were compared using validation results, and the better-performing approach was selected for final testing. The saved model and GUI provide a working prototype for predicting the sentiment of new movie reviews.
