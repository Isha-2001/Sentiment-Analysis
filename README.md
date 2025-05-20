# Sentiment Analysis using Decision Tree

This project implements a sentiment analysis model to classify tweets as positive or negative using a Decision Tree classifier. The workflow involves cleaning and preprocessing textual data, extracting meaningful features, training a model, and evaluating its performance.

## Features

- Text cleaning and normalization, including URL removal and emoticon conversion  
- Expansion of chat abbreviations (e.g., LOL → laughing out loud)  
- Punctuation removal and lemmatization for better text representation  
- Tokenization of tweets  
- Feature Extraction: Converting text into numerical features using techniques like TF-IDF.
- Model Training: Training a Decision Tree classifier on the processed data.
- Evaluation: Assessing model performance using appropriate metrics.

## Getting Started

### Prerequisites

- Python 3.x  
- Jupyter Notebook  
- Required Python libraries:  
  - pandas  
  - numpy  
  - scikit-learn  
  - nltk  
  - matplotlib  
  - seaborn  
  - wordcloud  
  - pillow  
  - requests  

Install dependencies with:

```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn wordcloud pillow requests
```

## Text Preprocessing

The following steps are applied to clean and prepare the tweets for modeling:

  1. URL Removal: All URLs are removed using regular expressions.
  2. Emoticon Conversion: Emoticons are replaced by descriptive text to preserve emotional content.
  3. Chat Words Expansion: Common chat abbreviations are replaced by their expanded forms.
  4. Punctuation Removal: All punctuation characters are stripped from the tweets.
  5. Lemmatization: Words are reduced to their base form using NLTK’s WordNetLemmatizer.
  6. Tokenization: Tweets are split into individual tokens (words).

## Visualization

The notebook includes visualizations such as:

  - Word clouds for positive tweets
  - Bar plots showing the most frequent hashtags in positive and negative tweets

These visualizations help provide insights into sentiment-related trends.

## Dataset

The dataset used in this notebook consists of tweets labeled with sentiment classes. Please ensure that the dataset file is available in the project directory or update the paths in the notebook accordingly.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

scikit-learn for machine learning tools
NLTK for natural language processing utilities
WordCloud for word cloud visualizations


