# Twitter-sentiment-analysis

# Project overview

This project demonstrates the application of Big Data techniques and tools to perform sentiment analysis on Twitter (now X) data. The focus was on analyzing tweets related to Artificial Intelligence (AI) collected between December 8th and 9th, 2022. The goal was to develop a model capable of predicting the sentiment of tweets and to analyze the resulting labeled dataset through visualizations.

# Objetives
The primary objective of this project was to develop a sentiment analysis model using tweets extracted from the web, followed by a detailed analysis of the dataset and model performance. This analysis aims to uncover key trends and patterns in public sentiment regarding AI during this time frame.

# Technologies & Tools
- **Programming language:** Python
- **Development environment:** Jupyter Notebook
- **Libraries & frameworks:**
  - **Data processing & analysis:** DataBricks, PySpark, RE (regular expressions), TextBlob, Amazon Athena
  - **Data visualization:** Quicksight
  - **Modeling and evalution**:  DataBricks, PySpark
 
# Skills employed in the project
- **Data wrangling:** performed data preprocessing, including cleaning and transformation, to prepare the dataset for analysis and model development.
- **Data visualization:** built visualizations to uncover trends and relationships in the dataset, providing insights into sentiment patterns expressed in tweets about AI.
- **Machine learning & Natural Language Processing (NLP): developed a sentiment classification model using machine learning algorithms to predict the sentiment of tweets based on textual features.
- **Model selection**: analyzing performance metrics such as accuracy precision, recall, and F1-score to decide on the most suited model to address the problem.
- **Report writing & documentation:** synthesizing findings and presenting results through detailed visualizations and concise textual summaries to aid data-driven decision-making.

# Key Insights and Model Performance

- Logistic Regression was identified as the most effective model for sentiment prediction, achieving an accuracy of 90% and an F1-score of 90%. L This means the model correctly predicted the sentiment of 90% of the tweets. Additionally, the model achieved a well-balanced performance, meaning it was good at both identifying positive, neutral, and negative sentiments without favoring one over the other.
- The sentiment breakdown of the dataset revealed that approximately 51% of tweets expressed negative sentiment, 31% were positive, and 19% were neutral. Therefore, as of December 2022, the majority of tweets related to AI conveyed negative sentiment.
- Negative manifestations of sentiments towards AI were more polarized than the expression of posivite sentiments. In other words, extreme negative manifestation was more common than positive ones.

For an visual presentation of the project, visit: https://github.com/diogofn1/Twitter-sentiment-analysis/blob/main/Twitter%20sentiment%20analysis%20-%20Presentation.pdf.
