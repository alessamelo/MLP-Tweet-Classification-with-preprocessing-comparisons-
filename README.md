# MLP-Tweet-Classification-with-preprocessing-comparisons-
This project explores the classification of tweets related to real disasters using a **Multi-Layer Perceptron (MLP)** neural network. The objective is to automatically distinguish between tweets that describe actual disaster events and those that do not.

The study focuses on evaluating the impact of different **text preprocessing strategies** on the performance of the classification model. Three preprocessing configurations are implemented and compared:

1. **Basic text cleaning** – lowercase conversion, removal of URLs, mentions, and punctuation.
2. **Stopword removal** – applying basic cleaning and removing common English stopwords.
3. **Lemmatization** – applying basic cleaning and reducing words to their base form.

Tweets are transformed into numerical representations using **TF-IDF vectorization**, and a neural network model is trained to classify them. The performance of each preprocessing configuration is evaluated using metrics such as **accuracy, precision, recall, F1-score, and AUC**, allowing a comparison of how different text cleaning techniques affect model performance.

This project demonstrates how preprocessing decisions influence the effectiveness of machine learning models in **natural language processing tasks**.

