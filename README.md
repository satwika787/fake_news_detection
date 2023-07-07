# Fake News Detection

This project aims to predict whether a news article is real or fake using machine learning techniques. The prediction is based on the content of the news articles and uses **natural language processing techniques**.

## Dataset

The dataset used for this project is the training dataset in CSV format. It contains information about news articles, including their authors, titles, and labels (real or fake). Link to the dataset : 'https://www.kaggle.com/competitions/fake-news/data?select=train.csv'

## Usage

* Install the required dependencies. You can install them using the following command:
    _pip install pandas nltk scikit-learn_
* Additionally, download the necessary NLTK stopwords by running the following command:
    _nltk.download('stopwords')_

## Natural Language Processing

To preprocess the textual data, the following natural language processing techniques are applied:

* Removal of special characters and non-alphabetic characters.
* Conversion to lowercase.
* Tokenization and stemming using the PorterStemmer algorithm.
* Removal of stop words.

## Model Training and Evaluation

The project utilizes the **TF-IDF (Term Frequency-Inverse Document Frequency) vectorization** technique to convert the textual data into numerical features. The **logistic regression** algorithm is then used to train a classification model.

* The model is evaluated using the **F1 score** and **accuracy metrics** on both the training and testing datasets.
* Finally, you can test the model by providing new text data and obtaining the predicted label (fake or real).

### Future Improvements 

* Incorporating additional features, such as  social network information, to provide more context for the prediction.
* Collecting a larger and more diverse dataset to train the model, potentially reducing biases and improving generalization.

