# fake_news_prediction
This project focuses on predicting whether a news article is fake or real using machine learning techniques. It utilizes a logistic regression model with TF-IDF vectorization to classify news articles.
## Dataset
The dataset used for this project is obtained from the file 'train.csv.zip', which contains news articles along with their labels (fake or real).
The following features are used for prediction:

Content: The combined text of the author and title of the news article.

## Usage
* Install the required dependencies. You can install them using the following command:
    pip install pandas nltk scikit-learn
* Additionally, download the necessary NLTK stopwords by running the following command:
    nltk.download('stopwords')
### Data Preprocessing
