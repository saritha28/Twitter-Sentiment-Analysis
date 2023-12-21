# Twitter Sentiment Analysis

## Overview
This project conducts sentiment analysis on a dataset containing 1.6 million tweets sourced from Kaggle. The primary objective is to classify tweet sentiments using Natural Language Processing (NLP) techniques and machine learning models.

## Dataset Details
- **Source**: Kaggle dataset comprising 1.6 million tweets.
- **Columns**: Target, IDs, Date, Flag, User, Text.

## Tools and Techniques Utilized
- **Text Processing**: Leveraged NLTK for text processing, encompassing stemming, stopwords removal, and text standardization.
- **Sentiment Analysis**: Computed polarity and subjectivity metrics via NLP methods.
- **Visualization**: Implemented WordCloud, Matplotlib, and Seaborn for comprehensive data visualization.
- **Vectorization**: Employed TF-IDF Vectorization for effective handling of textual data.
- **Model Building**: Utilized Logistic Regression, Naive Bayes Classifier, Random Forest, and Support Vector Classifier (SVC).
- **Encoding**: Converted sentiments to numeric variables through Label Encoder.

## Methodology
1. **Data Cleaning**: Eliminated noise, addressed missing values, and standardized text data.
2. **Text Processing**: Employed stemming and stopwords removal to prepare text data for analysis.
3. **Sentiment Analysis**: Calculated polarity and subjectivity, providing insights into sentiment distributions.
4. **Visualization**: Generated WordClouds, visualized sentiment distributions using Matplotlib and Seaborn.
5. **Model Building**: Developed machine learning models including Logistic Regression, Naive Bayes, Random Forest, and SVC.
6. **Evaluation**: Assessed model performance, achieving:
   - Logistic Regression: 83% accuracy
   - Naive Bayes Classifier: 81% accuracy
   - Random Forest: 93% accuracy
   - Support Vector Classifier (SVC): 90% accuracy

## Usage
- **Data Exploration**: Explore the dataset for insights into tweet sentiments and their distributions.
- **Text Processing**: Apply NLTK techniques for efficient text cleaning and preparation.
- **Visualizations**: Utilize visualizations to comprehend sentiment distributions effectively.
- **Model Building**: Employ various classifiers for sentiment classification and evaluation of performance.

## Included Files
- Jupyter Notebook: Contains the code for data processing, analysis, and model development.
- Dataset: The original dataset utilized for sentiment analysis.

## Future Enhancements
- Experiment with advanced feature engineering techniques.
- Explore deep learning models for sentiment analysis improvement.

## Acknowledgments
- Kaggle for providing the dataset.
- Acknowledgment to NLTK, Matplotlib, Seaborn, and scikit-learn libraries used in this project.
  
## Power BI Link
https://app.powerbi.com/links/6ofBP6MeUS?ctid=fc42da63-a990-45bc-8143-320165150d3c&pbi_source=linkShare&bookmarkGuid=1681bf86-21b7-4141-92a3-e8dfbe6ab4ab

