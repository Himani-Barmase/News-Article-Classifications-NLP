# News-Article-Classifications-NLP
his project focuses on classifying news articles into predefined categories such as sports, politics, and technology using Natural Language Processing (NLP) and supervised machine learning techniques. The goal is to automate the categorization of news content for better content organization and user experience.
Project Objective
To build a text classification model that accurately categorizes news articles based on their content. The project applies standard NLP preprocessing techniques and evaluates multiple machine learning algorithms to achieve high classification accuracy.

Data Preprocessing


Cleaned text data to remove special characters and unnecessary formatting.

Applied tokenization to break the text into words.

Removed stopwords to eliminate common words with little meaning.

Converted text to lowercase and standardized formatting for consistency.

Feature Extraction


Used TF-IDF (Term Frequency-Inverse Document Frequency) to transform text into numerical feature vectors.

Captured the relevance of words in context of their frequency across documents.

Model Development


Implemented supervised learning algorithms:

Logistic Regression

Naive Bayes

Support Vector Machine (SVM)

Applied cross-validation to ensure robust evaluation.

Performed hyperparameter tuning using Grid Search for improved performance.

Results and Insights
All models performed well, with SVM showing the highest accuracy on the validation set.

TF-IDF proved effective for feature representation in text classification.

The final model accurately classified news articles into categories, making it useful for content tagging and filtering.

Project Structure


News_Article_Classification.ipynb: Main notebook with all code and analysis

data/: Contains the dataset of news articles

visuals/: Includes charts and model performance visuals

README.md: Project documentation

Tools and Technologies
Python

Pandas, NumPy

Scikit-learn

NLTK

TF-IDF

Matplotlib, Seaborn

Jupyter Notebook
