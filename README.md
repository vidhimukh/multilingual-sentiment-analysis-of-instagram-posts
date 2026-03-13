Multilingual Sentiment Analysis of Instagram Posts

Overview :

This project performs sentiment analysis on multilingual Instagram posts using transformer-based language models. The goal is to classify posts into sentiment categories such as positive, negative, or neutral while handling multiple languages.


Two powerful multilingual models were used :

- mBERT (Multilingual BERT)

- XLM-R (XLM-RoBERTa)

The performance of both models was evaluated using various classification metrics and visualizations.

Objectives :

- Analyze sentiment in Instagram posts written in multiple languages.

- Compare the performance of mBERT and XLM-R models.

- Evaluate model performance using classification metrics.

- Visualize results using graphs and confusion matrices.

Technologies Used :

- Python

- Transformers (Hugging Face)

- PyTorch

- Scikit-learn

- Pandas

- Matplotlib / Seaborn

Models Used :
- mBERT (Multilingual BERT) :

A multilingual version of BERT trained on Wikipedia data from multiple languages. It enables sentiment analysis across languages without training separate models.

- XLM-R (XLM-RoBERTa) :

A transformer model trained on a very large multilingual dataset. It generally performs better on multilingual NLP tasks due to its larger training corpus.

Evaluation Metrics :

The models were evaluated using the following metrics:

- Accuracy

- ROC Curve

- Confusion Matrix

These metrics help determine the effectiveness of each model in predicting sentiment correctly.

Visualizations :

The following visualizations were used to analyze the model performance:

- Confusion Matrix

- ROC Curve

Project Structure :

multilingual-sentiment-analysis-of-instagram-posts

notebooks/
visualizations/
README.md
requirements.txt
