# Fine-tuning_GPT-2_news_classifier


This project is a part of a Machine Learning course. 

# Creation of custom dataset:

The data was scraped from multiple technological websites and political news websites using newspaper3k. This was used to create a custom dataset by filtering only English news(which can be found in news_data.csv). The dataset was then used to fine-tune a GPT-2 transformer model to classify the news articles into technology and politics. An example of prediction is also shown. 

The validation accuracy is 86.1% and the train accuracy is 67.1 %. The test Accuracy is 86.7%. We can improve this by scraping more news articles from different websites and increasing the train size of the model. Additionally, different pre-trained transformer models (including BERT, BART, Roberta) or a transformer model fine-tuned for news articles (in HuggingFace )can be used to see which one performs better on large training data and this use case.

Another way to increase the accuracy would be to use different contexts of technological data and political data rather than just news articles to make the model truly understand such aspects.
